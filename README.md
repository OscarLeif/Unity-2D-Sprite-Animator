# 2D Sprite Animator
 Tired of the "Unity Animator Hell", want more performance and faster workflow ? You've gone into the right place, this is a project i've made to replace Unity Animator usage on 2D projects, it's more performatic, simple and easy to use.

## How to install
### Package Manager (recommended)
1 - Open the package manager (Window > Package Manager)  
2 - Click on the plus icon and "Add package from git URL..."  
3 - Enter https://github.com/GabrielBigardi/2D-Sprite-Animator.git and click "Add"  
4 - Wait until the package manager finishes installing the package and recompiling  
   
### Lazy way
1 - Download this repository as ZIP or by cloning it.
2 - Drag it into your "Assets" folder.
  
## How to use
1 - Right click on your "Assets" folder > Create > Sprite Animation  
2 - Rename it as you like, add a name to the "Name" field and add/remove frames, select animation type and framerate.  
3 - Add a Sprite Animator component to the object you wan't to add these animations.  
4 - Add the previously created Sprite Animations from your assets folder to the "Sprite Animations" list in the Sprite Animator component.  
5 - Select if you wan't to play the animation automatically or do it by code.  
  
## Why to use
* Unity Animator was made for 3D games, it has a lot of unuseful interpolation settings and it's a hell to manage.
* Unity Animator is pretty expensive for simple 2D games, more about that in the benchmark section.
* Unity Animator is not fast to setup, you need to create animations, save it on a folder, setup transitions/parameters, try to organize the Animator window, etc...
* Unity Animator don't give you enough control for 2D (and even 3D) games, there isn't a easy way of doing things like: checking current frame, checking which frame you are, checking if animation has ended, etc...
* It's pretty easy to upgrade this code to your liking.
* 1000 other things that you probably already know if you've used Unity Animator for 2D games for a long time.
  
## Benchmarking
For the benchmark i did a simple test on a empty URP project with 2D Rendering/Lighting and 10.000 2D characters playing a 5-frames-long idle animation.
### Unity Default Animator
Animator disabled: 130 FPS.
Animator enabled: 15 FPS.
  
### Sprite Animator
Animator disabled: 130 FPS.
Animator enabled: 85 FPS.
  
## Where can i find further documentation about (codes and other things)?
[Click here](DOCUMENTATION.md)
  
## How do i contribute to this project?
[Click here](CONTRIBUTING.md).
  
## Contact
**Discord**: *Gabriel Bigardi#2292*  
**Twitter**: *@BigardiGabriel*  
**Email**: *gabrielbigardi@hotmail.com*  
