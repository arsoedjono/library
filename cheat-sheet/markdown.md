# Markdown Cheat Sheet

## Heading

```markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6 {#custom-id}

[Link to Heading 1](#heading-1)
[Link to Heading 6](#custom-id)
```

## Formatting

```markdown
*italic* or _italic_
**bold** or __bold__
**_bold and italic_**
a**very**important*messsage*

~~strikethrough~~
==highlight==
Sub~script~
Super^script^
```

NB: use asterisks `*` instead of underscores `_` to emphasize in the middle of a word

## Blockquotes

```markdown
> level 1
>> level 2
```

## List

```markdown
1. ordered
2. list

- unordered
- list

- [x] Checked list
- [ ] Unchecked list
```

## Code

```markdown
`one line`

\```<lang>
multiple
line
code
\```
```

NB: remove the backslash for multiple line code - enclose with triple backticks

## Horizontal Rule

```markdown
***
---
___
```

## Link

```markdown
[Google](https://www.google.com/)
[Google with Title](https://www.google.com/ "Best Search Engine")

[Google with Reference][link]
[Google with Reference And Title][link-title]
[link]: https://www.google.com/
[link]: https://www.google.com/ "Best Search Engine"

<https://www.google.com> or just https://www.google.com
<my@email.com>
```

## Image

```markdown
![San Juan Mountains](/assets/images/san-juan-mountains.jpg "San Juan Mountains")
```

## Table

```markdown
| Header | Header |
| --- | --- |
| Content | Content |

Alignment
| Header Left | Header Middle | Header Right |
| :--- | :---: | ---: |
| Content Left | Content Middle | Content Right |
```

## Footnote

```markdown
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.
```

## Diagram

Use `mermaid` language for multi-line code: https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/
