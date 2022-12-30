## What is raylib?
Raylib is a library, or framework to help people make games or other graphical applications. Raylib is designed to be easy to set up and easy to use. Raylib focuses on exploration and experimentation. Raylib is not a game engine, it is more of a collection of tools to help you make a game-like application.

Raylib is written in C and is a compiled native library. This means it runs directly on your computer with no middle man or inner platform. Raylib can used from many languages through language bindings, but this series will focus on using raylib directly with C and C++


## Why N+1 days?
A lot of programming tutorials advertise that you can learn something in 7 days, or 10 days, or 21 days. Generally that’s all a lie, everyone learns at a different pace.In programming, you never actually stop learning, your skills are always growing as you do more and learn new and different ways to do things.

So I won’t lie to you and say you’ll be a raylib expert in some fixed timeframe. This series of tutorials are here to help you get the basics of how to use raylib and start you on your game development journey.


## What Raylib does
Raylib is a framework that helps people make games.

Raylib provides the following features to code that uses it.

* Setting up a window for drawing (using OpenGL)
* Processing Input
* Playing sounds
* Loading Assets (images, models, sounds and music)
* Simple Drawing functions
* Simple Collision Functions
* Basic Vector and Matrix Math

Raylib provides a platform agnostic API or interface to these features so that users can focus more on actual game code rather than the boring platform specific boilerplate code of getting things set up.

## How your game works with raylib
Raylib works by providing your game with a series of functions it can call that will do things to make game development easier. Such as

* Opening a window that can be drawn into
* Loading images, sounds, and models
* Drawing shapes and pictures to the window using your GPU
* Reporting the state of various input devices such as the mouse, keyboard, or gamepads
* Playing sounds
* Mathematical Helpers


## How raylib is not an engine
Rylib is not a game engine like unity, unreal or godot. These engines are platforms in themselves and provide many more services than raylib does. They also work in a fundamentally different way. Engines like unity manage everything about your game for you. Unity runs your game code for you and your game code manipulates the game state within unity, causing things to happen.

In raylib, your game alway starts with your code. Your code always asks raylib to do something for you. Raylib never runs your code, it is always being told exactly what to do by you. Raylib does not track any game state or game objects for you. This means that many things you need to do to make a game in raylib are up to you, not raylib. Raylib is just there to help when you need it.


## Programming Languages
The raylib source code is written in C. These videos will go over raylib using C/C++ compatible code. 

If you want to use raylib with C or C++ and are not familiar with the languages, it is highly recommended that you learn the basics first before you use raylib. Trying to learn C or C++ and Raylib at the same time will double your frustration and can lead to burnout

There are many good C and C++ tutorials online

* C tutorial
    https://beej.us/guide/bgc 

* C++ tutorial
    https://www.learncpp.com

There are many bindings to other languages for raylib, such as C#, Python, Lua, and GO.
https://github.com/raysan5/raylib/blob/master/BINDINGS.md
Much of the information presented here will be applicable to raylib in other languages but the examples and sample code will be in C. You will be responsible for creating the correct syntax for non C/C++ languages


## What we will cover
### 1] Basics

* Intro
* Setup
* Game Loop Basics
* Drawing
* Loading Assets
* Input
* Audio
* Debugger

### 2] 2D 
* DrawTexture
* Shapes
* Motion
* Timers
* State Data
* Animation (sprites)
* Camera 2d
* Collision 2d
* Vector Math
* Box2d
* Optimization 2d

### 3] 3D
* 3d Concepts
* Camera 3d
* Meshes
* Materials
* Matrix Math
* Hierarchical Transforms
* Shader Basics
* Collision 3d
* Scene Graph concepts
* Animation (3d models)
* 3d optimization

### 4] Advanced
* Building for web
* Advanced Input
* Render Textures
* Images and software rendering
* Packaging
* Advanced Optimizations
* Custom Render Batches
* ImGui
* Tilemaps
* C++ and raylib
* Game Architecture Patterns
* ECS Concepts
* Including Windows Code
* Networking and why it’s hard
* Git Best Practices
