# NonceCash Snap Packaging

Commands for building and uploading a NonceCash Core Snap to the Snap Store. Anyone on amd64 (x86_64), arm64 (aarch64), or i386 (i686) should be able to build it themselves with these instructions. This would pull the official NonceCash binaries from the releases page, verify them, and install them on a user's machine.

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
snapcraft register noncecash-core
snapcraft upload \*.snap
sudo snap install noncecash-core
```

### Usage
```
noncecash-unofficial.cli # for noncecash-cli
noncecash-unofficial.d # for noncecashd
noncecash-unofficial.qt # for noncecash-qt
noncecash-unofficial.test # for test_noncecash
noncecash-unofficial.tx # for noncecash-tx
```

### Uninstalling
```
sudo snap remove noncecash-unofficial
```