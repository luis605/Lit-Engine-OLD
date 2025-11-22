<p align="center">
  <img src="https://github.com/luis605/Lit-Engine-OLD/blob/main/Docs/images/icon.png" width=30% height=30%>
</p>

> [!WARNING]
> Lit Engine's development was restarted and this repository is no longer maintained. \
> Please migrate to https://github.com/luis605/Lit-Engine.

Lit Engine is an **open-source high-level game engine** powered by raylib. Made with the speed and portability of C++, Lit Engine allows you to build 3D experiences with minimal effort, and our intuitive interface will quickly launch you into the development world.

**Give a :star: if you find the project useful! Your support helps the project to keep innovating and delivering exciting features.**

![Number of GitHub contributors](https://img.shields.io/github/contributors/luis605/Lit-Engine)
[![Number of GitHub issues that are open](https://img.shields.io/github/issues/luis605/Lit-Engine)](https://github.com/luis605/Lit-Engine/issues)
![Number of GitHub closed issues](https://img.shields.io/github/issues-closed/luis605/Lit-Engine)
![Number of GitHub pull requests that are open](https://img.shields.io/github/issues-pr-raw/luis605/Lit-Engine)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/luis605/Lit-Engine)
[![Website](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://litengine.org/)
[![Number of GitHub stars](https://img.shields.io/github/stars/luis605/Lit-Engine)](https://github.com/luis605/Lit-Engine/stargazers)

~~*Lit Engine is in active development. Contributions and feedback are highly appreciated!*~~

**IMPORTANT NOTE:** *Lit Engine's development is paused due (probably for just some months) to personal burnout and lack of motivation. Contributions and feedback are highly appreciated! If you want to see future development, let me know! :)*

<hr>

# Quickstart
## 1. Clone the Repository

First, clone the repository and its submodules.

```bash
git clone --recurse-submodules --shallow-submodules -j2 https://github.com/luis605/Lit-Engine
cd Lit-Engine
```

If you cloned without `--recurse-submodules`, you can fetch them with:
```bash
git submodule update --init --recursive --depth 1

```

## 2. Install, Build, and Run
### Linux

Choose the instructions for your operating system.

<details>
<summary><b>Linux</b></summary>

```bash

# 1. Install dependencies
cd Install
sudo ./install.sh
cd ..

# 2. Configure and build the project
mkdir build && cd build
cmake -DCMAKE_POLICY_VERSION_MINIMUM=3.5 ..
make -j4

# 3. Run the engine
make run

# Optional: To run the debugger
# First, build in debug mode: cmake .. -DCMAKE_BUILD_TYPE=Debug
# Then, run: make debug
```

</details>
<details>
<summary><b>Windows</b></summary>

```bash

# 1. Install dependencies
cd Install
.\install.bat
cd ..

# 2. Configure and build the project
mkdir build && cd build
cmake -DCMAKE_POLICY_VERSION_MINIMUM=3.5 .. # Both MinGW Makefiles and Microsoft Visual Studio are supported.
make -j4

# 3. Run the engine
make run

# Optional: If you are using MinGW Makefiles and you want to run the debugger (using GDB)
# First, build in debug mode: cmake .. -G "MinGW Makefiles" -DCMAKE_BUILD_TYPE=Debug
# Then, run: make debug
```

</details>

# Screenshots

![Lit Engine Screenshot 1](https://github.com/luis605/Lit-Engine/blob/main/Docs/images/screenshot1.webp?raw=true)

# Documentation

Documentation is available at https://litengine.org/manual.

**Note:** Our documentation isn't yet finished!

# Contributors
<a href="https://github.com/luis605/Lit-Engine/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=luis605/Lit-Engine&max=400&columns=20" />
  <img src="https://us-central1-tooljet-hub.cloudfunctions.net/github" width="0" height="0" />
</a>

# Socials
### Find us here!

[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCP38rM1LFbABOVdd67p2-NQ)

[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/XqUZQCxrs6)

[![LitEngine](https://img.shields.io/badge/LitEngine-orange?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy533cub3JnLzIwMDAvc3ZnIiB2aWV3Qm94PSIwIDAgNDkgNDkiIHhtbGnsPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3dlaHRlLWxpdmUiPgogIDxwYXRoIGQ9Ik0zMS42NiAzNy4zMyYjM4MzgzOCA0OS42NiAxNi45OSYjMzgzODAwIDI0LjMxNyAwJiM0MWM2LjU0LTYuNTQgMTUuNzEtNy42NyAyMy4xMi0wLjkydjMwLjE2Yy03LjQxLTAuNjgtMTMuNTQtMi44Ni0xOS42Ni02LjU0eiIgZmlsbD0iI2ZmZmZmZiIvPjwvc3ZnPg==)](https://litengine.org)

# License
Check [LICENSE.md](https://github.com/luis605/Lit-Engine/blob/main/LICENSE) for more information.
