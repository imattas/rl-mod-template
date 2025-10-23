# RL-Template
### Template for creating Rocket League mods
`DISCLAIMER: IF YOU USE THIS PROJECT FOR MALICIOUS PURPOSES THAT IS ON YOU :P THIS PROJECT HAS BEEN CREATED FOR SOLELY MODDING THE GAME.`
---
![image](https://user-images.githubusercontent.com/72645298/234754559-16e1872c-6e7b-4c30-8e31-c2acf1dd5d4d.png)
---
If you dont create your own pattern scan function you can just update the offsets to the latest offsets in the `Core.cpp` file. You can get the latest offsets from https://rl.dumps.host/offsets

The filters(folders) in your solution explorer may not be correct / you may have to check your additional includes in the project settings 

To find functions you can use, you can either scour over the sdk given or use the Rocket League function scanner tool with Bakkesmod. 

To make sure your sdk is up-to-date with the latest version, you can use Matix2's SDK Generator: https://github.com/matix2/RLSDK-Generator/

I have also generously included a "World to Screen" function in the drawing module.

To call in game functions you can use:
```cpp
Main.Execute([]() {  function  });
```


## RL Mod Template v1.0.0

For instance storage, game state tracker, and function hooks, they are all game-specific; so you will need to add on to it depending on what classes/functions your game uses. There are comments throughout the project explaining how everything works as well as some examples of certain features.

#### Requirements

- Moderate understanding of how Unreal Engine works (Globals, objects, actors, reflection system, etc).
- Moderate to advanced understanding of modern C++ (Memory and allocation specifically).
- Visual Studio or another Windows based compiler (For Windows header files, along with library linking).
- ISO C++20 Standard.

## Screenshots

![](https://i.imgur.com/ofnaNVV.png)
