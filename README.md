# SQL2 Based game - BambiBall

![gamesdl](https://user-images.githubusercontent.com/57843834/165837709-9c2fdecf-7abb-4ad3-bfd4-3727b60023f4.PNG)
 
This project is written in C and uses [CMake][] as a build system.<br>
It shows how we can make a basic animation using [SDL2][sdl] : A ball moving in a map.

It could be used as a base for any SDL2 game. Just fork it, clone it and
execute the `rename_project.sh` script. You will be prompted to enter the new
project name, the new executable name and the new git repository, but you can
keep the autodetected values. Finally, just commit and push the result to your
repository.

# Description

This game was developed during the ISS Course project during my Freshman year at the
Mediterranean Institue of Technology (Medtech). In this game, the player will play with
a ball called Bambi and will have to travel over the map to finish the level and win.

# Authors / Original developers

The project was originally developed by:

- [Amine Ben Hassouna](https://github.com/aminosbh)
- [Mahmoud Mansouri][]
- [Mohamed Achref Liratni][]

# Contributing

Thank you for your interest in our project. There are many ways to contribute,
and we appreciate all of them :

- Source Code
- Unit tests
- Bug Reports
- Documentation
- Localization
- etc

Do not hesitate to open a pull request of you find an error or if you want to add
a features.

Contributions should be under the terms of the MIT license [&lt;LICENSE&gt;](LICENSE).

## Dependencies

For the Dependencies and the build you can directly see them in [Build](BUILD.md)

- [Git][]
- C Compiler (gcc, ...)
- [CMake][]
- [SDL2][sdl] library
- [SDL2_image][] library
- [SDL2_gfx][] library

**On Debian/Ubuntu based distributions, use the following command:**

```sh
sudo apt install git build-essential pkg-config cmake cmake-data libsdl2-dev libsdl2-image-dev libsdl2-gfx-dev
```

This project also use this libraries:

- [SDL2_ttf][] library
- [SDL2_net][] library
- [SDL2_mixer][] library

```sh
sudo apt install libsdl2-ttf-dev libsdl2-net-dev libsdl2-mixer-dev
```

## Build instructions

```sh
# Clone this repo
git clone https://gitlab.com/aminosbh/flying-plane-sdl-animation.git
cd flying-plane-sdl-animation

# Create a build folder
mkdir build
cd build

# Build
cmake ..
make

# Run
./flying-plane-sdl-animation
```

**_Note:_** To use SDL2_ttf, SDL2_net or SDL2_mixer, you should uncomment some
instructions in the CMakeLists.txt file and re-execute the `make` command.

### Open the project with an IDE under Linux

See [IDE_USAGE.md](IDE_USAGE.md) for details.

## License

Author: Amine B. Hassouna [@aminosbh](https://gitlab.com/aminosbh)
[Mahmoud Mansouri]
[Mohamed Achref Liratni]

This project is distributed under the terms of the MIT license
[&lt;LICENSE&gt;](LICENSE).

The images under the assets directory are distributed under different licenses:

- `plane.png` and `plane-shadow.png`:<br>
  Author: Amine B. Hassouna [@aminosbh](https://gitlab.com/aminosbh)<br>
  License: [Creative Commons Attribution 4.0 International License.][ccby]

- `ocean.jpg`:<br>
  Author: [the3rdSequence.com](https://www.the3rdsequence.com)<br>
  License: [Creative Commons Attribution 4.0 International License.][ccby]<br>
  Site: https://www.the3rdsequence.com/texturedb/texture/23/sea+water

[sdl]: https://www.libsdl.org
[cmake]: https://cmake.org
[git]: https://git-scm.com
[sdl2_image]: https://www.libsdl.org/projects/SDL_image
[sdl2_ttf]: https://www.libsdl.org/projects/SDL_ttf
[sdl2_net]: https://www.libsdl.org/projects/SDL_net
[sdl2_mixer]: https://www.libsdl.org/projects/SDL_mixer
[sdl2_gfx]: http://www.ferzkopp.net/wordpress/2016/01/02/sdl_gfx-sdl2_gfx
[ccby]: http://creativecommons.org/licenses/by/4.0/
[mohamed achref liratni]: https://github.com/MohamedLiratni
[mahmoud mansouri]: https://github.com/MahmoudMans
