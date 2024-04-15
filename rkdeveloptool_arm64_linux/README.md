Runing rkdeveloptool with GNU elf loader:

```sh
$ ls ./rkdev
ld-linux-aarch64.so.1  libc.so.6  libgcc_s.so.1  libm.so.6  libstdc++.so.6  libudev.so.1  libusb-1.0.so.0  log  rkdeveloptool

$ sudo LD_LIBRARY_PATH=./rkdev ./rkdev/ld-linux-aarch64.so.1 ./rkdev/rkdeveloptool
```
