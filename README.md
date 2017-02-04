iOS toolchain for Windows.
==

The iOS toolchain for Windows.

Currently supports 64 bit Windows Vista, 7, 8, 8.1 and 10.

This toolchain requires Cygwin. With python installed **inside Cygwin**

What you get:
==
1. LLVM + Clang 3.9.1
2. LD64 264.3.102
3. CCTools 877.5


What this toolchain supports:
==
1. iOS SDKs up to version 10.2 (may work with higher versions, but untested)
2. Building binaries for arm, armv6, armv7, armv7s and arm64.
3. Objective C 2.0
4. Objective C Blocks (introduced with iOS 4.0)
5. Objective C Literals (introduced with iOS 5.1)
6. Objective C ARC (introduced with iOS 5.0)
7. TBD linker files (introduced with iOS 9.0)

The binaries from this toolchain have been tested and work properly on an iPod touch 5, iPad mini, and iPhone 6, on iOS 6.1.2, 7.1.2, 8.1.2, 8.3, 8.4, 9.0.2, and 9.3.3.
