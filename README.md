# CCE OpenEdge ABL developer pack

This is an opinionated combination of
* extensions,
* keybindings
* and default settings
for OpenEdge ABL developers at CCE.

This extension pack may be useful outside of CCE, but will change according to CCE needs.

Feel free to [fork](https://github.com/cverbiest/vscode-cce-abl-pack) and adapt to your own needs.

My other collections without configuration remains available
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
| ctrl+numpad_decimal | Navigate to next marked | editor.action.marker.nextInFiles" |

## Default Settings

* Fira Font with ligatures
* Windows Openedge in c:\Progress\oexxx


## OpenEdge related Extensions by publisher

### Riverside Software

* [Riverside OpenEdge ABL](https://marketplace.visualstudio.com/items?itemName=RiversideSoftware.openedge-abl-lsp) : Build, editing, debugging
* [Riverside CABL](https://marketplace.visualstudio.com/items?itemName=RiversideSoftware.sonarlint-abl): Linting for OpenEdge ABL code

### Baltic Amadeus

* [ProPeek](https://marketplace.visualstudio.com/items?itemName=BalticAmadeus.pro-peek) : consult OpenEdge profiler data
* [ProBro](https://marketplace.visualstudio.com/items?itemName=BalticAmadeus.pro-bro) : Database viewer
* [AblFormatter](https://marketplace.visualstudio.com/items?itemName=BalticAmadeus.openedge-abl-formatter) : Database viewer

### Consultingwerk

* [PASOE Manager Extension](https://marketplace.visualstudio.com/items?itemName=ConsultingwerkApplicationModernizationSolutionsLtd.oemanager)

### Kenneth Herring

* [AblUnit](https://marketplace.visualstudio.com/items?itemName=kherring.ablunit-test-runner) : Testing

## Non Openedge related extensions

####  "benrogerswpg.websearchengine",

###  "bhughes339.replacerules",

###  "eamodio.gitlens",

###  "esbenp.prettier-vscode",

###  "jtr.vscode-position",

###  "rioj7.vscode-file-templates",

###  "hkato193.jp-katohirohito-extension-vscode-quickopen-with-selection",

###  "usernamehw.errorlens"


**Enjoy!**

## History

### Version 1.2.0

* Add Baltic Amadeus  ABL Formatter

### Version 1.1.1

* Revert back to strict ABL

### Version 1.1.0

* Open up to non OpenEdge extensions

### Version 1.0.0

* Add Consultingwerk PASOE Manager Extension
