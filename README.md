# ReloadedOS Manifest

## Getting started

To get started with ReloadedOS, you'll need to [set up a Linux build environment](https://source.android.com/docs/setup/start/initializing#setting-up-a-linux-build-environment) and get familiar with [Repo and Git](https://source.android.com/docs/setup/download).

To initialize the ReloadedOS sources locally, use a command like this:
```
 repo init -u https://github.com/ReloadedOS/manifest -b u
```

Then to sync up:
```
 repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune --retry-fetches=5 -j$(nproc --all)
```

## Finally, to build

```
$ source build/envsetup.sh
$ brunch <device>
```
