  # Rohie OS #
--##Meow or   Never##--

# Initialize Source
    repo init --depth=1 -u https://github.com/RohieOS/manifest -b r
    

# Sync
    repo sync -c -j$(nproc --all) --no-clone-bundle --no-tags

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
