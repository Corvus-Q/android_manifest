### Corvus ROM ###

![CorvusROM](https://raw.githubusercontent.com/Rafiester/Public_Stuff/master/corvus_home.png)
<p align="center">

[![Sourceforge](https://img.shields.io/sourceforge/dm/corvus-os?color=1d91f0&label=RavenLair%20downloads&style=for-the-badge&labelColor=121217&logo=github)](https://corvus-rom.github.io/)
</p>

# Initialize Local Repository #
```bash
repo init -u https://github.com/Corvus-ROM/android_manifest.git -b 10
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
[![XDA-Template](https://raw.githubusercontent.com/Rafiester/Public_Stuff/master/XDADevelopers_button.png)](https://raw.githubusercontent.com/Corvus-ROM/android_manifest/10/xda)

# Maintainership form
[![Form](https://raw.githubusercontent.com/Rafiester/Public_Stuff/master/Submission_button.png)](https://docs.google.com/forms/d/e/1FAIpQLSeOEzQXfNnPehPQRXxmt3L5FYc5neOhEE3m6ZW_xbIuuQ-dCg/viewform?usp=sf_link)

# Telegram Support 
[![Telegram](https://raw.githubusercontent.com/Rafiester/Public_Stuff/master/Telegram_button.png)](https://t.me/corvussupport)

 Credits:
 =======

 * [**DirtyUnicorns**](https://github.com/DirtyUnicorns)
