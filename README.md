# About
Hooks the dx11 [present method](https://learn.microsoft.com/en-us/windows/win32/api/dxgi/nf-dxgi-idxgiswapchain-present) to render a gui internally


## Usage
- Open the .`sln` file
- Make sure that you are on `Debug` and `x64`
- Build


You should have a `.dll` (dynamic link library) produced, use a dll injector to execute the code into a process, this should render a menu, by default it's toggleable with the `DEL` key and and uninjectable with the pre-coded button.

To interact and change the GUI to what suits you best locate [this](https://github.com/ridhwan2/dx11-hook/blob/main/main.cpp#L81) section of the code, (you may have to scroll a little)




## Credits
[kiero](https://github.com/Rebzzel/kiero)
[imgui](https://github.com/ocornut/imgui)

## License

> [MIT](https://opensource.org/license/mit/) 2023 Ridhwan
> 
> Some parts of the software may be coded by other people (see credits)
