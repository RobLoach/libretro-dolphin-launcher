# libretro-dolphin-launcher

Launch Sony PlayStation 2 games through [PCSX2](https://pcsx2.net/), directly from [RetroArch](http://www.libretro.com/). Based on [libretro-dolphin-launcher](https://github.com/RobLoach/libretro-dolphin-launcher) from Rob Loach.

![Dolphin Launcher Screenshot](screenshot.jpg)

## Installation

1. Compile the core
  ``` bash
  git clone https://github.com/coldscientist/libretro-pcsx2-launcher.git
  cd libretro-pcsx2-launcher
  make
  ```

2. Copy the core file to the RetroArch cores directory
  ``` bash
  cp pcsx2_launcher_libretro.so /usr/lib/libretro/
  ```

3. Make sure [PCSX2](https://pcsx2.net/) [is installed](https://pcsx2.net/download.html). You should be able to run at least one of the following commands:
  ``` bash
  PCSX2
  flatpak run net.pcsx2.PCSX2
  ```

## Usage

1. Scan Sony PlayStation 2 games in RetroArch

2. Launch the games directly from the RetroArch menu

3. Alternatively, you can run games through the command line
  ``` bash
  retroarch -L pcsx2_launcher_libretro.so Crash.iso
  ```

## Contributors

- [Rob Loach](http://github.com/robloach)
- [Alcaro](https://github.com/Alcaro)
- [Eduardo Mozart de Oliveira](https://github.com/coldscientist)
