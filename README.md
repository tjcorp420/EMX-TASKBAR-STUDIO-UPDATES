# EMX Taskbar Studio

Extract the complete portable ZIP into a permanent local folder and open **EMX.TaskbarStudio.exe**. Keep all runtime DLLs with it. Windows 10 version 2004 or newer, Windows x64; no separate .NET installation is required.

Use the **EMX taskbar ON / OFF** toggle in the footer on every page, or **Ctrl + Alt + L**, to switch between EMX and Windows. Change the on/off hotkey on Home or Behavior: one letter, digit or F1–F24, or a combination. A single key is reserved for EMX while the app is running. Conflicting bindings keep the previous key. Your on/off choice and binding persist on restart. On Home, **Auto-hide Windows taskbar while EMX Dock is running** also enables EMX. The Windows taskbar stays accessible through the dock's **⊞** button or **Ctrl + Alt + T** for eight seconds. Change the duration and binding in Behavior. Permanent Restore hides EMX until auto-hide is enabled again. Exit always restores Windows.

- Home: fourteen presets with different layouts and styles.
- Pins: all Windows pins, a chosen subset, or a library built from scratch. The installed-app picker supports Store apps such as SoundCloud without finding an EXE.
- Appearance: bar, floating islands, individual icon pills, split groups or rail; shape, color, opacity, borders, image, pattern and animated MP4 backgrounds. Choose **Choose animated MP4 background** to import a local video: muted looping playback behind the icons, paused while hidden. H.264 MP4 up to 256 MB and 4096 pixels per side; decoding depends on installed Windows codecs.
- Layout: choose screen edge/alignment, floating or screen-edge placement, maximum length, minimum bar thickness, padding and wheel/arrow navigation. Sizing controls include exact numeric entry. Partial edge tiles hide fully while scrolling reaches every app.
- Icons: thirteen surfaces including Circle, Diamond, Triangle, Hexagon, Octagon, Shield and Star, with editable idle visibility. Real artwork stays intact.
- Colors: owned EMX picker, RGB sliders and HEX/RGB input. Image/video color uses editable tint; gradient-end controls are disabled for materials that do not use them.
- Animations: magnify, lift, tilt, float, bounce, press, halo, fade or no motion, with editable strength, duration and easing.
- Audio: Windows master volume/mute and media playback, artwork and transport supported by the selected app/browser. Resize with the bottom-right grip or window border; drag the header. Size and position are remembered.
- Updates: click **Check for updates**, review the available version, then **Download & restart**. Downloads are verified before installation, replaced files are backed up, and startup is checked. Settings and pins stay in your user configuration folder.

SoundCloud and supported browsers expose playback through Windows media sessions. Missing timing or unsupported controls stay unavailable. This release does not provide native desktop blur, per-app volume or a replacement Windows system tray. Use ⊞ to access the Windows tray.

Settings are stored under `%LOCALAPPDATA%\EMX\TaskbarStudio`. Updating requires a writable, ordinary local installation folder and space for the staged runtime and backup; it never requests administrator privileges. Backups remain in the configuration's `updates` folder for recovery. Close EMX before manually restoring a previous portable release.

Download releases: https://github.com/tjcorp420/EMX-TASKBAR-STUDIO-UPDATES/releases
