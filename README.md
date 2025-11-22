# AoD Toggle
<img width="480" height="518" alt="Screenshot_20251123-000226" src="https://github.com/user-attachments/assets/9e9629b9-f223-4f1d-a6b8-2e54b479b009" />
<img width="480" height="518" alt="Screenshot_20251123-000256" src="https://github.com/user-attachments/assets/77cfa6c7-4613-4397-bde9-57446a48e267" />

[![GitHub release](https://img.shields.io/github/release/Alberto97/AlwaysOnDisplayToggle.svg?logo=github)](https://github.com/HackZy01/AoDToggle/releases/latest)
[![GitHub license](https://img.shields.io/github/license/Alberto97/AlwaysOnDisplayToggle)](https://github.com/Alberto97/AlwaysOnDisplayToggle/blob/master/LICENSE)

Hassle-free AoD toggle that Google didn't implement

## Permissions

The app requires the ```WRITE_SECURE_SETTINGS``` permission to be able to toggle AoD on and off.\
You can grant it with [Shizuku](https://shizuku.rikka.app/) or adb:

```bash
adb shell pm grant org.alberto97.aodtoggle android.permission.WRITE_SECURE_SETTINGS
```
or in case of multiple users (`<userId>` is listed as first number in output of `adb shell pm list users`):
```bash
adb shell pm grant --user <userId> org.alberto97.aodtoggle android.permission.WRITE_SECURE_SETTINGS
```

Please note that this app has only been tested on Google Pixels.\
Different manufacturers may have implemented AoD their own way and therefore the app might not work.
