# BeagleBone Repo Manifest

## How to

### Install repo

To use this manifest repo, the 'repo' tool must be installed first.

```bash
mkdir ~/bin
curl http://commondatastorage.googleapis.com/git-repo-downloads/repo  > ~/bin/repo
chmod a+x ~/bin/repo
PATH=${PATH}:~/bin
```

### Sync Repo

```bash
mkdir yocto-beaglebone
cd yocto-beaglebone
repo init -u https://github.com/tmoore3/beaglebone-manifest.git
repo sync
```
