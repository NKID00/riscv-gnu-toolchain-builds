## riscv-gnu-toolchain auto-builds

GNU/Linux and Windows builds of the latest commit on master branch of [riscv-gnu-toolchain](https://github.com/riscv-collab/riscv-gnu-toolchain).

Builds run automatically at 02:02 UTC on every Tuesday.

GNU/Linux builds are built on Ubuntu 20.04, Windows builds are built on Windows Server 2019 using Mingw-w64 on MSYS2.

## Usage

Download the latest artifact and simply extract it to anywhere you like.

Artifacts of the latest build can be downloaded in [the release page](https://github.com/NKID00/riscv-gnu-toolchain-builds/releases), previous builds(retained for 90 days) can be found in [each workflow run page](https://github.com/NKID00/riscv-gnu-toolchain-builds/actions).

## Naming conventions

Artifacts contain debug symbols are named `*-debug`.

Artifacts contain GDB(The GNU Project Debugger) are named `*-gdb`.

Download `riscv-*-newlib-multilib-gdb.tar.xz`(for GNU/Linux) or `riscv-*-newlib-multilib-gdb-windows.zip`(for Windows) if you don't konw what to do.
