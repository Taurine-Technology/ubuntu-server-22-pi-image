# Ubuntu Server Pi Images

Custom OVS-enabled Raspberry Pi Images with Docker, a bridge and L2 capabilities enabled by default.

## Ubuntu 20 Instructions

1. Download the custom image [here](https://drive.google.com/file/d/1w8OCs4Kleek1VZXgGsr5XNq8zwlYHGR7/view?usp=sharing).
2. Calculate its SHA-256 hash and ensure it matches the value in [hash.txt](./hash.txt). On Linux this is done as follows: `sha256sum taurine-ubuntu-20-server.img.gz`,
3. Use Raspberry Pi imager to write this image to an SD card.
