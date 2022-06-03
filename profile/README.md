# Welcome to µOS++!

**µOS++ IIIe** (_micro oh ɛs plus plus third edition_) is the third iteration of µOS++, a POSIX-like, portable, open source, royalty-free, multi-tasking real-time framework intended for 32/64-bits embedded applications, written in C++. ([User's manual](http://micro-os-plus.github.io/user-manual/), [API reference](http://micro-os-plus.github.io/reference/cmsis-plus/))

The original monolithic version of the project is available from:

- [micro-os-plus-iii](https://github.com/micro-os-plus/micro-os-plus-iii)
- [micro-os-plus-iii-cortexm](https://github.com/micro-os-plus/micro-os-plus-iii-cortexm)

## µOS++ source packages

Work is currently under way to a modularise the project, with code split over several source packages, each stored in a separate Git repo.

The projects are listed below, in alphabetical order. The **version** badge shows the package.json version in the stable branch (`xpack`), and the **tag** badge shows the latest tag by date.

- [architecture-cortexa-xpack](https://github.com/micro-os-plus/architecture-cortexa-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/architecture-cortexa-xpack)](https://github.com/micro-os-plus/architecture-cortexa-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/architecture-cortexa-xpack)](https://github.com/micro-os-plus/architecture-cortexa-xpack/tags/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/architecture-cortexa.svg?color=blue)](https://www.npmjs.com/package/@micro-os-plus/architecture-cortexa/)
- [architecture-cortexm-xpack](https://github.com/micro-os-plus/architecture-cortexm-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/architecture-cortexm-xpack)](https://github.com/micro-os-plus/architecture-cortexm-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/architecture-cortexm-xpack)](https://github.com/micro-os-plus/architecture-cortexm-xpack/tags/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/architecture-cortexm.svg?color=blue)](https://www.npmjs.com/package/@micro-os-plus/architecture-cortexm/)
- [architecture-riscv-xpack](https://github.com/micro-os-plus/architecture-riscv-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/architecture-riscv-xpack)](https://github.com/micro-os-plus/architecture-riscv-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/architecture-riscv-xpack)](https://www.npmjs.com/package/@micro-os-plus/architecture-riscv/)
- [architecture-synthetic-posix-xpack](https://github.com/micro-os-plus/architecture-synthetic-posix-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/architecture-synthetic-posix-xpack)](https://github.com/micro-os-plus/architecture-synthetic-posix-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/architecture-synthetic-posix-xpack)](https://github.com/micro-os-plus/architecture-synthetic-posix-xpack/tags/)
- [build-helper-xpack](https://github.com/micro-os-plus/build-helper-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/build-helper-xpack)](https://github.com/micro-os-plus/build-helper-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/build-helper-xpack)](https://github.com/micro-os-plus/build-helper-xpack/tags/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/build-helper.svg?color=blue)](https://www.npmjs.com/package/@micro-os-plus/build-helper/)
- [cmsis-os-xpack](https://github.com/micro-os-plus/cmsis-os-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/cmsis-os-xpack)](https://github.com/micro-os-plus/cmsis-os-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/cmsis-os-xpack)](https://github.com/micro-os-plus/cmsis-os-xpack/tags/)
- [devices-cortexm-xpack](https://github.com/micro-os-plus/devices-cortexm-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/devices-cortexm-xpack)](https://github.com/micro-os-plus/devices-cortexm-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/devices-cortexm-xpack)](https://github.com/micro-os-plus/devices-cortexm-xpack/tags/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/devices-cortexm.svg?color=blue)](https://www.npmjs.com/package/@micro-os-plus/devices-cortexm/)
- [devices-qemu-cortexm-xpack](https://github.com/micro-os-plus/devices-qemu-cortexm-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/devices-qemu-cortexm-xpack)](https://github.com/micro-os-plus/devices-qemu-cortexm-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/devices-qemu-cortexm-xpack)](https://github.com/micro-os-plus/devices-qemu-cortexm-xpack/tags/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/devices-qemu-cortexm.svg?color=blue)](https://www.npmjs.com/package/@micro-os-plus/devices-qemu-cortexm/)
- [devices-sifive-xpack](https://github.com/micro-os-plus/devices-sifive-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/devices-sifive-xpack)](https://github.com/micro-os-plus/devices-sifive-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/devices-sifive-xpack)](https://github.com/micro-os-plus/devices-sifive-xpack/tags/)
- [devices-stm32f0-extras-xpack](https://github.com/micro-os-plus/devices-stm32f0-extras-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/devices-stm32f0-extras-xpack)](https://github.com/micro-os-plus/devices-stm32f0-extras-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/devices-stm32f0-extras-xpack)](https://github.com/micro-os-plus/devices-stm32f0-extras-xpack/tags/)
- [devices-stm32f4-extras-xpack](https://github.com/micro-os-plus/devices-stm32f4-extras-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/devices-stm32f4-extras-xpack)](https://github.com/micro-os-plus/devices-stm32f4-extras-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/devices-stm32f4-extras-xpack)](https://github.com/micro-os-plus/devices-stm32f4-extras-xpack/tags/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/devices-stm32f4-extras.svg?color=blue)](https://www.npmjs.com/package/@micro-os-plus/devices-stm32f4-extras/)
- [diag-trace-xpack](https://github.com/micro-os-plus/diag-trace-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/diag-trace-xpack)](https://github.com/micro-os-plus/diag-trace-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/diag-trace-xpack)](https://github.com/micro-os-plus/diag-trace-xpack/tags/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/diag-trace.svg?color=blue)](https://www.npmjs.com/package/@micro-os-plus/diag-trace/)
[![npm](https://img.shields.io/npm/dt/@micro-os-plus/diag-trace)](https://www.npmjs.com/package/@micro-os-plus/diag-trace/)
- [libs-c-xpack](https://github.com/micro-os-plus/libs-c-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/libs-c-xpack)](https://github.com/micro-os-plus/libs-c-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/libs-c-xpack)](https://github.com/micro-os-plus/libs-c-xpack/tags/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/libs-c.svg?color=blue)](https://www.npmjs.com/package/@micro-os-plus/libs-c/)
- [libs-cpp-estd-xpack](https://github.com/micro-os-plus/libs-cpp-estd-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/libs-cpp-estd-xpack)](https://github.com/micro-os-plus/libs-cpp-estd-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/libs-cpp-estd-xpack)](https://github.com/micro-os-plus/libs-cpp-estd-xpack/tags/)
- [libs-cpp-xpack](https://github.com/micro-os-plus/libs-cpp-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/libs-cpp-xpack)](https://github.com/micro-os-plus/libs-cpp-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/libs-cpp-xpack)](https://github.com/micro-os-plus/libs-cpp-xpack/tags/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/libs-cpp.svg?color=blue)](https://www.npmjs.com/package/@micro-os-plus/libs-cpp/)
- [memory-allocators-xpack](https://github.com/micro-os-plus/memory-allocators-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/memory-allocators-xpack)](https://github.com/micro-os-plus/memory-allocators-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/memory-allocators-xpack)](https://github.com/micro-os-plus/memory-allocators-xpack/tags/)
- [micro-test-plus-xpack](https://github.com/micro-os-plus/micro-test-plus-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/micro-test-plus-xpack)](https://github.com/micro-os-plus/micro-test-plus-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/micro-test-plus-xpack)](https://github.com/micro-os-plus/micro-test-plus-xpack/tags/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/micro-test-plus.svg?color=blue)](https://www.npmjs.com/package/@micro-os-plus/micro-test-plus/)
[![npm](https://img.shields.io/npm/dt/@micro-os-plus/micro-test-plus)](https://www.npmjs.com/package/@micro-os-plus/micro-test-plus/)
- [platform-sifive-arty-xpack](https://github.com/micro-os-plus/platform-sifive-arty-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/platform-sifive-arty-xpack)](https://github.com/micro-os-plus/platform-sifive-arty-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/platform-sifive-arty-xpack)](https://github.com/micro-os-plus/platform-sifive-arty-xpack/tags/)
- [platform-sifive-hifive1-xpack](https://github.com/micro-os-plus/platform-sifive-hifive1-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/platform-sifive-hifive1-xpack)](https://github.com/micro-os-plus/platform-sifive-hifive1-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/platform-sifive-hifive1-xpack)](https://github.com/micro-os-plus/platform-sifive-hifive1-xpack/tags/)
- [platform-stm32f4discovery-xpack](https://github.com/micro-os-plus/platform-stm32f4discovery-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/platform-stm32f4discovery-xpack)](https://github.com/micro-os-plus/platform-stm32f4discovery-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/platform-stm32f4discovery-xpack)](https://github.com/micro-os-plus/platform-stm32f4discovery-xpack/tags/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/platform-stm32f4discovery.svg?color=blue)](https://www.npmjs.com/package/@micro-os-plus/platform-stm32f4discovery/)
- [posix-io-xpack](https://github.com/micro-os-plus/posix-io-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/posix-io-xpack)](https://github.com/micro-os-plus/posix-io-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/posix-io-xpack)](https://github.com/micro-os-plus/posix-io-xpack/tags/)
- [rtos-xpack](https://github.com/micro-os-plus/rtos-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/rtos-xpack)](https://github.com/micro-os-plus/rtos-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/rtos-xpack)](https://github.com/micro-os-plus/rtos-xpack/tags/)
- [semihosting-xpack](https://github.com/micro-os-plus/semihosting-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/semihosting-xpack)](https://github.com/micro-os-plus/semihosting-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/semihosting-xpack)](https://github.com/micro-os-plus/semihosting-xpack/tags/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/semihosting.svg?color=blue)](https://www.npmjs.com/package/@micro-os-plus/semihosting/)
- [startup-xpack](https://github.com/micro-os-plus/startup-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/startup-xpack)](https://github.com/micro-os-plus/startup-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/startup-xpack)](https://github.com/micro-os-plus/startup-xpack/tags/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/startup.svg?color=blue)](https://www.npmjs.com/package/@micro-os-plus/startup/)
- [utils-lists-xpack](https://github.com/micro-os-plus/utils-lists-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/utils-lists-xpack)](https://github.com/micro-os-plus/utils-lists-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/utils-lists-xpack)](https://github.com/micro-os-plus/utils-lists-xpack/tags/)
- [version-xpack](https://github.com/micro-os-plus/version-xpack/)
[![GitHub package.json version](https://img.shields.io/github/package-json/v/micro-os-plus/version-xpack)](https://github.com/micro-os-plus/version-xpack/blob/xpack/package.json)
[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/micro-os-plus/version-xpack)](https://github.com/micro-os-plus/version-xpack/tags/)
[![npm (scoped)](https://img.shields.io/npm/v/@micro-os-plus/version.svg?color=blue)](https://www.npmjs.com/package/@micro-os-plus/version/)

## 3rd party source packages

There are also several source packages with 3rd party content, grouped in a separate GitHub organisation [xpack-3rd-party](https://github.com/xpack-3rd-party).

## The web sources

The project [web site](http://micro-os-plus.github.io/) is generated using Jekyll from the markdown
content available in the [web-jekyll](https://github.com/micro-os-plus/web-jekyll) repo.
A preview of the development branch is published at [web-preview](http://micro-os-plus.github.io/web-preview/).

## Other repos

- [helper-scripts](https://github.com/micro-os-plus/helper-scripts)

To clone all source xPack repos on a new machine, use the
[clone-and-link-all-git-repos.sh](https://github.com/micro-os-plus/helper-scripts/blob/master/clone-and-link-all-git-repos.sh) script.

```sh
curl -L https://raw.githubusercontent.com/micro-os-plus/helper-scripts/master/clone-and-link-all-git-repos.sh -o ~/Downloads/clone-and-link-all-git-repos.sh

bash ~/Downloads/clone-and-link-all-git-repos.sh

ls -l ~/Work/micro-os-plus-xpack-repos
```

## Badges

Credit for the badges go to [Shields IO](https://shields.io).

