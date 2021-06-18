### Corvus ROM ###

![CorvusROM](https://raw.githubusercontent.com/Astile97/extras/master/corvus/cover.PNG)
<p align="center">

# Initialize Local Repository #
```bash
repo init -u https://github.com/Corvus-Q/android_manifest.git -b 10
```

# Or Initialize Shallow Clone #
```bash
repo init --depth=1 -u https://github.com/Corvus-Q/android_manifest.git -b 10
```

# Syncing Repository # 
```bash
repo sync -j$(nproc --all) --force-sync --no-tags --no-clone-bundle
```

# Building Environment #
```bash   
# Set up environment
. build/envsetup.sh

# Choose a target
lunch du_device-userdebug

# Build the ROM
make corvus
```
# XDA Template
[![XDA-Template](https://raw.githubusercontent.com/rashedsahaji/RandomStuff/master/XDADevelopers_button.png)](https://raw.githubusercontent.com/Corvus-ROM/android_manifest/10/xda)

# Maintainership form
[![Form](https://raw.githubusercontent.com/rashedsahaji/RandomStuff/master/Submission_button.png)](https://docs.google.com/forms/d/e/1FAIpQLSeOEzQXfNnPehPQRXxmt3L5FYc5neOhEE3m6ZW_xbIuuQ-dCg/viewform?usp=sf_link)

# Telegram Support 
[![Telegram](https://raw.githubusercontent.com/rashedsahaji/RandomStuff/master/Telegram_button.png)](https://t.me/corvuscommunityofficial)

 Credits:
 =======

 * [**DirtyUnicorns**](https://github.com/DirtyUnicorns)

