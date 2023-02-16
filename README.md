# looks_speed(\<yaw>,\<pitch>,[speed],[display_debug])
##### A function for MKB. Adds an alternative way of using looks. Instead of time, you give it a speed. It should be useful if you want to make more uniform movements of camera.

- **Installation**
	- Create a script file in the macros folder. Ex: `functions.txt`;
	- Paste this script and save;
  - In the beginning of a script of your own, call the file you created with the function. Ex: `$$<functions.txt>`
  
- **Usage**
	- The function works almost the same as the 'looks' action the mod provides. Give it a yaw, a pitch, and then a speed you want it to have while moving the camera;
	- There is also a fourth parameter, boolean, that may be set to True if you want it to display debugger messages in the chat;
  - Examples: 
      - looks_speed(10,20,50);
      - looks_speed(+45,,80);
      - looks_speed(+45,0,40);

### References:
- [Macro KeyBind Mod](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/1275039-macro-keybind-mod), the mod used to run this script ~ by [Mumfrey](https://github.com/mumfrey)
- [LiteLoader](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/1290155-liteloader), the mod loader required to use this mod ~ by [Mumfrey](https://github.com/mumfrey)
- [Unofficial documentation](https://beta.mkb.gorlem.ml/docs/actions/), containing lots of information about the custom programming language created by the mod ~ by [Gorlem](https://github.com/Gorlem/)  
- [MKB Syntax Highlighting](https://github.com/KeeMeng/MKB-Syntax-Highlighting), a plugin for the software Sublime Text that provides lots of features to programmers of this language ~ by [KeeMeng (TKM)](https://github.com/KeeMeng) 
- [Klacaiba](https://github.com/spthiel/klacaiba), a module for the MKB mod that allows the usage of *calc*, needed to make the math (really important for this script), and *elseifmatches*. It also contains many other features that were not used by this script ~ by [Elspeth](http://github.com/spthiel) 
- [Functions Module](https://github.com/Gorlem/functions-module), a module for the MKB mod that allows to create custom functions that may be used like the actions the mod adds ~ by [Gorlem](https://github.com/Gorlem/) 
