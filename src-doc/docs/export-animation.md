# ![Export anim Icon](img/icons/exportanim-icon-r.png) Animation

You can export After Effects animations with DuIO.

1. Select the layers and/or the keyframes to export
2. Click on the *Export Animation* button

The exported data will be stored in a standard and open JSON (text) file.
You can then [re-import the animation](import-animation.md) to other projects/layers in After Effects, or use it in another software.

!!! tip
    It can be useful in After Effects to store the motion data appart for the After Effects project file, to make it quicker and easier to re-use it or even build an animation library for any kind of animations.

!!! hint
    This JSON data can be pretty easily parsed in any other software with only a little development work. It can be a game engine, another animation software, conversion to a web animation format... It's up to you, if you know a little bit about writing scripts.  
    The format is not yet documented, but easy to understand just by reading the file. It is very close to how animations are stored in After Effects.
    