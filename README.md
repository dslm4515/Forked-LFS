# Forked-LFS (32+64-bit x86)
A Fork of Thomas' Multilib Linux From Scratch, using the build method that was dropped after LFS 9.0

This is the 64+32-bit x86 Multi-Library build of LFS.

This is based on the work of Thomas' Multilib Linux From Scratch (https://www.linuxfromscratch.org/~thomas/multilib-m32), which now uses a different build method based on LFS versions newer than 9.0. This new build method does not work on musl libc based hosts. The `tools` toolchain built here is sandboxed and portable, making it independent from the host's libc.

New users are highly recommended to read Part 1 of the LFS book at http://www.linuxfromscratch.org. There is some material for new users to read in 
`1-Preparation` directory. Experienced users can skip `1-Preparation` and use the `00-Quick-Start` then progress to `2-tools` and `3-chroot` to start right away.

The list of packages and their checksums are found in the `extras` directory of this repo.
