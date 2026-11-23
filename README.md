# SunTec Floor Plan Maker

Downloads for the **SunTec Floor Plan Maker** desktop app, which turns a Leica BLK2GO point cloud (.e57) into a 2D floor plan and an NS 3940 area schedule (DWG, DXF, PDF, PNG and Excel). This repository holds only the installers; there is no source code here.

## Download

| Computer | File |
|---|---|
| Mac with an Apple chip (M1 or newer), macOS 13 or newer | [SunTec-Floor-Plan-Maker-mac-apple-silicon.dmg](https://github.com/neeraj-bh/floor-plan-maker/releases/latest/download/SunTec-Floor-Plan-Maker-mac-apple-silicon.dmg) |
| Windows 10 or 11 | [SunTec-Floor-Plan-Maker-windows-setup.exe](https://github.com/neeraj-bh/floor-plan-maker/releases/latest/download/SunTec-Floor-Plan-Maker-windows-setup.exe) |

Macs with an Intel chip are not supported yet.

## Opening it the first time

The app isn't signed yet, so your computer asks once:

- **Mac:** open the `.dmg` and drag **SunTec Floor Plan Maker** into **Applications**, then open it. When macOS says it can't check the app, open **System Settings › Privacy & Security**, scroll down and click **Open Anyway**.
- **Windows:** open the setup. If "Windows protected your PC" appears, click **More info › Run anyway**. It installs for you only and needs no admin rights.

For DWG files, install the free [ODA File Converter](https://www.opendesign.com/guestfiles/oda_file_converter); the app finds it by itself.

After that it opens like any other app. It checks for new versions when it opens (and from Help › Check for Updates…) and updates itself. Your scans and projects never leave your computer.

Every release includes `checksums.txt` (SHA-256) for its files.
