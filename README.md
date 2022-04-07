# BagPacker Extensions Pack

<!-- [![Version](https://vsmarketplacebadge.apphb.com/version/codeSTACKr.superhero-extensions.svg?subject=SuperHero%20Extensions&colorA=09131b&colorB=ff652f)](https://marketplace.visualstudio.com/items?itemName=codeSTACKr.superhero-extensions)
[![Rating](https://vsmarketplacebadge.apphb.com/rating-short/codeSTACKr.superhero-extensions.svg?label=Ratings&colorA=09131b&colorB=ff652f)](https://marketplace.visualstudio.com/items?itemName=codeSTACKr.superhero-extensions&ssr=false#review-details)
[![Become A VS Code SuperHero](https://img.shields.io/badge/-Become%20A%20VS%20Code%20SuperHero%20%E2%86%92-gray.svg?colorB=ff652f)](http://vsCodeHero.com) -->

Thanks for checking out my VS Code BagPack extension pack.

## Included Extensions


### Apollo GraphQL


Rich editor support for GraphQL client and server development that seamlessly integrates with the Apollo platform


### Auto Rename Tag

<img src="https://raw.githubusercontent.com/codeSTACKr/superhero-extensions/master/images/ext_autorename.jpg" alt="Auto Rename Tag" width="60%" />

This one automatically renames the corresponding tag that you modify. This is just a helpful time-saver.

### Prettier

<img src="https://raw.githubusercontent.com/codeSTACKr/superhero-extensions/master/images/ext_prettier.jpg" alt="Prettier" width="60%" />

This extension keeps your code formatted and uniform throughout.

### Live Server

<img src="https://raw.githubusercontent.com/codeSTACKr/superhero-extensions/master/images/ext_liveserver.jpg" alt="Live Server" width="60%" />

This extension sets up a local web server so that you can see the changes made in real-time without having to reload. It’s a must-have for web development.

### Better Comments

<img src="https://raw.githubusercontent.com/codeSTACKr/superhero-extensions/master/images/ext_bettercomments.jpg" alt="Better Comments" width="60%" />

This extension helps to make your comments stand out.

### HTML CSS Support

<img src="https://raw.githubusercontent.com/codeSTACKr/superhero-extensions/master/images/ext_htmlcsssupport.jpg" alt="HTML CSS Support" width="60%" />

Here are a few key features this extension adds:

- Class attribute completion.
- Id attribute completion.
- Scans workspace folder for CSS and SCSS files.
- Supports remote css files.

### GitLens

<img src="https://raw.githubusercontent.com/codeSTACKr/superhero-extensions/master/images/gitlens.jpg" alt="GitLens" width="60%" />

GitLens supercharges the Git functionality within VS Code. Easily see who made changes to code, when they made the changes, and why they made them.

## Install

```
code --install-extension bag-packer-0.0.1.vsix
```

## Settings

```
{
  "window.zoomLevel": 2,
  "explorer.confirmDragAndDrop": false,
  "javascript.validate.enable": false,
  "editor.formatOnPaste": true,
  "editor.snippetSuggestions": "top",
  "files.autoSave": "afterDelay",
  "files.autoSaveDelay": 100,
  "editor.fontSize": 20,
  "better-comments.multilineComments": true,
  "better-comments.highlightPlainText": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "better-comments.tags": [
    {
      "tag": "!",
      "color": "#D84727",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "?",
      "color": "#5EB1BF",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "//",
      "color": "#9BC53D",
      "strikethrough": true,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "todo",
      "color": "#EF7B45",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "*",
      "color": "#3F612D",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    }
  ],
  "terminal.integrated.profiles.linux": { "bash": { "path": "/bin/bash" } },
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[go]": {
    "editor.insertSpaces": true,
    "editor.formatOnSave": true,
    "editor.defaultFormatter": "golang.go-nightly"
  },
  "[markdown]": {
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true
  },
  "settingsSync.ignoredExtensions": ["bengreenier.vscode-node-readme"],
  "fileutils.typeahead.enabled": true,
  "launch": {
    "configurations": [],
    "compounds": []
  },
  "cSpell.userWords": ["Twilio", "middlewares", "sendgrid"],
  "redhat.telemetry.enabled": true,
  "svelte.enable-ts-plugin": true,
  "workbench.editor.untitled.hint": "hidden",
  "solidity.defaultCompiler": "localNodeModule",
  "bookmarks.useWorkaroundForFormatters": true,
  "json.schemas": [

  ],
  "go.toolsManagement.autoUpdate": true,
  "tabnine.experimentalAutoImports": true
}
```
