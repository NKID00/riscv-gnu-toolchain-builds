## riscv-gnu-toolchain auto-builds

GNU/Linux and Windows builds of the latest commit on master branch of [riscv-gnu-toolchain](https://github.com/riscv-collab/riscv-gnu-toolchain).

Builds run automatically at 02:02 UTC every day.

Builds with GDB are configured with `./configure --prefix=/opt/riscv/ --enable-multilib`, builds without GDB are configured with `./configure --prefix=/opt/riscv/ --enable-multilib --disable-gdb`.

GNU/Linux builds are built on Ubuntu 20.04. Windows builds are built on Windows Server 2019 using Mingw-w64 on MSYS2.

## Usage

Download the latest artifact and simply extract it to anywhere you like.

Artifacts of the 3 latest builds can be downloaded in [the release page](https://github.com/NKID00/riscv-gnu-toolchain-builds/releases), previous builds(retained for 90 days) can be found in [each workflow run page](https://github.com/NKID00/riscv-gnu-toolchain-builds/actions).

## Naming conventions

Artifacts contain debug symbols are named `*-debug`.

Artifacts contain GDB are named `*-gdb`. GDB builds for Windows are currently broken.

Download `riscv-*-newlib-multilib-gdb.tar.xz`(for GNU/Linux) or `riscv-*-newlib-multilib-windows.zip`(for Windows) if you don't know what to do.
