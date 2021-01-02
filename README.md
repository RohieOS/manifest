  # Rohie OS - CAF #
--##Meow or   Never##--

# Initialize Source
    repo init --depth=1 -u https://github.com/RohieOS/manifest -b 11
    

# Sync
    repo sync -c -j$(nproc --all) --no-clone-bundle --no-tags

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ m rohie -jX

