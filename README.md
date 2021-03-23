# Important Notice:
## This core is deprecated and will no longer be maintained.

Please use https://github.com/libretro/mupen64plus-libretro-nx

# Mupen64Plus

Mupen64Plus is [mupen64plus](https://github.com/mupen64plus/mupen64plus-core) + [GLideN64](https://github.com/gonetz/GLideN64) + [libretro](http://www.libretro.com/)

#### How is this different from [Parallel-N64](https://github.com/libretro/parallel-n64)?

Parallel-N64 implements multiple Graphics plugins. There are also code modifications that make it different than standalone mupen64plus.

Mupen64Plus uses GLideN64 (a graphics plugin that is not available in Parallel-N64). The emulator code itself is identical to standalone mupen64plus.

By choosing one graphics plugin (GLideN64), we will be able to keep the code in line with upstream, and maintaining the code will be much simpler.

#### Acknowledgments

A special thanks to the mupen64plus team, the libretro team, and gonetz and those that have worked on GLideN64.

**Minimum RetroArch version: v1.3.4**

For information on the options look at the [wiki section](https://github.com/libretro/mupen64plus-libretro/wiki#options).

#### Build instructions for OGA and related clones
```
git clone https://github.com/christianhaitian/mupen64plus-libretro.git
cd mupen64plus-libretro
make platform=aarch64 -j${nproc}
strip mupen64plus_libretro.so
```
