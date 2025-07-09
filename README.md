     .----------------.  .----------------.  .----------------. 
    | .--------------. || .--------------. || .--------------. |
    | |  ________    | || |  _________   | || |  ____  ____  | |
    | | |_   ___ `.  | || | |_   ___  |  | || | |_  _||_  _| | |
    | |   | |   `. \ | || |   | |_  \_|  | || |   \ \  / /   | |
    | |   | |    | | | || |   |  _|      | || |    > `' <    | |
    | |  _| |___.' / | || |  _| |_       | || |  _/ /'`\ \_  | |
    | | |________.'  | || | |_____|      | || | |____||____| | |
    | |              | || |              | || |              | |
    | '--------------' || '--------------' || '--------------' |
     '----------------'  '----------------'  '----------------' 

           DarknessFX @ https://dfx.lv | X: @DrkFX

# Unreal Engine CommonUI Minimal Menu Kit
<img src="https://github.com/DarknessFX/UE_MinimalMenuKit/blob/main/.git_img/UE_MinimalMenuKit.PNG?raw=true" width="640px" /> <br/>


## About
Sample project for **Unreal Engine 5.6 with CommonUI** without EnhancedInput.

> [!NOTE]
> It is easy to extend to support EnhancedInput, but for now this is for CommonUI basic foundation.


## Project Settings requirements
```
Open Project Settings. (Menu Edit > Project Settings)
  Go to Game > Common Input Settings, Input Section:
    Input Data = IAD_Generic
  Expand Platform Input section > Windows > Default
  Controller Data > Add 4 Elements:
    IPC_Keyboard
    IPC_Gamepad
    IPC_Touch
    IPC_VR
  Go to Engine > General Settings, Default Classes section:
    Game Viewport Client Class = CommonGameViewportClient
Restart Editor.
```

## Credits
Unreal Engine from Epic Games - https://www.unrealengine.com/ <br/>


## License
@MIT - Free for everyone and any use. <br/><br/>
DarknessFX @ <a href="https://dfx.lv" target="_blank">https://dfx.lv</a> | X: <a href="https://x.com/DrkFX" target="_blank">@DrkFX</a><br/>https://github.com/DarknessFX/UE_MinimalMenuKit
