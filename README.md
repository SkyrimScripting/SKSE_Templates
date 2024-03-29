# Skyrim SKSE plugin C++ templates

> Templates of SKSE projects for Skyrim

_Follow links to templates below. Each one is in a separate "[Template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)" GitHub repository._

> All templates use [CommonLibSSE NG](https://github.com/CharmedBaryon/CommonLibSSE-NG) and should work on Skyrim SE, AE, GOG, and VR

## Requirements

> Some templates may have additional requirements.  
> Be sure to read the README for any template you use.

- [Visual Studio 2022](https://visualstudio.microsoft.com/) (_the free Community edition is fine!_)
- [`vcpkg`](https://github.com/microsoft/vcpkg)
  - 1. Clone the repository using git OR [download it as a .zip](https://github.com/microsoft/vcpkg/archive/refs/heads/master.zip)
  - 2. Go into the `vcpkg` folder and double-click on `bootstrap-vcpkg.bat`
  - 3. Edit your system or user Environment Variables and add a new one:
    - Name: `VCPKG_ROOT`  
      Value: `C:\path\to\wherever\your\vcpkg\folder\is`

<img src="https://raw.githubusercontent.com/SkyrimScripting/Resources/main/Screenshots/Setting%20Environment%20Variables/VCPKG_ROOT.png" height="150">

## "Hello, world!"

This [Hello, world!](https://github.com/SkyrimScripting/SKSE_Template_HelloWorld) template is as simple as templates get!

Use this to confirm your C++ compiler is working and you can compile and run basic SKSE plugins.

## Skyrim Scripting YouTube series templates

The following templates will be featured in the YouTube series* teaching SKSE development.

> `*` _currently being recorded, planned release in January 2023_

They each demonstrate a different feature of SKSE.

They use lots of code comments describing the feature that they demonstrate.

|||
|-|-|
| [MessageBox and Notification](https://github.com/SkyrimScripting/SKSE_Template_MessageBox_And_Notification) | Display a popup message in the game and a notification message. |
| [Write to Log File](https://github.com/SkyrimScripting/SKSE_Template_Logging) | Configure an SKSE `.log` file and write to it! |
| [SKSE Events](https://github.com/SkyrimScripting/SKSE_Template_SKSE_Events) | Detect important SKSE events, _e.g. save game, new game, etc_ |
| [Forms](https://github.com/SkyrimScripting/SKSE_Template_Forms) | Lookup and loop thru game forms, _e.g. find all soups in the game_ |
| [Game Events](https://github.com/SkyrimScripting/SKSE_Template_GameEvents) | Detect game events, _e.g. when objects are activated or menus opened/closed_ |
| [Multiple .cpp/.h Files](https://github.com/SkyrimScripting/SKSE_Template_MultipleSourceAndHeaderFiles) | Supports multiple .h and .cpp files |
|||

