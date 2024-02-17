# Braun Extension Pack

A collection of vscode plugins that makes it more productive (and cool).

You can install it from the marketplace [here](https://marketplace.visualstudio.com/items?itemName=matheeusbl.braun-extension-pack).

## Included Extensions

- [Apc Customize UI++](https://marketplace.visualstudio.com/items?itemName=drcika.apc-extension) - Allows customization outside vscode scoop.

- [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit) - Official C# extension from Microsoft.

- [C# Namespace Autocompletion](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.namespace) - Full namespace autocompletion for C#.

- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) - Spelling checker for source code.

- [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) - Highlights colors in your editor.

- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig) - Attempts to override user/workspace settings with settings found in `.editorconfig` files.

- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) - Improve highlighting of errors, warnings and other language diagnostics.

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) - Integrates ESLint into VS Code.

- [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot) - AI from GitHub that helps increase your productivity. It costs $10 monthly to use or $100 yearly.

- [GitLens - Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) - Supercharges the Git capabilities built into Visual Studio Code. It helps you to visualize code authorship at a glance via Git blame annotations and code lens.

- [Highlight](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-highlight) - Advanced text highlighter based on regexes. Useful for todos, annotations, colors etc.

- [Min Theme](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.min-theme) - A minimal theme for VS Code that comes in dark and light.

- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - Enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

- [Pretty Typescript Errors](https://marketplace.visualstudio.com/items?itemName=yoavbls.pretty-ts-errors) - Make TypeScript errors prettier and human-readable in VSCode.

- [Prisma](https://marketplace.visualstudio.com/items?itemName=Prisma.prisma) - Adds syntax highlighting, linting, code completion, formatting, jump-to-definition and more for Prisma Schema files.

- [Symbols](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols) - A simple file icon theme for VS Code.

- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) - Enhances the Tailwind development experience by providing Visual Studio Code users with advanced features such as autocomplete, syntax highlighting, and linting.

## Do you want to install just a few extensions?

To install just a few extensions, you need to edit the [package.json](package.json) removing the unwanted extensions from `extensionPack` and after that just follow the steps below to install it locally.

## How to develop and install it locally

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
