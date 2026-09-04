# Nerocash Snap Packaging

Commands for building and uploading a Nerocash Core Snap to the Snap Store. Anyone on amd64 (x86_64), arm64 (aarch64), or i386 (i686) should be able to build it themselves with these instructions. This would pull the official Nerocash binaries from the releases page, verify them, and install them on a user's machine.

## Building Locally
```
sudo apt install snapd
sudo snap install --classic snapcraft
sudo snapcraft
```

### Installing Locally
```
snap install \*.snap --devmode
```

### To Upload to the Snap Store
```
snapcraft login
snapcraft register nerocash-core
snapcraft upload \*.snap
sudo snap install nerocash-core
```

### Usage
```
nerocash-unofficial.cli # for nerocash-cli
nerocash-unofficial.d # for nerocashd
nerocash-unofficial.qt # for nerocash-qt
nerocash-unofficial.test # for test_nerocash
nerocash-unofficial.tx # for nerocash-tx
```

### Uninstalling
```
sudo snap remove nerocash-unofficial
```