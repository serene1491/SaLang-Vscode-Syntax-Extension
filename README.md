# SaLang Syntax Highlight

Extension for syntax highlighting, themes and snippets of the SaLang language.
Why would you install this? Idk, it's just a language I developed in my spare time.

## Features

- Support for comments, strings, variables, and functions.
- Custom dark and light themes.
- Snippets for rapid development.

## Installation

Download the `.vsix` from the [latest release](https://github.com/serene1491/SaLang-Vscode-Syntax-Extension/releases) and install with:
```bash
code --install-extension SaLangHighLightVscExtension.vsix
```

On Linux / WSL / Git Bash:

```bash
wget -O salang.vsix https://github.com/serene1491/SaLang-Vscode-Syntax-Extension/releases/download/0.1.0/SaLangHighLightVscExtension.vsix && code --install-extension salang.vsix && rm salang.vsix
```

On Windows

```bash
curl -L -o salang.vsix https://github.com/serene1491/SaLang-Vscode-Syntax-Extension/releases/download/0.1.0/SaLangHighLightVscExtension.vsix && code --install-extension salang.vsix && del salang.vsix
```

## License

MIT
