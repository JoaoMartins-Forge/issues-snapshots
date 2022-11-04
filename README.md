# issues-screenshots

Sample to go throw multiple camera orientations, generate screenshots and saving those as images

![Platforms](https://img.shields.io/badge/Web-Windows%20%7C%20MacOS%20%7C%20Linux-lightgray.svg)
[![Data-Management](https://img.shields.io/badge/Viewer-v7-green.svg)](http://developer.autodesk.com/)

[![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](http://opensource.org/licenses/MIT)
[![Level](https://img.shields.io/badge/Level-Basic-green.svg)](http://developer.autodesk.com/)

## Thumbnail

![thumbnail](./assets/screenshots.gif)

## Description

This sample demonstrates a way to generate multiple screenshots with Viewer from predefined camera orientations.
I takes adbantage of Viewer's [getScreenShot](https://forge.autodesk.com/en/docs/viewer/v7/reference/Viewing/GuiViewer3D/#getscreenshot-w-h-cb-overlayrenderer) method and [CAMERA_TRANSITION_COMPLETED](https://forge.autodesk.com/en/docs/viewer/v7/reference/Viewing/#camera-transition-completed) event.
To take advantage of it, you can use any JSON file with the format just like the `sampleViews.json` file.
In there, we have multiple arrays that can be used to configure the camera object.
From any specific configuration, you can use [getCameraFromViewArray](https://forge.autodesk.com/en/docs/viewer/v7/reference/Viewing/GuiViewer3D/#getcamerafromviewarray-params-model) method to check the corresponding array.

## Live version

You can run this sample live here:

https://joaomartins-forge.github.io/issues-snapshots/index.html

## License

This sample is licensed under the terms of the [MIT License](http://opensource.org/licenses/MIT). Please see the [LICENSE](LICENSE) file for full details.

## Written by

João Martins [@JooPaulodeOrne2](http://twitter.com/JooPaulodeOrne2), [Developer Advocate and Support](http://forge.autodesk.com)
