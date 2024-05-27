# NES development template for vscode
Based on https://github.com/nesdoug/01_Hello

Develop nes roms in C, compile with cc65 and debug with Alchemy65 extension.

Steps:
- Requires bash as the default terminal. You can also adapt .bat or makefile files from nesdoug repo and change the command property in tasks.json
- Install [Alchemy65](https://marketplace.visualstudio.com/items?itemName=alchemic-raker.alchemy65)
- Add [Mesen emulator](https://github.com/NovaSquirrel/Mesen-X/releases/tag/1.0.0) to this project parent folder
- Launch and PreLaunch tasks included. Just F5 and you are ready to go.
