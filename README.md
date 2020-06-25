# toolchain-arm

Arm release of the pre-built GNU cross-toolchain for the A-profile cores: `10.2-2020.11`.

## arm-none-linux-gnueabihf

Arm toolchain for the ARM architecture. It uses GCC 10.2.1, GDB 10.1,
glibc 2.31 and binutils 2.35.1. It generates code that runs on all
Cortex-A profile devices. The code generated uses the hard floating
point calling convention, and uses the VFPv3-D16 FPU instructions.

## aarch64-none-linux-gnu

Arm toolchain for the AArch64 architecture.
This is the same toolchain that was previously distributed by Linaro.

## Source and related information

Check [Arm Developer / GNU-A Downloads](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain) for details.
