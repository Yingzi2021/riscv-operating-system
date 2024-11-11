**Step by step, learn to develop an operating system on RISC-V**

# Operating environment

Environment:

```
Linux boying-BOHL-WXX9 6.8.0-45-generic #45~22.04.1-Ubuntu SMP PREEMPT_DYNAMIC Wed Sep 11 15:25:05 UTC 2 x86_64 x86_64 x86_64 GNU/Linux
```

Install necessary toolchain:

```
$ sudo apt update
$ sudo apt install build-essential gcc make perl dkms git gcc-riscv64-unknown-elf gdb-multiarch qemu-system-misc
```

# Building and usage

- `make`：Compile and build
- `make run`：Start qemu and run
- `make debug`：Start debugging
- `make code`：Disassemble to view binary code
- `make clean`：cleanup

For specific use, please refer to the Makefile under the specific sub-project.

# References

The design of this course refers to the following network resources, thank you :)

- The Adventures of OS：<https://osblog.stephenmarz.com/index.html>
- mini-riscv-os: <https://github.com/cccriscv/mini-riscv-os>
- Xv6, a simple Unix-like teaching operating system：<https://pdos.csail.mit.edu/6.828/2020/xv6.html>
