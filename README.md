# bpftrace-android-patches
Patches to build bpftrace dependencies for Android with the android NDK 21 pre.

Many of these patches are based on https://github.com/michalgr/bpftrace/tree/build_scripts_for_android and https://github.com/michalgr's instructions for how he built android with NDK 17.

Some patches were added to this set to work-around issues not outlined there. I'll try and credit michal's thorough work here where I can, as he lead the exploration and had I not known it was possible to build bpftrace for android, I likely would have given up while developing this patchset.

The libelf patches are my own, and my major contribution is to update his work, and codify it in CMake, which is the build system bpftrace already uses.
