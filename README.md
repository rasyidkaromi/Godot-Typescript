#  GodotJS - JavaScript language binding for Godot game engine

This module implements JavaScript/TypeScript language support for the Godot game engine using [QuickJS](https://bellard.org/quickjs/) as the JavaScript engine.

## Features

- Almost complete ES2020 support
- All Godot API available
- Operator overriding for built-in types (Vector3, Color, etc)
- TypeScript support
- [Using third-party libraries from npm](https://github.com/GodotExplorer/ECMAScriptDemos/tree/master/npm_module)
- Multi-thread support with Worker API
- Full code completion support for all Godot APIs including signals and enumerations
- Debug in Visual Studio Code with the [plugin](https://marketplace.visualstudio.com/items?itemName=geequlim.godot-javascript-debug) - currently not available for 4.x

### Getting started

Read the [getting-started](https://geequlim.github.io/ECMAScript/getting-started).

## Getting the engine

No installation or setup necessary. The binaries for download are the complete, usable Godot editor and engine with JavaScript/TypeScript language support.

### Binary downloads
Download the binaries from the [release page](https://github.com/GodotExplorer/ECMAScript/releases).

### Compiling from source
- Clone the source code of [godot](https://github.com/godotengine/godot): 
  - ``git clone git@github.com:godotengine/godot.git``  or
  - ``git clone https://github.com/godotengine/godot.git``
- Clone this module and put it into `godot/modules/javascript`: 
	- ``git clone git@github.com:rasyidkaromi/Godot-Typescript.git godot/modules/javascript``  or
	- ``git clone https://github.com/rasyidkaromi/Godot-Typescript.git godot/modules/javascript``
- [Recompile the godot engine](https://docs.godotengine.org/en/4.1/development/compiling/index.html) 
  - Use ``scons`` with those additional options ``warnings=extra werror=yes module_text_server_fb_enabled=yes`` to show all potential errors

## Documentation, Tutorials & Demos

Read this [documentation](https://geequlim.github.io/ECMAScript/getting-started) or look at the tutorials or demos:


- [ECMAScriptDemos](https://github.com/Geequlim/ECMAScriptDemos) - Demos
- [godot-ECMAScript-cookbook](https://github.com/why-try313/godot-ECMAScript-cookbook/wiki) - Tutorial
- [godot-typescript-starter](https://github.com/citizenll/godot-typescript-starter) - Template
