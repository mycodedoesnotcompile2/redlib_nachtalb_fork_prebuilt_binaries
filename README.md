More target releases of Nachtalb fork of redlib.  
See [Releases](https://github.com/mycodedoesnotcompile2/redlib_nachtalb_fork_prebuilt_binaries/releases) for prebuilt binaries.

### Architectures

| Architecture | Targets |
|---|---:|
| AArch64 (ARM64) | 4 |
| ARM (32-bit) | 3 |
| ARMv7 | 3 |
| i686 (x86 32-bit) | 2 |
| MIPS64EL | 2 |
| RISC-V 64-bit (riscv64gc) | 2 |
| x86_64 (AMD64) | 5 |
| **Total** | **21** |

### Operating Systems

| Operating System | Targets |
|---|---:|
| Linux | 15 |
| macOS (Darwin) | 2 |
| Android | 2 |
| Windows | 2 |

### Complete Target Triplets

| Architecture | OS | ABI / Environment |
|---|---|---|
| aarch64 | macOS | apple-darwin |
| aarch64 | Android | linux-android |
| aarch64 | Linux | GNU, musl |
| arm | Linux | gnueabihf, musleabi, musleabihf |
| armv7 | Android | androideabi |
| armv7 | Linux | gnueabihf, musleabihf |
| i686 | Windows | MSVC |
| i686 | Linux | GNU |
| mips64el | Linux | GNU ABI64, musl ABI64 |
| riscv64gc | Linux | GNU, musl |
| x86_64 | macOS | apple-darwin |
| x86_64 | Windows | GNU, MSVC |
| x86_64 | Linux | GNU, musl |

### Linux libc / ABI Support

- **glibc:** `*-unknown-linux-gnu`
- **glibc hard-float:** `*-unknown-linux-gnueabihf`
- **musl:** `*-unknown-linux-musl`
- **musl EABI:** `*-unknown-linux-musleabi`
- **musl EABI hard-float:** `*-unknown-linux-musleabihf`
- **MIPS64 GNU ABI:** `mips64el-unknown-linux-gnuabi64`
- **MIPS64 musl ABI:** `mips64el-unknown-linux-muslabi64`

### Unsupported Targets

- FreeBSD, OpenBSD, NetBSD
- illumos / Solaris
- PowerPC / PowerPC64
- s390x
- 32-bit MIPS

