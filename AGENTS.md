# AGENTS.md — Launcher

## What this is
A simple C application launcher. Minimal C program (helloc_linux) built with CMake.

## Stack
- C
- CMake build system
- GTK/desktop launcher (via run.sh)

## Build
```bash
./build.sh   # runs cmake and make
```

## Run
```bash
./run.sh   # runs the built launcher
```

## Structure
- `src/main.c` — entry point
- `CMakeLists.txt` — build config
- `build.sh` — build script
- `run.sh` — run script
- `helloc_linux` — example/pre-built binary

## Conventions
- No comments in code unless asked.
- Verify: `cmake . && make`