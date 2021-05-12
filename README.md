![logo](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Images/GGL_logo.png)

# GGL-Documentation

GML GUI Library (GGL), Written by Ced30.

# Welcome to GGL!

**GGL** is a graphical user interface library for Game Maker Studio v2.3+,
It's made with ease of use in mind, mainly to quickly build **GUI** for your **games** and **tools**. 
The **GUI** elements are composed of gameObjects (parents) and structs (children).

## Description

**GGL** supports Game Maker Studio2 versions 2.3 and above. 

**What the package contains:**
- 1 Controller object
- 1 Event_manager object
- a collection of parent_GGL elements
- a collection of GGL_sub elemnts
- a collection of factory scripts
- a collection of wrapper scripts
- a collection of sprites
- a collection of sounds

**Features of the Controller object:**
- Instance destruction
- Keeps track of which button is currently selected
- Mouse input variables
- Z-order

**Features of the Event_Manager object:**
- Handles the events that you can fire or register to (greatly simplifies elements interaction)

GGL GUI elements are divided in 2 categories, parent and children, the "parent" version, are objects that you can drag into the room, and the "children", are structs that must be added to a container parent.

## Installation:

- [**Instructions**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Installation/instructions.md)

## Important

**Object Destruction:**

Because of the fact that objects are drawn by the **obj_GGL_controller**, you **must avoid using** the "instance_destroy()" command
to destroy a parent element, use the "Expire()" method instead, the controller object will handle the parent's destruction.

## Quick Start

- [**Room Setup**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Quick%20Start/Room_Setup.md)
- [**Instancing parent_GGL objects**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Quick%20Start/Instancing_parent_GGL%20objects.md)

## API

Only the **relevant functions**, which would be **public** in an object oriented language will be documented for now.

**Classes:**

- [**Instance Classes**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Classes.md)

- [**Instance Prefabs**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Instance%20Prefabs.md)

- [**Struct Classes**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Struct%20Classes.md)

- [**Struct Prefabs**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Struct_Prefabs.md)

**Classes Methods:**

- [**Common methods**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Common_Methods.md)

**Functions:**

- [**Factory Functions**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/Factory%20Functions.md)

- [**GGL_Functions**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/API/GGL_Functions.md)

## Inheritance map

- [**UML Diagrams**](https://github.com/Ced30/GML-GUI-Library-GGL-Documentation/blob/main/Diagrams/Inheritance.md)

