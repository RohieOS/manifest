# Rohie OS #
Meow or Never

# Initialize Source
repo init -u https://github.com/RohieOS/manifest -b r

# Sync
repo sync -c -j$(nproc --all) --no-clone-bundle --no-tags

### Build ###

bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
