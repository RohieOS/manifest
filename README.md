![RohieOS](https://i.imgur.com/bgk8Ql0.png[/img])

# RohieOS Meow [![Download RohieOS](https://img.shields.io/sourceforge/dt/rohieos.svg)](https://sourceforge.net/projects/rohieos/files/r/)  [![Download RohieOS](https://img.shields.io/sourceforge/dm/rohieos.svg)](https://sourceforge.net/projects/rohieos/files/r/)  
The Pure AOSP Experience Which Every Users Want With Basic Features.
Based On CAF, With Meow Icons

### Requirements
Before start to compiling RohieOS for your own device, some requirements as explained bellow:
- 16GB RAM (Swap can be helpful)
- Quadcore Processor
- 150GB Free Disk Space

---------------------------------------------------------------------------------------

 Getting Started:
 ==============

To get started with manifest/RohieOS, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize your local repository, use a command like this:

```bash
repo init -u https://github.com/RohieOS/manifest.git -b 11

```
You can alternatively use this command to save some space and time :

```bash
repo init --depth=1 -u https://github.com/RohieOS/manifest.git -b 11

```

Then to sync up:

```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
You can just use `repo sync` or above command, but this will save you from lot of terminal spam, data and time.
```bash
repo sync -c -q --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
---------------------------------------------------------------------------------------
 Compilation of  RohieOS:
 ==================

From root directory of project, perform following commands in terminal

```bash
$ . build/envsetup.sh
$ lunch aosp_<device_codename>-buildtype
$ m rohie
```
---------------------------------------------------------------------------------------
 Maintainership:
 ================

 Apply for official maintainership [**Here**](https://t.me/rohieos)

---------------------------------------------------------------------------------------
 TeamRohieOS
 ===============

 * [**Manish Sarkar**](https://t.me/Manish4586) - Founder & Lead Developer
 

