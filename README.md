# Scarpet for Kate
### Full Syntax Highlighting for KSyntaxHighlighing (Kate)

Full syntax highlighting support for Scarpet in [Kate (KDE)](https://kate-editor.org/).

Scarpet is a scripting language for Minecraft supported by [Carpet Mod](https://github.com/gnembon/fabric-carpet).

Kate is an open source, cross platform, versatile text editor made by KDE.

## Installation
To install the syntax highlighting support file, download [`scarpet.xml`](./scarpet.xml) and move it to one of the following folders,
depending on your platform (or how Kate was installed).

You may need to create the directories if they are not present.

| Platform              | Directory                                                                               |
|-----------------------|-----------------------------------------------------------------------------------------|
| On Windows®           | `%USERPROFILE%\AppData\Local\org.kde.syntax-highlighting\syntax`                        |
| For local user        | `$HOME/.local/share/org.kde.syntax-highlighting/syntax/`                                |
| For all users         | `/usr/share/org.kde.syntax-highlighting/syntax/`                                        |
| For Flatpak packages  | `$HOME/.var/app/flatpak-package-name/data/org.kde.syntax-highlighting/syntax/`          |
| For Snap packages     | `$HOME/snap/snap-package-name/current/.local/share/org.kde.syntax-highlighting/syntax/` |
