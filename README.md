# EMX Taskbar Studio

Extract the complete portable ZIP into a permanent local folder and open **EMX.TaskbarStudio.exe**. Keep all runtime DLLs with it. Windows 10 version 2004 or newer, Windows x64; no separate .NET installation is required.

Use the **EMX taskbar ON / OFF** toggle in the footer on every page, or **Ctrl + Alt + L**, to switch between EMX and Windows. Change the on/off hotkey on Home or Behavior: one letter, digit or F1–F24, or a combination. A single key is reserved for EMX while the app is running. Conflicting bindings keep the previous key. Your on/off choice and binding persist on restart. On Home, **Auto-hide Windows taskbar while EMX Dock is running** also enables EMX. The Windows taskbar stays accessible through the dock's **⊞** button or **Ctrl + Alt + T** for eight seconds. Change the duration and binding in Behavior. Permanent Restore hides EMX until auto-hide is enabled again. Exit always restores Windows.

- Home: fourteen presets with different layouts and styles.
- Pins: all Windows pins, a chosen subset, or a library built from scratch. The installed-app picker supports Store apps such as SoundCloud without finding an EXE.
- Appearance: bar, floating islands, individual icon pills, split groups or rail; shape, color, opacity, borders, image, pattern and animated MP4 backgrounds. Choose **Choose animated MP4 background** to import a local video: muted looping playback behind the icons, paused while hidden. H.264 MP4 up to 256 MB and 4096 pixels per side; decoding depends on installed Windows codecs.
- Layout: choose screen edge/alignment, floating or screen-edge placement, maximum length, minimum bar thickness, padding and wheel/arrow navigation. Sizing controls include exact numeric entry. Partial edge tiles hide fully while scrolling reaches every app.
- Icons: shared PNG/JPEG or silent MP4 icon backgrounds with their own opacity, centered original artwork, and thirteen surfaces including Circle, Diamond, Triangle, Hexagon, Octagon, Shield and Star, with editable idle visibility. Real artwork stays intact.
- Colors: owned EMX picker, RGB sliders and HEX/RGB input. Image/video color uses editable tint; gradient-end controls are disabled for materials that do not use them.
- Animations: magnify, lift, tilt, float, bounce, press, halo, fade or no motion, with editable strength, duration and easing.
- Audio: independent app/browser volume and mute, Windows master volume/mute and media playback, artwork and transport supported by the selected app/browser. Resize with the bottom-right grip or window border; drag the header. Size and position are remembered.
- Updates: click **Check for updates**, review the available version, then **Download & restart**. Downloads are verified before installation, replaced files are backed up, and startup is checked. Settings and pins stay in your user configuration folder.

SoundCloud and supported browsers expose playback through Windows media sessions. Missing timing or unsupported controls stay unavailable. This release does not provide native desktop blur or a replacement Windows system tray. Use ⊞ to access the Windows tray.

Settings are stored under `%LOCALAPPDATA%\EMX\TaskbarStudio`. Updating requires a writable, ordinary local installation folder and space for the staged runtime and backup; it never requests administrator privileges. Backups remain in the configuration's `updates` folder for recovery. Close EMX before manually restoring a previous portable release.

Download releases: https://github.com/tjcorp420/EMX-TASKBAR-STUDIO-UPDATES/releases

Behavior → Auto-hide EMX taskbar: hover over the selected screen edge to reveal it. Choose Slide, Fade, Zoom or None and adjust leave/hover delays. Reveal follows transition duration and easing in Animations. Recovery hotkeys and tray access remain available while hidden; Windows temporary reveal takes priority. This opt-in is off by default.

Layout → Position along edge (%) uses the available travel, with zero at center. Center taskbar on this edge clears offsets. Alignment clears the offset on its axis. A dock almost as wide as the screen has little travel: reduce maximum length. Cross-edge offset and edge-distance changes switch to Floating.

Animations → Repeat hover motion while pointed keeps the selected effect cycling until pointer exit. Edit Hover cycle duration for speed; disable Repeat for a finite transition. Zero transition duration disables motion.

Pin local Epic Games and Steam game shortcuts (.url), including Fortnite and Keep Digging, as well as standard .lnk shortcuts. Game launch actions are validated when pinned and clicked. Browser links, scripts and unrelated protocols are rejected.

App & browser volume in EMX Audio changes an app independently of Windows master level. Apps appear after creating an audio session; browser tabs may share one browser level. A YouTube tab may therefore change along with other audio tabs. Exclusive streams can be unavailable.

EMX Audio keeps its drag header and Close button fixed while the body scrolls, including at the minimum panel height. App sliders are explicitly labeled Windows mixer. SoundCloud may expose its own player percentage in its accessible volume button; EMX reads that separately when available. That percentage is read-only: the installed SoundCloud player does not expose a working slider control API. Change its internal level in SoundCloud; EMX independently controls its Windows mixer level.

Profiles: select an existing profile and Load & edit. Change settings on any page, then return and Save changes. Rename and Delete operate on the selected profile; deletion asks for confirmation and leaves the live taskbar settings intact. Create from current and Duplicate require a new name and never overwrite an existing profile.
