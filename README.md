# kitadai31/revanced-cli

This is ReVanced CLI fork for [kitadai31/revanced-patches-android6-7](https://github.com/kitadai31/revanced-patches-android6-7) and [d4n3436/revanced-patches-android5](https://github.com/d4n3436/revanced-patches-android5).

Forked from [ReVanced CLI v3.1.1](https://github.com/ReVanced/revanced-cli/releases/tag/v3.1.1)

### Differences from original revanced-cli v3.1.1

- Added dummy cli options for compatibility with Revancify and auto-cli
- Added `--rip-lib` and `--unsigned` (from j-hc)
- Fixed a bug that patched APK contains garbage files in "res" directory
- Switched revanced-pacher to [fork](https://github.com/kitadai31/revanced-patcher) to improve performance
