# GUISAN

![logo](examples/guisan.png "GUISAN")

## An SDL2 GUI construction toolkit

[![Build Status](https://github.com/kallisti5/guisan/actions/workflows/build.yaml/badge.svg)](https://github.com/kallisti5/guisan/actions)
[![Appveyor build status](https://ci.appveyor.com/api/projects/status/2qv4w2pxgc4lqtw5?svg=true)](https://ci.appveyor.com/project/gbaudic/guisan)
[<img src="https://ko-fi.com/img/githubbutton_sm.svg" height="20px" />](https://ko-fi.com/Q5Q2QF1PE)

Check out the online [Doxygen documentation](https://codedocs.xyz/gbaudic/guisan).

Guisan was forked from Guichan to create a simple GUI construction toolkit that is compatible with SDL 2.0.0+. It is primarily intended for use in games. If you need a full-fledged GUI toolkit, other libraries like GTK+ or Qt will be more appropriate. 

It compiles and runs on Linux, Windows (MSYS2) and Windows (Visual Studio). Mac is not tested. 

## Features

* Statically links to your applications to reduce runtime requirements
* Small, but effective

## How to use

Check the wiki of this repo for a list of available widgets, some general advice on how to integrate into your programs. The examples and demo in the repo will be helpful too. 

## Build requirements

* scons
* pkg-config

## Runtime requirements

* SDL 2.0+
* SDL2_image
* SDL2_ttf
* SDL2_mixer (for the demo)

## Example

![openglwidget](examples/opengldemo.png)

## License:

Released under the BSD license. See COPYING for more details. 
