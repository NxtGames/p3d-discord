<img src="https://avatars3.githubusercontent.com/u/1965106?s=200&v=4" align="right">

[![Build Status](https://travis-ci.com/NxtStudios/libDiscord.svg?branch=master)](https://travis-ci.com/NxtStudios/libDiscord)

libDiscord
============

Discord RPC module for the Panda3d game engine using the native discord-rpc library.


## Building LibDiscord
run `python build.py`. This will build the module for you're current platform once the required dependencies are installed/availble.

### Requirements

- The Panda3D SDK (get it <a href="http://www.panda3d.org/download.php?sdk">here</a>)
- CMake 2.6 or higher (get it <a href="https://cmake.org/download/">here</a>)
- windows only: The thirdparty folder installed in the Panda3D sdk folder (See <a href="https://www.panda3d.org/forums/viewtopic.php?f=9&t=18775">here</a>)
- discord-rpc (get it <a href="https://github.com/discordapp/discord-rpc">here</a>)

**For compiling on Windows 32 bit:**

- Visual Studio 2010/2015

**For compiling on Windows 64 bit:**

- Visual Studio 2010/2015
- Windows SDK 7.1 (be sure to tick the VC++ 64 bit compilers option)

## License
libDiscord is licensed under the MIT license. See the provided LICENSE file for details.

