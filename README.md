![MiltonLogo](http://i.imgur.com/hXxloIS.png)

Milton is a modern paint app.

### [Latest release (2016-01-23) pre-alpha 003](https://github.com/serge-rgb/milton/releases/tag/prealpha003)

![Milton Paint girl](http://i.imgur.com/7UmXTlD.png)


Features
--------

- Infinite canvas

    ![zoooom](http://i.imgur.com/fqOhPlr.gif)

    You don't pick a resolution, and you don't work with pixels.  Your work is
stored as a sequence of commands, and rendered on the fly.  Whenever you want
to, you can export your work to bitmaps of any size.

- Simple

    Milton solves a single problem: draw without pixels. It doesn't pretend to
be something more than that.

- Persistent

    No save button. Ctrl-S is *so* 1980's

- Wacom support

    Milton currently supports Wacom on Windows Mac and Linux. The Mac version
supports any tablet device.

- Software rendered.

    Milton features a software rasterizer by design, for reliability and
flexibility.

- Light-weight

- Multi-platform

    Windows, Linux, OSX (Linux and OSX versions are In-Progress)

- Open Source

    Milton is MIT-licensed



What Milton is not:
-------------------

Milton is not an image editor or a vector graphics editor. It's a program that
lets you draw, sketch and paint.

User Manual
===========

If the GUI makes something not-obvious, please create a github issue!

It's very helpful to drag the mouse (or pen) while pressing `space` to pan the
canvas.  Also, switching between the brush and the eraser with `b` and `e`.
You can change the brush size with `[` and `]` and control the transparency
with the number keys.


How to Compile
==============

Milton targets Windows, Linux and OSX.

Windows
-------

Requirements:

- Visual Studio >= 2013 (Community Edition is fine.)

0. Open a developer console. You have at least two options:
    - Open "Developer Command Prompt" and go to Milton's directory.
    - (VS2015 only) Use cmd.exe and run `scripts\vcvars.bat` to have the Visual Studio 2015 suite in your PATH. It will try to use the 64-bit version
1. `build.bat` (The first time will compile dependencies, the next times it should be quick)
2. Milton is compiled to `build\Milton.exe`

Linux
-----

_PORT IN PROGRESS_

Requirements:

- SDL2 development libraries. On Ubuntu, this is `apt-get install libsdl2-dev`
- The clang compiler.

Just run `make`

OSX
---

_PORT IN PROGRESS_

Requirements:

- CMake (for building SDL)

1. `./setup_osx.sh` to download dependencies and build SDL
2. `./build_osx.sh`
3. Milton is compiled to `./build/milton`


License
=======

    Copyright (c) 2015-2016 Sergio Gonzalez

    Permission is hereby granted, free of charge, to any person obtaining a copy of
    this software and associated documentation files (the "Software"), to deal in
    the Software without restriction, including without limitation the rights to
    use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
    of the Software, and to permit persons to whom the Software is furnished to do
    so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.

Credits and Thanks
==================

* Art
    * Milton's logo and first artwork by the very talented [Perla Fierro](http://portafolio.eclat-studio.com/)

* Code
    * [Apoorva Joshi](http://apoorvaj.io) - Author of [Papaya](https://github.com/ApoorvaJ/Papaya) for joining forces and creating [EasyTab](https://github.com/ApoorvaJ/EasyTab).
    * [Michael Freundorfer](https://github.com/mordecai154)
    * [Joshua Mendoza](https://github.com/jomendoz)

* Rubber-ducking / Whiteboarding
    * Rodrigo Gonzalez del Cueto [@rdelcueto](https://twitter.com/rdelcueto)
    * Luis Eduardo Pérez
    * Mom

* The "Jueves Sensual" team :)
    * Axel Becerril
    * Ruben Bañuelos
    * Caro Barberena
    * Carlos Chilazo
    * Roberto Lapuente
    * Joshua Mendoza
    * Maximiliano Monterrubio
    * Santiago Montesinos
    * Aarón Reyes García
    * Vane Ugalde

* Inspiration / Education
    * Casey Muratori for Handmade Hero

