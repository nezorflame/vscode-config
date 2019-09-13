# vscode-config

Useful links and settings for [VSCode](https://github.com/microsoft/vscode) IDE.

## Documentation

- [Getting Started](https://code.visualstudio.com/docs)
- [Tips and Tricks](https://code.visualstudio.com/docs/getstarted/tips-and-tricks)
- [Keybindings](https://code.visualstudio.com/docs/getstarted/keybindings)
- [Code Navigation](https://code.visualstudio.com/docs/editor/editingevolved)
- [IntelliSense](https://code.visualstudio.com/docs/editor/intellisense)
- [CodeLens](https://code.visualstudio.com/blogs/2017/02/12/code-lens-roundup)
- [Emmet](https://code.visualstudio.com/docs/editor/emmet)
- [Debugging](https://code.visualstudio.com/docs/editor/debugging)
- [Tasks](https://code.visualstudio.com/docs/editor/tasks)
- [User code snippets](https://code.visualstudio.com/docs/editor/userdefinedsnippets)

## Recommended extensions

Keybindings as in the IDEA-like IDE's - [link](https://marketplace.visualstudio.com/items?itemName=k--kato.intellij-idea-keybindings)

### Integrations

- **Go** ([link](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Go)): main extension for VSCode which transforms it into the IDE for Go + **LSP-server** [gopls](https://github.com/golang/tools/blob/master/gopls/README.md) for proper [Go modules](https://github.com/golang/go/wiki/Modules) integration
- **Go Autotest** ([link](https://marketplace.visualstudio.com/items?itemName=windmilleng.vscode-go-autotest)): support for autotesting of Go tests
- **Docker** ([link](https://marketplace.visualstudio.com/items?itemName=PeterJausovec.vscode-docker)): Docker integration
- **Kubernetes** ([link](https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools)): Kubernetes integration
- **Team Chat: for Slack, Discord, Live Share** ([link](https://marketplace.visualstudio.com/items?itemName=karigari.chat)): integration with the popular team chat platforms

### Additional formatting support

- **vscode-proto3** ([link](https://marketplace.visualstudio.com/items?itemName=zxh404.vscode-proto3)): Protobuf v3
- **Clang-Format** ([link](https://marketplace.visualstudio.com/items?itemName=xaver.clang-format)): multi-language formatting support (including **protobuf**) - **must-have** companion for the **vscode-proto3** (don't forget to install the [ClangFormat](https://clang.llvm.org/docs/ClangFormat.html) binary e.g. with `brew install clang-format`)
- **YAML** ([link](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)): YAML
- **shell-format** ([link](https://marketplace.visualstudio.com/items?itemName=foxundermoon.shell-format)): script and config formatting (`shellscript`, `Dockerfile`, `hosts`, etc.)
- **Markdown All in One** ([link](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)): extended  Markdown support
- **markdownlint** ([link](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)): linter for the Markdown files
- **Better TOML** ([link](https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml)): [TOML](https://github.com/toml-lang/toml) support
- **pgFormatter** ([link](https://marketplace.visualstudio.com/items?itemName=bradymholt.pgformatter)): PostgreSQL

### Utilities

- **TODO Highlight** ([link](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)): better support for `TODO`, `FIXME` and other `WIP`-like code comments
- **Quick Task** ([link](https://marketplace.visualstudio.com/items?itemName=lkytal.quicktask)): task manager for VSCode tasks
- **Paste JSON as Code** ([link](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)): code generation out of the JSON files
- **Dash** ([link](https://marketplace.visualstudio.com/items?itemName=deerawan.vscode-dash)): support for the [Dash](https://kapeli.com/dash) (macOS) and [Zeal](https://zealdocs.org/) (Linux/Windows) documentation helpers
- **Share Code** ([link](https://marketplace.visualstudio.com/items?itemName=RolandGreim.sharecode)): enables quick code sharing through the Github Gist / Pastebin
- **carbon-now-sh** ([link](https://marketplace.visualstudio.com/items?itemName=ericadamski.carbon-now-sh)): make beautiful code screenshots with formatting support
- **change-case** ([link](https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case)): quickly change the case of the word(s), supports multiple styles
- **VS Live Share** ([link](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare#user-content-quickstart-sharing)) + **extension pack** ([link](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack)): allows to create remote coding sessions and work collaboration (more on that [here](https://visualstudio.microsoft.com/ru/services/live-share/))

### Git

- **GitLab Workflow** ([link](https://marketplace.visualstudio.com/items?itemName=fatihacet.gitlab-workflow)): Gitlab workflow integration
- **GitLens — Git supercharged** ([link](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)): Git-multitool
- **Git History** ([link](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)): extends native Git support with rich history functions
- **ignore "g" it** ([link](https://marketplace.visualstudio.com/items?itemName=Andreabbondanza.ignoregit)): quickly add files/folders to `.gitignore`

### Database tools

- **vscode-database** ([link](https://marketplace.visualstudio.com/items?itemName=bajdzis.vscode-database)): support working with MySQL and PostgreSQL right from the VSCode editor (can be integrated with other DB extensions)
- **SQLite** ([link](https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite)): SQLite
- **SQL Server (mssql)** ([link](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql)): MSSQL

### Themes and icon packs

- **One Dark Pro** ([link](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)): Atom-like theme
- **Material Icon Theme** ([link](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)): Material-styled icons
- **Material Theme** ([link](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme)): a set of Material themes (already with icons!)
