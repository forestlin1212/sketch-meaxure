# Sketch MeaXure

> Sketch MeaXure is a re-implemention of `Sketch Measure` with TypeScript, uses Sketch JavaScript API. 
>
> It aims to be:
>
> 1. More stable, not likely to break down after Sketch update.
> 1. Easy to maintain.
>
> ## Improvements
>
> Improvements that users can recognize:
>
> 1. Fully works with lastest version of Sketch (v66).
> 1. The latest `Tint` feature support.
> 1. Easily resize markers, without concerns to break them. (The `resizing constrain` feature).
> 1. Export directly with `Anima stacks` activated.
> 1. Customize the order of exported artboards.
> 1. Better display of text fragments.
> 1. Re-organize functions and panels.
>
> ## Notice
>
> If you encounter problems managing (toggle hidden/locked, remove, and export) markers created by Sketch Measure, run the menu `Plugin - Sketch MeaXure - Help - Rename Old Markers`.
>
> ## Installation
>
> - [Download](https://github.com/qjebbs/sketch-meaxure/releases/latest/download/sketch-meaxure.sketchplugin.zip) the latest release of the plugin
> - Un-zip
> - Double-click on Sketch-Meaxure.sketchplugin
>



## The difference of this repo

- The exported preview images is changed from png to jpg, which can save a lot of storage.
- Restored the scale options of Sketch Measure, and delete "Convert to pixels".  In fact, I don’t think "Convert to pixels" is useful.



## How to build

- Install npm
- [Download](https://github.com/qjebbs/sketch-meaxure/releases/latest/download/sketch-meaxure.sketchplugin.zip) the Sketch-Meaxure.sketchplugin to project root directory, and rename to `sketch-meaxure.sketchplugin`
- cd to project root directory
- `npm install typescript`
- `npm install webpack`
- `npm run build`

