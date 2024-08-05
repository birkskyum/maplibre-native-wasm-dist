# MapLibre Native - WebAssembly compilation

There are multiple paths to compile MapLibre Native to WebAssembly (WASM), and some even enable running MapLibre Native in the browser.

The purpose of this repo is to track progress, document and demonstrate these paths as they evolve.

### Qt for WebAssembly

[MapLibre Native Qt](https://github.com/maplibre/maplibre-native-qt) makes it easy to build Mobile and Desktop apps with MapLibre in C++.

[Qt for WebAssembly](https://doc.qt.io/qt-6/wasm.html) allow those apps to run on the Web as well!

Note: Be sure to verify your use-case is within Qt's license.

#### Roadmap
Compilation and deployment of our Widget example app
- ✅ WebGL1 ( [Try Demo!](https://maplibre-native-wasm-dist.pages.dev/qt-opengl2/) ) - ( [Build guide and binaries](https://github.com/birkskyum/maplibre-native-wasm-dist/tree/main/qt-opengl2) ) - [Ref. Ticket](https://github.com/maplibre/maplibre-native-qt/issues/49)
- ⌛ WebGL2 - [Ref. Ticket
](https://github.com/maplibre/maplibre-native-qt/issues/147)
- ⌛ WebGPU - [Ref. Ticket
](https://github.com/maplibre/maplibre-native-qt/issues/153)

Side quests and optmizations to be made:
- ⌛ Move from Asynchify to JSPI ( [more info](https://v8.dev/blog/jspi) )
- ⌛ Autogenerated TypeScript type declarations
- ⌛ Public API exposed to JS

### GLFW
- ⌛ WebGL2 demo
- ⌛ WebGPU demo

### Kotlin WASM / Compose Multiplatform

Compose ticket [here](https://github.com/maplibre/maplibre-native/issues/2638).

More info on Compose Multiplatform [here](https://www.jetbrains.com/lp/compose-multiplatform/).

More info on Kotlin WASM [here](https://kotlinlang.org/docs/wasm-overview.html).

### Flutter for Web

Currently, the https://github.com/maplibre/flutter-maplibre-gl uses MapLibre GL JS for the web target.

It is technically possible to use a wasm build of Native for web as well, which would give identical rendering and feature set.

Work is not started. More info [here](https://flutter.dev/multi-platform/web)

### MapLibre Native Core

- ⌛ WebGL2 - [Ref. Ticket](https://github.com/maplibre/maplibre-native/issues/2554)
- ⌛ WebGPU
