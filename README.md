# Forked-LFS
A Fork of Linux From Scratch, using the build method that was dropped after LFS 9.0

This is based on the work of Linux From Scratch (http://www.linuxfromscratch.org), which now uses a different build method after version 9.0. This new build method does not work on musl libc based hosts. The `tools` toolchain is sandboxed and portable, making it independent from the host's libc.

New users are highly recommended to read Part 1 of the LFS book at http://www.linuxfromscratch.org. There is some material for new users to read in 
`1-Preparation` directory. Experienced users can skip `1-Preparation` and use the `00-Quick-Start` then progress to `2-tools` and `3-chroot` to start right away.

The list of packages and their checksums are found in the `extras` directory of this repo.
