# LotusOS #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/LotusOS/platform_manifest -b pie

# Sync
repo sync -jx
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch lotus_$device-userdebug

# Build the code
$ mka bacon -jX
