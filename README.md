# ZigGameDevStarter

ZigGameDevStarter is a minimal Zig desktop graphics scaffold using GLFW, OpenGL and Dear ImGui from the `zig-gamedev` submodule. The current program creates a window and initializes the UI; it does not contain game logic yet.

## Build and run

Clone the repository with its submodules, install a compatible Zig toolchain and run:

```sh
git clone --recurse-submodules https://github.com/BenMcAvoy/ZigGameDevStarter.git
cd ZigGameDevStarter
zig build run
```

The build graph and platform library setup are defined in `build.zig`.

## Status

This is a starter experiment for trying the Zig game-development libraries, not a finished game or reusable template release.
