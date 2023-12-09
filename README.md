# LLVM Builds

This repository acts as a host for pre-built LLVM releases using github actions to build them.

## Builds

### Arch

- Linux (ubuntu 20.04) x86_64
- Windows x86_64
- Mac x86_64

### Version

- 16.0.6
- 17.0.6

## Notes

- Github Actions don't support Aarch runners at this time so only x86 builds are provided
- Windows builds are `.7z` files but have the file extension `exe` because that is how it is done
  on the llvm-project repository
