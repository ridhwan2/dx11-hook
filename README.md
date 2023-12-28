# About
Renders a gui by internally hooking [DirectX11](https://en.wikipedia.org/wiki/DirectX)

## Usage
- Open the `.sln` file
- Make sure that you are on `Debug` and `x64`
- Build & add features!

You should have a `.dll` (dynamic link library) produced, use a dll injector to execute the code into a process, this should render a menu, by default it's toggleable with the `DEL` key and and uninjectable with the pre-coded button. 

- If your menu isn't opening make sure that vgk.sys, or any similar processes (easy anticheat, battleye, richoet, etc) aren't running, or use a better injector.
- Make sure that your game is on "Windowed Fullscreen" or the menu may not render properly.

## Credits
- [kiero](https://github.com/Rebzzel/kiero)
- [imgui](https://github.com/ocornut/imgui)

## Misc

> [MIT](https://opensource.org/license/mit/) 2023 Ridhwan
> 
> Some parts of the software may be coded by other people (see credits)
