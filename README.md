# CCE OpenEdge ABL developer pack

This is an opinionated combination of
* extensions
* keybindings
* and default settings
for OpenEdge ABL developers at CCE.

This extension pack may be useful outside of CCE, but will change according to CCE needs.

Feel free to [fork](https://github.com/cverbiest/vscode-cce-abl-pack) and adapt to your own needs.

My other collections without configuration remain available
* [abl-developer-pack](https://marketplace.visualstudio.com/items?itemName=cverbiest.abl-developer-pack)
*  [cverbiest-full-pack](https://marketplace.visualstudio.com/items?itemName=cverbiest.cverbiest-full-pack)

# What's inside

## Keybindings

| Key                 | Description             | Action                            |
| ------------------- | ----------------------- | --------------------------------- |
| ctrl+alt+c          | Compile editor content  | abl.compileBuffer                 |
| shift+f2            | Compile editor content  | abl.compileBuffer                 |
| ctrl+alt+t          | Open runtask dialog     | workbench.action.tasks.runTask    |
| ctrl+alt+x          | Show active file in VsCode explorer, combine with [explorer.autoReveal](vscode://settings/explorer.autoReveal) false | workbench.files.action.showActiveFileInExplorer |
| ctrl+numpad_decimal | Navigate to next error/warning marker | editor.action.marker.nextInFiles |

## Default Settings

These settings can still be changed locally, only the default values are set by the plugin

* [Fira Font](https://github.com/tonsky/FiraCode) with ligatures
* Windows Openedge in oe128 in c:\Progress\oe128, oe122 in c:\Progress\oe122
* `explorer.autoReveal` set to false, use ctrl+alt+x to show active file in explorer

## OpenEdge related Extensions by publisher

### Riverside Software

* [Riverside OpenEdge ABL](https://marketplace.visualstudio.com/items?itemName=RiversideSoftware.openedge-abl-lsp) : Build, editing, debugging
* [Riverside CABL](https://marketplace.visualstudio.com/items?itemName=RiversideSoftware.sonarlint-abl): Linting for OpenEdge ABL code

### Baltic Amadeus

* [ProPeek](https://marketplace.visualstudio.com/items?itemName=BalticAmadeus.pro-peek) : consult OpenEdge profiler data
* [ProBro](https://marketplace.visualstudio.com/items?itemName=BalticAmadeus.pro-bro) : Database viewer
* [AblFormatter](https://marketplace.visualstudio.com/items?itemName=BalticAmadeus.openedge-abl-formatter) : Abl code formatter

### Consultingwerk

* [PASOE Manager Extension](https://marketplace.visualstudio.com/items?itemName=ConsultingwerkApplicationModernizationSolutionsLtd.oemanager)

### Kenneth Herring

* [AblUnit](https://marketplace.visualstudio.com/items?itemName=kherring.ablunit-test-runner) : Testing

## Non Openedge related extensions

### Websearch selected text `benrogerswpg.websearchengine`
Search selected text using preconfigured search engines, included are:
* OpenEdge Knowledgebase
* ABL doc search
* Search All ABL reference
* ABL 12.8 reference
* ABL 12.2 reference
* Google Progress site
* Google
* Stack Overflow
* Wikipedia
* GitHub

### File templates `rioj7.vscode-file-templates`
Define your own file templates. See my [vscode-abl-sample-workspace](https://github.com/cverbiest/vscode-abl-sample-workspace/tree/main/.vscode/templates) for some ABL templates.

### Replace rules `bhughes339.replacerules`
Create sets of re-usable replace rules.

### Git lens `eamodio.gitlens`
Display inline git information.

### Prettier code formatter `esbenp.prettier-vscode`
An opinionated code formatter for a large set of languages.

### Jump to absolute file position `jtr.vscode-position`
Useful if you get an error at character position ... .

### QuickOpen with selected text `kato19.jp-katohirohito-extension-vscode-quickopen-with-selection`
Puts the selected text in the QuickOpen dialog.

### Error lens
Display inline errors using `usernamehw.errorlens`

**Enjoy!**

## History

### Version 0.0.5
* Cleanup readme file

### Version 0.0.4

* Prepare for publishing

### Version 0.0.3

* Add keybindings and connfiguration defaults

### Version 0.0.2

* Add extra non OpenEdge extensions

### Version 0.0.1

* Started as clone of abl-developer-pack
