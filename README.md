# BackPacker Extensions Pack <img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/backpack.png" alt="Auto Rename Tag" width="55px" />

Thanks for checking out my VS Code backPack extension pack.

## Remove all existing extensions (optional)

```
rm -rf ~/.vscode/extensions
```

## Install From Cloning Repository

```
code --install-extension back-packer-0.0.3.vsix
```

## Install From marketplace

```
ext install AbdulmoizAhmer.back-packer
```

## Settings (optional)

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
   "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "settingsSync.ignoredExtensions": ["bengreenier.vscode-node-readme"],
  "fileutils.typeahead.enabled": true,
  "launch": {
    "configurations": [],
    "compounds": []
  },
  "cSpell.userWords": ["Kubernetes", "middlewares", "sendgrid", "Twilio"],
  "redhat.telemetry.enabled": true,
  "svelte.enable-ts-plugin": true,
  "workbench.editor.untitled.hint": "hidden",
  "solidity.defaultCompiler": "localNodeModule",
  "bookmarks.useWorkaroundForFormatters": true,
  "json.schemas": [

  
  ],
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs":"active",
  "go.toolsManagement.autoUpdate": true,
  "tabnine.experimentalAutoImports": true,
  "vs-kubernetes": {
    "vscode-kubernetes.kubectl-path.linux": "/home/abdulmoiz/.vs-kubernetes/tools/kubectl/kubectl",
    "vscode-kubernetes.minikube-path.linux": "/home/abdulmoiz/.vs-kubernetes/tools/minikube/linux-amd64/minikube",
    "vscode-kubernetes.helm-path.linux": "/home/abdulmoiz/.vs-kubernetes/tools/helm/linux-amd64/helm"
  }
}
```

## Included Extensions

### Apollo GraphQL

Rich editor support for GraphQL client and server development that seamlessly integrates with the Apollo platform.

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/apollographql.png" alt="Auto Rename Tag" width="60%" height="60%" />

### Auto Import

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/autoimport.png" alt="Auto Rename Tag" width="60%" height="60%" />

Automatically finds, parses and provides code actions and code completion for all available imports. Works with Typescript and TSX.

### Auto Rename Tag

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/autorenametag.png" alt="Auto Rename Tag" width="60%" height="60%" />

This one automatically renames the corresponding tag that you modify. This is just a helpful time-saver.

### Babel JavaScript

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/babeljavascript.png" alt="Auto Rename Tag" width="60%" height="60%" />

VSCode syntax highlighting for today's JavaScript.

### Bash Beautify

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/bashbeautify.png" alt="Auto Rename Tag" width="60%" height="60%" />

Format / Beautify bash and shell scripts.

### Better Comments

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/bettercomments.png" alt="Auto Rename Tag" width="60%" height="60%" />

Improve your code commenting by annotating with alert, informational, TODOs, and more!

### Better TOML

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/bettertoml.png" alt="Auto Rename Tag" width="60%" height="60%" />

Better TOML is vs code extension to support TOML file.

### Bookmarks

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/bookmarks.png" alt="Auto Rename Tag" width="60%" height="60%" />

Mark lines and jump to them.

### Bridge to Kubernetes

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/bridgetokubernetics.png" alt="Auto Rename Tag" width="60%" height="60%" />

Rapid Kubernetes development for teams.

### change-case

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/change-case.png" alt="Auto Rename Tag" width="60%" height="60%" />

Quickly change the case (camelCase, CONSTANT_CASE, snake_case, etc) of the current selection or current word.

### Code Spell Checker

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/codespellchecker.png" alt="Auto Rename Tag" width="60%" height="60%" />

Spelling checker for source code.

<!-- ### CodeSnap

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/codesnap.png" alt="Auto Rename Tag" width="60%" height="60%" />

Take beautiful screenshots of your code. -->

### Color Highlight

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/colorhighlight.png" alt="Auto Rename Tag" width="60%" height="60%" />

Highlight web colors in your editor.

### CSS Peek

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/csspeek.png" alt="Auto Rename Tag" width="60%" height="60%" />

Allow peeking to css ID and class strings as definitions from html files to respective CSS. Allows peek and goto definition.

### css-to-react

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/csstoreact.png" alt="Auto Rename Tag" width="60%" height="60%" />

Convert CSS to React-style style objects or JSON.



### Diff

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/diff.png" alt="Auto Rename Tag" width="60%" height="60%" />

Diff 2 opened files with ease. Because running `code --diff path1 path2` is too slow.

### Docker

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/docker.png" alt="Auto Rename Tag" width="60%" height="60%" />

Makes it easy to create, manage, and debug containerized applications.

### DotENV

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/dotenv.png" alt="Auto Rename Tag" width="60%" height="60%" />

Support for dotenv file syntax.

### ES7+ React/Redux/React-Native snippets

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/es7plusreactreduxreactnative.png" alt="Auto Rename Tag" width="60%" height="60%" />

Extensions for React, React-Native and Redux in JS/TS with ES7+ syntax. Customizable. Built-in integration with prettier.

### ESLint

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/eslint.png" alt="Auto Rename Tag" width="60%" height="60%" />

Integrates ESLint JavaScript into VS Code.

### Ethereum DeFi Language Support

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/ethereumdefilanguagesupport.png" alt="Auto Rename Tag" width="60%" height="60%" />

Ethereum DeFi support for NodeJS applications

### Ethereum Essentials Pack

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/ethereumessentialspack.png" alt="Auto Rename Tag" width="60%" height="60%" />

Extension pack for Ethereum developers

### Ethereum Remix

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/ethereumremix.png" alt="Auto Rename Tag" width="60%" height="60%" />

Ethereum Remix plugins in VSCode

### EthSential

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/ethsential.png" alt="Auto Rename Tag" width="60%" height="60%" />

Security analysis for Ethereum smart contracts

### File Downloader

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/filedownloader.png" alt="Auto Rename Tag" width="60%" height="60%" />

Exposes an API that allows other extensions to download files.

### File Utils

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/fileutils.png" alt="Auto Rename Tag" width="60%" height="60%" />

A convenient way of creating, duplicating, moving, renaming, deleting files and directories.

### Font Awesome Auto-complete & Preview

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/fontawsomeautocomplete.png" alt="Auto Rename Tag" width="60%" height="60%" />

Autocomplete & preview Font Awesome icons in any language.

<!-- ### Git Blame

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/gitblame.png" alt="Auto Rename Tag" width="60%" height="60%" />

See git blame information in the status bar. -->

### Git Extension Pack

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/gitextensionpack.png" alt="Auto Rename Tag" width="60%" height="60%" />

Popular Visual Studio Code extensions for Git.

### Git History

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/githistory.png" alt="Auto Rename Tag" width="60%" height="60%" />

View git log, file history, compare branches or commits.

### GitHub Pull Requests and Issues

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/githubpullrequestsandissues.png" alt="Auto Rename Tag" width="60%" height="60%" />

Pull Request and Issue Provider for GitHub.

<!-- ### gitignore

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/autorenametag.png" alt="Auto Rename Tag" width="60%" height="60%" />

Lets you pull .gitignore templates from the https://github.com/github/gitignore repository. Language support for .gitignore files. -->

### GitLens — Git supercharged

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/gitlens.png" alt="Auto Rename Tag" width="60%" height="60%" />

Supercharge Git within VS Code — Visualize code authorship at a glance via Git blame annotations and CodeLens, seamlessly navigate and explore Git repositories, gain valuable insights via rich visualizations and powerful comparison commands, and so much more

### Go

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/go.png" alt="Auto Rename Tag" width="60%" height="60%" />

Rich Go language support for Visual Studio Code.

### Go Doc

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/godoc.png" alt="Auto Rename Tag" width="60%" height="60%" />

Show documentation of go symbols and packages.

### Go Nightly

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/gonightly.png" alt="Auto Rename Tag" width="60%" height="60%" />

Rich Go language support for Visual Studio Code (Nightly).

### Go Outliner

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/gocodeoutlineexplorer.png" alt="Auto Rename Tag" width="60%" height="60%" />

Go code outline explorer.

### Go Test Explorer

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/gotestexplorer.png" alt="Auto Rename Tag" width="60%" height="60%" />

Go Test Explorer.

### Go to SCSS

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/gotoscss.png" alt="Prettier" width="60%" height="60%" />

Switch between the code and the stylesheet file.

### Golang TDD

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/golangtdd.png" alt="Live Server" width="60%" height="60%" />

Show green/red lights on the bottom bar. Red when tests are failing and green when passing. This runs on save. Better feedback with less effort.

### Golang Tools

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/golangtools.png" alt="Better Comments" width="60%" height="60%" />

Tools for productive work.

### HTML to CSS / LESS / SCSS

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/htmltocsslessscss.png" alt="HTML CSS Support" width="60%" height="60%" />

Copy HTML code and paste it as CSS / LESS / SCSS selectors code.

### html-to-react

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/htmlscsssupport.png" alt="HTML CSS Support" width="60%" height="60%" />

Converts HTML code to React JSX.

### htmltagwrap

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/htmltagwrap.png" alt="HTML CSS Support" width="60%" height="60%" />

Wraps selected code with HTML tags.

### Image preview

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/imagepreview.png" alt="HTML CSS Support" width="60%" height="60%" />

Shows image preview in the gutter and on hover.

### Import Cost

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/importcost.png" alt="HTML CSS Support" width="60%" height="60%" />

Display import/require package size in the editor.

### indent-rainbow

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/indent-rainbow.png" alt="HTML CSS Support" width="60%" height="60%" />

Makes indentation easier to read.

### IntelliSense for CSS class names in HTML

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/intellisenseforcssclassnames.png" alt="HTML CSS Support" width="60%" height="60%" />

CSS class name completion for the HTML class attribute based on the definitions found in your workspace.

### JavaScript and TypeScript Nightly

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/javascriptandtypescriptnightly.png" alt="HTML CSS Support" width="60%" height="60%" />

Enables typescript@next to power VS Code's built-in JavaScript and TypeScript support.

### javascript console utils

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/javascriptconsoleutils.png" alt="HTML CSS Support" width="60%" height="60%" />

Help insert and remove console.(\*) statements.

### JS JSX Snippets

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/jsjsxsxippets.png" alt="HTML CSS Support" width="60%" height="60%" />

Extensions for React, Redux in JS with babel and ES7 syntax.

### JSON to TS

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/jsontots.png" alt="HTML CSS Support" width="60%" height="60%" />

Convert JSON object to typescript interfaces.

### jsx-to-scss

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/jsxtoscss.png" alt="HTML CSS Support" width="60%" height="60%" />

Help you generate scss/less structure from jsx.

### Kubernetes

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/kubernetes.png" alt="HTML CSS Support" width="60%" height="60%" />

Develop, deploy and debug Kubernetes applications.

### Live Sass Compiler

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/livesasscompiler.png" alt="HTML CSS Support" width="60%" height="60%" />

Compile Sass or Scss to CSS at realtime with live browser reload.

<!-- ### Live Server

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/liveserver.png" alt="HTML CSS Support" width="60%" height="60%" />

Launch a development local Server with live reload feature for static & dynamic pages. -->

### Live Share

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/liveshare.png" alt="HTML CSS Support" width="60%" height="60%" />

Real-time collaborative development from the comfort of your favorite tools.

### Markdown Preview Github Styling

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/markdownpreviewgithubstyling.png" alt="HTML CSS Support" width="60%" height="60%" />

Changes VS Code's built-in markdown preview to match Github's style.

### MinifyAll

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/minifyall.png" alt="HTML CSS Support" width="60%" height="60%" />

Minifier for JSON, CSS, HTML, XML, TWIG, LESS, SASS, SCSS, JavaScript, JSONC, and JavaScriptReact(testing). Compressor of files and folders. You will love its simplicity!.

### MongoDB for VS Code

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/mongodbforvscode.png" alt="HTML CSS Support" width="60%" height="60%" />

Connect to MongoDB and Atlas directly from your VS Code environment, navigate your databases and collections, inspect your schema and use playgrounds to prototype queries and aggregations.

### Move TS - Move TypeScript files and update relative imports

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/movetsmovetypescriptfiles.png" alt="HTML CSS Support" width="60%" height="60%" />

extension for moving typescript files and folders and updating relative imports in your workspace.

### Multi Line tricks

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/multilinetricks.png" alt="HTML CSS Support" width="60%" height="60%" />

Enable Alt+L (line select) and Alt+Shift+L (selection to multi-cursor) behavior on VSCode.

### MySQL

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/mysql.png" alt="HTML CSS Support" width="60%" height="60%" />

Database manager for MySQL/MariaDB, PostgreSQL, SQLite, Redis and ElasticSearch.

### Node TDD

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/nodetdd.png" alt="HTML CSS Support" width="60%" height="60%" />

Ease test-driven development in Node and JavaScript.

### node-readme

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/nodereadme.png" alt="HTML CSS Support" width="60%" height="60%" />

A vscode extension to view javascript module documentation in editor.

### Node.js Exec

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/nodejsexec.png" alt="HTML CSS Support" width="60%" height="60%" />

Execute the current file or your selected code with node.js.

### npm

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/npm.png" alt="HTML CSS Support" width="60%" height="60%" />

npm support for VS Code.

### npm Intellisense

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/npmintellisense.png" alt="HTML CSS Support" width="60%" height="60%" />

Visual Studio Code plugin that autocompletes npm modules in import statements.

### One Monokai Theme

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/onemonokaitheme.png" alt="HTML CSS Support" width="60%" height="60%" />

A cross between Monokai and One Dark theme.

### open in browser

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/openinbrowser.png" alt="HTML CSS Support" width="60%" height="60%" />

This allows you to open the current file in your default browser or application.

### Open in GitHub, Bitbucket, Gitlab, VisualStudio.com !

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/openingithubbitbucket.png" alt="HTML CSS Support" width="60%" height="60%" />

Jump to a source code line in Github, Bitbucket, Gitlab, VisualStudio.com !.

### Paste JSON as Code

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/pastejsonascode.png" alt="HTML CSS Support" width="60%" height="60%" />

Copy JSON, paste as Go, TypeScript, C#, C++ and more.

### Peacock

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/peacock.png" alt="HTML CSS Support" width="60%" height="60%" />

Subtly change the workspace color of your workspace. Ideal when you have multiple VS Code instances and you want to quickly identify which is which.

### Prettier - Code formatter

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/prettiercodeformatter.png" alt="HTML CSS Support" width="60%" height="60%" />

Code formatter using prettier.

### Project Manager

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/projectmanager.png" alt="HTML CSS Support" width="60%" height="60%" />

Easily switch between projects.

### Project Snippets

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/projectsnippets.png" alt="HTML CSS Support" width="60%" height="60%" />

Project/Workspace level snippets.

### px to rem

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/pxtorem.png" alt="HTML CSS Support" width="60%" height="60%" />

Converts px to rem, and vice versa.

### Quokka.js

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/quokkajs.png" alt="HTML CSS Support" width="60%" height="60%" />

JavaScript and TypeScript playground in your editor.

### React Native Tools

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/reactnativetools.png" alt="HTML CSS Support" width="60%" height="60%" />

Debugging and integrated commands for React Native.

### Remote - Containers

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/remotecontainers.png" alt="HTML CSS Support" width="60%" height="60%" />

Open any folder or repository inside a Docker container and take advantage of Visual Studio Code's full feature set.

### Remove Comments

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/removecomments.png" alt="HTML CSS Support" width="60%" height="60%" />

Remove all comments from your code at once! Unclutter and undocument your code in one go!

### REST Client

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/restclient.png" alt="HTML CSS Support" width="60%" height="60%" />

REST Client for Visual Studio Code.

### Rust

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/rust.png" alt="HTML CSS Support" width="60%" height="60%" />

Rust for Visual Studio Code (powered by Rust Language Server/Rust Analyzer). Provides lints, code completion and navigation, formatting and more.

### SCSS IntelliSense

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/scssintellisense.png" alt="HTML CSS Support" width="60%" height="60%" />

Advanced autocompletion and refactoring support for SCSS.

### Search node_modules

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/searchnode_modules.png" alt="HTML CSS Support" width="60%" height="60%" />

Quickly search the node_modules folder.

### seti

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/seti.png" alt="HTML CSS Support" width="60%" height="60%" />

Seti theme for VsCode.

### solidity

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/solidity.png" alt="HTML CSS Support" width="60%" height="60%" />

Ethereum Solidity Language for Visual Studio Code.

### Solidity Debugger

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/soliditydebugger.png" alt="HTML CSS Support" width="60%" height="60%" />

Debugger for Solidity smart contracts - powered by the Meadow testing and development tool suite.

### Svelte for VS Code

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/svelteforvscode.png" alt="HTML CSS Support" width="60%" height="60%" />

Svelte language support for VS Code.

### Svg Preview

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/svgpreview.png" alt="HTML CSS Support" width="60%" height="60%" />

Preview for Svg files.

### Tabnine AI Autocomplete for Javascript, Python, Typescript, PHP, Go, Java, Ruby & more

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/tabnineaiautocomplete.png" alt="HTML CSS Support" width="60%" height="60%" />

JavaScript, Python, Java, Typescript & all other languages - AI Code completion plugin. Tabnine makes developers more productive by auto-completing their code.

### Tailwind CSS IntelliSense

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/tailwindcssintellisense.png" alt="HTML CSS Support" width="60%" height="60%" />

Intelligent Tailwind CSS tooling for VS Code.

### Template String Converter

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/templatestringconverter.png" alt="HTML CSS Support" width="60%" height="60%" />

Converts a string to a template string when ${ is typed.

### Todo Tree

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/todotree.png" alt="HTML CSS Support" width="60%" height="60%" />

Show TODO, FIXME, etc. comment tags in a tree view.

### TSLint

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/tslint.png" alt="HTML CSS Support" width="60%" height="60%" />

TSLint support for Visual Studio Code.

### TypeScript Hero

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/typescripthero.png" alt="HTML CSS Support" width="60%" height="60%" />

Additional toolings for typescript.

### TypeScript Importer

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/typescriptimporter.png" alt="HTML CSS Support" width="60%" height="60%" />

Automatically searches for TypeScript definitions in workspace files and provides all known symbols as completion item to allow code completion.

### Typescript React code snippets

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/typescriptreactcodesnippets.png" alt="HTML CSS Support" width="60%" height="60%" />

Code snippets for react in typescript.

### TypeScript Vue Plugin (Volar)

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/typescriptvueplugin.png" alt="HTML CSS Support" width="60%" height="60%" />

Vue Plugin for TypeScript server.

### Vetur

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/vuetur.png" alt="HTML CSS Support" width="60%" height="60%" />

Vue tooling for VS Code.

### Visual Studio Code Commitizen Support

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/visualstudiocodecommitizensupport.png" alt="HTML CSS Support" width="60%" height="60%" />

commitizen - git commit with conventions.

### vscode-UnCSS

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/vscode-UnCSS.png" alt="Auto Rename Tag" width="60%" height="60%" />

Can use uncss with vscode.

### Visual Studio IntelliCode

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/vscodeintellicode.png" alt="HTML CSS Support" width="60%" height="60%" />

AI-assisted development.

### Visual Studio Keymap

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/visualstudiokeymap.png" alt="HTML CSS Support" width="60%" height="60%" />

Popular Visual Studio keybindings for VS Code.

### VS Color Picker

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/vscolorpicker.png" alt="HTML CSS Support" width="60%" height="60%" />

A tiny & smart color picker for web developer.

### VS HTML to CSS

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/vshtmltocss.png" alt="HTML CSS Support" width="60%" height="60%" />

Generate CSS classes from HTML structure.

### vscode-faker

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/vscodefaker.png" alt="HTML CSS Support" width="60%" height="60%" />

Generate fake data for name, address, lorem ipsum, commerce and much more.

### vscode-proto3

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/vscodeproto3.png" alt="HTML CSS Support" width="60%" height="60%" />

Protobuf 3 support for Visual Studio Code.

### vue

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/vue.png" alt="HTML CSS Support" width="60%" height="60%" />

Syntax Highlight for Vue.js.

### Vue Language Features (Volar)

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/vuelanguagefeatures.png" alt="HTML CSS Support" width="60%" height="60%" />

Language support for Vue 3.

### Vyper

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/vyper.png" alt="HTML CSS Support" width="60%" height="60%" />

Ethereum Vyper language support for Visual Studio Code.

### YAML

<img src="https://raw.githubusercontent.com/Abdulmoiz-Ahmer/back-packer-images/master/yaml.png" alt="HTML CSS Support" width="60%" height="60%" />

YAML Language Support by Red Hat, with built-in Kubernetes syntax support.
