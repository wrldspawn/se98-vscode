# [SE98](https://github.com/nestoris/Win98SE) for Visual Studio Code

SE98 (Windows 9x/2000) icons for Visual Studio Code.

## To-do

- Audio filetypes
- Video filetypes
- SVG icon
- Unique JSX/TSX/MDX icons
  - There aren't really any good ways I can figure out to convey it being a different file type that look good
- More special folders (e.g. `node_modules`)
- Git related files
	- Visual Studio 6 and Visual Studio .NET 2002/2003 have era accurate programming related icons
- [Anything you feel is missing](https://github.com/wrldspawn/se98-vscode/issues/new)

## Contributing

- [Stick to the 256 color palette](https://github.com/nestoris/Win98SE/blob/main/reference/README.md)
  - Palettes for paint.net and Aseprite can be found in this repo's `palettes` folder
- Keep consistency with the other icons
	- File and text icons are aligned with a 1px gap to the left and a 2px gap to the right
  - File and text icons use generic versions as a base, as there is extra shading applied compared to typical 9x and 2000 icons

## Product Icons (icons for the rest of the UI)

Until the restrictions of product icons being a single color font are lifted, it is not currently possible.

Theoretically it should be possible to make 96 DPI pixel perfect SVGs (via `.26458` width/height `rect`s)
and convert it to a font (woff fonts will force antialiasing off on almost all platforms if bitmap glyphs are present),
but this is not tested in the slightest.

This only leaves CSS as the most feasible option. You can use either [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)
or [VSCode Tweaker Windhawk mod](https://windhawk.net/mods/vscode-tweaker) (persists across updates) to inject custom CSS.

An example starting point for replacing icons can be found [here](https://gist.github.com/wrldspawn/258eddda72e9e917f555e1361a784346).

## Credits

- [Windows NT/2000 theme](https://github.com/manekinekko/windows-nt-vscode-theme) - Inspiration and motivation to make a more complete icon theme
- nestoris - SE98