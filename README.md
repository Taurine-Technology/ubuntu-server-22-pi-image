# Ubuntu Server 22 Pi Image

A custom OVS-enabled Raspberry Pi Image with Docker, a bridge and L2 enabled by default.

## Instructions

1. Download the custom image [here](https://drive.google.com/file/d/17xGv5WzuEfAZAtMVd2uxTc1b7eSnCX89/view?usp=sharing).
2. Calculate its SHA-256 hash and ensure it matches the value in [hash.txt](./hash.txt). On Linux this is done as follows: `sha256sum taurine-pi-ubuntu-server-22.img.gz`,
3. Use Raspberry Pi imager to write this image to an SD card.
