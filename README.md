# CMAKE stm32F4 example 2022

**To build install:**
 * cmake and make
 * arm-none-eabi toolchain: https://xpack.github.io/blog/2020/07/03/arm-none-eabi-gcc-v9-3-1-1-1-released/
 * make sure cmake,make,arm-none-eabi-gcc are reachable from path

**Run:**
1. `git submodule update --init`
1. `mkdir build && cd build`
2. `cmake ..`
3. `cmake --build . -- -j 16`
4. enjoy


Fallback source:
https://dev.to/younup/cmake-on-stm32-the-beginning-3766
https://github.com/ObKo/stm32-cmake