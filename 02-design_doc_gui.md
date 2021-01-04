# Design Document GUI Project

* **Authors:** [helgee](https://github.com/helgee)
* **State:** draft

## Goals

* Visualize orbits and trajectories in a visually pleasing and accurate way
* Run on all major operating systems: Windows, macOS, Linux
* Provide an "OpenAstrodynamics distribution" with all software and data necessary to get started
* Provide GUI elements for common tasks together with an "escape hatch" for scripting

### Stretch Goals

* Enable use of specialized controllers, e.g. gamepads, 3D mice
* Run in a web browser to enable SaaS deployment
* Work with VR/AR frameworks

### Non-Goals

* Run on mobile devices

## Technology

* Open source game engines
	* [Godot](https://godotengine.org)
	* [Bevy](https://bevyengine.org)
* Open source special purpose renderers
	* [Celestia](https://celestia.space)
	* [OpenFrames](https://github.com/ravidavi/OpenFrames)
	* [VTS](https://logiciels.cnes.fr/en/content/vts)
	* [Skybolt](https://github.com/Piraxus/Skybolt)
* WebGL-based frameworks
	* [Three.js](https://threejs.org)
	* [Babylon.js](https://www.babylonjs.com)
	* [Cesium.js](https://cesium.com/cesiumjs)
	* [elm-3d-scene](https://github.com/ianmackenzie/elm-3d-scene)
* Commercial game engines
	* [Unity](https://unity.com)
	* [Unreal](https://www.unrealengine.com)
