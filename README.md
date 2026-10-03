# EMX Taskbar Studio

Extract the complete portable ZIP into a permanent local folder and open **EMX.TaskbarStudio.exe**. Keep all runtime DLLs with it. Windows 10 version 2004 or newer, Windows x64; no separate .NET installation is required.

On Home, enable **Auto-hide Windows taskbar while EMX Dock is running** to use EMX. The Windows taskbar stays accessible through the dock's **⊞** button or **Ctrl + Alt + T** for eight seconds. Change the duration and binding in Behavior. Permanent Restore hides EMX until auto-hide is enabled again. Exit always restores Windows.

- Home: fourteen presets with different layouts and styles.
- Pins: all Windows pins, a chosen subset, or a library built from scratch. The installed-app picker supports Store apps such as SoundCloud without finding an EXE.
- Appearance: bar, floating islands, individual icon pills, split groups or rail; shape, color, opacity, borders, image and pattern backgrounds.
- Layout: choose screen edge/alignment, floating or screen-edge placement, dimensions and wheel/arrow navigation.
- Animations: magnify, lift, tilt, float, bounce, press, halo, fade or no motion, with editable strength, duration and easing.
- Audio: Windows master volume/mute and media playback, artwork and transport supported by the selected app/browser. Resize with the bottom-right grip or window border; drag the header. Size and position are remembered.
- Updates: click **Check for updates**, review the available version, then **Download & restart**. Downloads are verified before installation, replaced files are backed up, and startup is checked. Settings and pins stay in your user configuration folder.

SoundCloud and supported browsers expose playback through Windows media sessions. Missing timing or unsupported controls stay unavailable. This release does not provide native desktop blur, per-app volume or a replacement Windows system tray. Use ⊞ to access the Windows tray.

Settings are stored under `%LOCALAPPDATA%\EMX\TaskbarStudio`. Updating requires a writable, ordinary local installation folder and space for the staged runtime and backup; it never requests administrator privileges. Backups remain in the configuration's `updates` folder for recovery. Close EMX before manually restoring a previous portable release.

Download releases: https://github.com/tjcorp420/EMX-TASKBAR-STUDIO-UPDATES/releases
