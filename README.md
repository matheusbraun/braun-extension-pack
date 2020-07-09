# Braun Extension Pack

A collection of vscode plugins that makes it more productive (and cool).

## Included Extensions

- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - Allows matching brackets to be identified with colours.

- [Dracula Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula) - A dark theme for VS Code.

- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - Attempts to override user/workspace settings with settings found in `.editorconfig` files.

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integrates ESLint into VS Code.

- [GitLens - Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - Supercharges the Git capabilities built into Visual Studio Code. It helps you to visualize code authorship at a glance via Git blame annotations and code lens.

- [Live Share Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare-pack) - Includes everything you need to start collaboratively editing and debugging in real time, including integrated audio and text chat.

- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=kief.material-icon-theme) - Customize your folders/files icons.

- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - Enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

## Do you want to install just a few extensions?

To install just a few extensions, you need to edit the [package.json](package.json) removing the unwanted extensions from `extensionPack` and after that just follow the steps below to install it locally.

## Hot to develop and install it locally

- Clone the repository

```bash
$ git clone https://github.com/matheeusbl/braun-extension-pack
```

- Install vsce

```bash
$ npm i -g vsce
```

- Generate the extension package

```bash
$ vsce package
```

- Install the extension through the file `.vsix`

1. Open VS Code
2. Select **Extensions** menu
3. Click in **More** > **Install from VSIX...**
4. Select the file `braun-extension-pack-x.x.x.vsix`
5. Click in **Reload Now** to reaload VS Code
