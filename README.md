![Title Logo.png](src%2Fmain%2Fresources%2Fassets%2Fzoom-o-matic%2FTitle%20Logo.png)

A simple, but customizable multi-button zoom tool for Minecraft.

It allows for up to 3 keybinds with customizable zoom and on / off smooth camera.

_This mod is for learning most of all, feel free to use it, but its biggest purpose is learning and teaching to mod fabric._
# Documentation for Learning Fabric
While we are certaintly not experts on fabric, we would like to share our journey and in a hope that it can help others get started with learning fabric modding and Java. 

As such, we are currently working (in progress) on a detailed commentary of the code. In the future we may work towards a tutorial either written or video based on feedback.

[Find the code commentary here.](docs/COMMENTARY.md) 

# Usage
## To install
After fabric mod loader has been installed for the correct version place the latest Zoom-o-matic release with compatible dependencies in the .minecraft/mods folder.
## Dependencies
Fabric Mod Loader (Install to use)
https://fabricmc.net/use/installer/

Fabric API (Place in mod folder)
https://github.com/FabricMC/fabric

owo-lib (Place in mod folder)
https://github.com/wisp-forest/owo-lib

## Using the Mod
**The default Zoom 1 Keybind is "c" which is already bound, so you need to unbind "Save Hotbar Activator" or bind zoom1 to another key to make the mod work.**

### Mod Menu
The mod is registered in mod menu, so you can adjust settings through that GUI if you desire, otherwise you can use commands. 

### Keybinds
Are found in the Zoom-o-Matic section of the normal minecraft keybind menu. 

Options -> Controls -> Keybinds

### Zoom Amount
Adjusts the amount of zooming, with 

`/ZoomO ZoomAmount Zoom_X YY`

- **X** = Zoom Keybind #, (1, 2, or 3.)
- **YY** is the % zoom, (1 - 99)

### Smooth Camera
Toggles whether smooth_camera should be active when zooming, which slows down movement.

`/ZoomO SmoothCamera Zoom_X YY`

- **X** = Zoom Keybind #, (1, 2, or 3.)
- **YY** true/false

# About This Mod & Plans
This mod is meant to be a place to learn how to mod fabric mods for minecraft. This our first mod, so we know it's not 100% perfect, but that's not the point.

The goal is to optimize it, make it better, and improve the features in order to help learn more about modding.

## Here is a list of improvements we would like to make, in order of want:
- Remove owo dependency - i.e. Create a world-independent data saving system.
- Add scrolling zoom
- Add a custom, customizable smoother,
- Add a custom GUI
  - Add more keybinds (including more keybinds, via GUI)
- Add animations
  - Presets like easing.
- Add customizable animations 

# Credit
**@Fej1Dev** has been hand and hand in this entire process, coding large portions himself, and helping me when I get stuck with my portions!

**@LogcialGeekBoy  & [Logical Zoom](https://github.com/LogicalGeekBoy/logical_zoom) - Some of the code used in this mod (mainly the mixin) was from Logical Zoom, but more importantly was that his mod inspired us to make our own. 