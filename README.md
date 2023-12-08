# Scarpet for Kate (KSyntaxHighlighting)

Full Syntax Highlighting support for Scarpet in [Kate](https://kate-editor.org/) through KSyntaxHighlighting with complete theming support.

Kate is an open source, cross platform, versatile text editor made by KDE.

Scarpet is a scripting language for Minecraft supported by Gnembon's [Carpet Mod](https://github.com/gnembon/fabric-carpet).

## Features

- Any complete theme is compatible as all styles used are default styles.
- Syntax highlighting: comments, control flow, keywords, operators, constants, function calls and definitions, global variables and strings
- Code folding for maps `{}`, lists `[]` and blocks `()`
- Minecraft API highlighting
- Minecraft Event API highlighting
- Deprecated APIs are ~~strikethrough~~
- Autocompletion for keywords and built-in functions
- Partial support for printf-like sequences in strings (e.g. `'%s %d %.2f'`)

## Screenshots

![Github Dark Theme Screenshot](./screenshot/github_dark.png "Github Dark Theme Screenshot")

![Monokai Theme Screenshot](./screenshot/monokai.png "Monokai Theme Screenshot")

## Installation
Download or move [`scarpet.xml`](./scarpet.xml) to one of the following folders, depending on the platform (or how Kate was installed).

You may need to create the directories if they are not present.

| Platform              | Directory                                                                               |
|-----------------------|-----------------------------------------------------------------------------------------|
| On Windows®           | `%USERPROFILE%\AppData\Local\org.kde.syntax-highlighting\syntax`                        |
| For local user        | `$HOME/.local/share/org.kde.syntax-highlighting/syntax/`                                |
| For all users         | `/usr/share/org.kde.syntax-highlighting/syntax/`                                        |
| For Flatpak packages  | `$HOME/.var/app/flatpak-package-name/data/org.kde.syntax-highlighting/syntax/`          |
| For Snap packages     | `$HOME/snap/snap-package-name/current/.local/share/org.kde.syntax-highlighting/syntax/` |
