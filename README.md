# Ubuntu Touch for Google Pixel 4a

## How to build

To manually build this project, follow these steps:

```bash
./build.sh -b buildddir  # buildddir is the name of the build directory
./build/prepare-fake-ota.sh out/device_sunfish.tar.xz ota
./build/system-image-from-ota.sh ota/ubuntu_command out
```
