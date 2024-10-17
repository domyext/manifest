# DomyEXT Repository Manifest

Utilize Google's git-repo to make it easier to track mulltiple repositories at once.

## Getting started

## Creating a work directory
```
mkdir -p ~/domyext
cd ~/domyext
```

### Downloading source
```
repo init -u https://github.com/domyext/manifest -b main
repo sync -j4
```