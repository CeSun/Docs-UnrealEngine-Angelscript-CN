+++
title = "安装"
weight = 10
+++

# Installation
## 1. Getting Unreal Engine Source Access
The angelscript integration requires direct changes to unreal engine code to work.
You will need to get access to unreal engine source code to be able to access the 
version of the engine used in this project.

To get source code access, follow this guide from Epic Games:
[https://www.unrealengine.com/en-US/ue-on-github](https://www.unrealengine.com/en-US/ue-on-github)


## 2. Downloading UnrealEngine-Angelscript
You can download a precompiled editor binary with angelscript from the
[Releases Pages](https://github.com/Hazelight/UnrealEngine-Angelscript/releases)
on github.

Alternatively, clone the [GitHub Repository](https://github.com/Hazelight/UnrealEngine-Angelscript)
and build the unreal editor using visual studio as usual.

Note that you will need to build from source yourself if you want to use any additional plugins.
This fork will not be compatible with any binary plugin distributions from the unreal marketplace.


## 3. Installing the Visual Studio Code Extension
A visual studio code extension with auto-completion and debugging support is available.

Install visual studio code from [https://code.visualstudio.com/](https://code.visualstudio.com/).

Then install the [Unreal Angelscript Extension](https://marketplace.visualstudio.com/items?itemName=Hazelight.unreal-angelscript)
from the marketplace, or search for 'Unreal Angelscript' in the extensions sidebar within Visual Studio Code.