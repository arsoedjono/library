# Visual Studio Code Extensions

## Extensions

### Git

- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

### Linter

- [Rubocop](https://marketplace.visualstudio.com/items?itemName=misogi.ruby-rubocop) (does not support RVM)

### Looks

- [File Icons](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Markdown Table Prettifier](https://marketplace.visualstudio.com/items?itemName=darkriszty.markdown-table-prettify) (can also be used for Cucumber tables)

### Programming Language

- [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
- [Cucumber](https://marketplace.visualstudio.com/items?itemName=alexkrechik.cucumberautocomplete)
```json
{
  "cucumberautocomplete.steps": [
    "features/step_definitions/**/*.rb"
  ],
  "cucumberautocomplete.strictGherkinCompletion": true
}
```
- [Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby) (problem on using Rubocop as linter)

## Fonts

### Fira Code

#### How to

1. Download font -> https://github.com/tonsky/FiraCode#download-v2--how-to-install--troubleshooting--news--updates
2. Unzip, select all fonts, open, and install
3. Open VSCode settings > Text Editor > Font
4. Set `Font Family` to `Fira Code`
5. Add these to `settings.json`
```json
{
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
}
```

#### References
- [Instagram Link](https://www.instagram.com/p/B6TQ_Q0IBrq/?igshid=1pi5e2qiy1cx8)
- [Github](https://github.com/tonsky/FiraCode)
  - [Instructions](https://github.com/tonsky/FiraCode/wiki/VS-Code-Instructions)
