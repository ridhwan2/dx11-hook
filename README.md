# About
Renders a gui by internally hooking [DirectX11](https://en.wikipedia.org/wiki/DirectX)

![menu](https://cdn.discordapp.com/attachments/1100164162295959555/1163125073247481906/cmXblhbWXbvnrerV8tqTAkgJLCiwpsKTAkgJLCuxLCiyB1L6c9uWglxRYUmBJgSUFlhRYUqALCiyBVBdUXNaxpMCSAksKLCmwpMCSAvuSAksgtSnfTnoJQWWFFhSYEmBJQWWFOiCAksg1QUVl3UsKbCkwJICSwosKbCkwL6kwP8PfiL6mFQC1V8AAAAASUVORK5CYII.png?ex=653e6fa3&is=652bfaa3&hm=45166019dd00289495dff83bd9172f6009f75ea6bd0c1a68ad75cba38a508a33&)

## Usage
- Open the `.sln` file
- Make sure that you are on `Debug` and `x64`
- Build & add features!

You should have a `.dll` (dynamic link library) produced, use a dll injector to execute the code into a process, this should render a menu, by default it's toggleable with the `DEL` key and and uninjectable with the pre-coded button. 

- If your menu isn't appearing than an anticheat may be blocking it from loading, to evade this make sure that you have `-insecure` and/or `-allow_third_party_software` enabled.
- Make sure that your game is on "Windowed Fullscreen" or the menu may not render properly.

## Credits
- [kiero](https://github.com/Rebzzel/kiero)
- [imgui](https://github.com/ocornut/imgui)

## Misc

> [MIT](https://opensource.org/license/mit/) 2023 Ridhwan
> 
> Some parts of the software may be coded by other people (see credits)
