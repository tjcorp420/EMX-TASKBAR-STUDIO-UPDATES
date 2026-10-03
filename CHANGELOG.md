# Changes

## 0.1.6
- Make the EMX on/off toggle respond to accessibility TogglePattern as well as mouse and keyboard changes. Synchronization after hotkeys or native recovery cannot recursively change taskbar state.


## 0.1.5
- Persistent EMX on/off footer toggle and global rebindable shortcut (default Ctrl + Alt + L), including single letters, digits and F1–F24. Windows/EMX handoff and preferences persist.
- Local MP4 backgrounds: muted native playback, looping, opacity, pause while hidden, decoder cleanup and recoverable solid-color fallback.
- Fix the real updater restart handoff: distinguish mutex ownership from an existing named handle, and close the helper lock before restarting.
- A published-release update test caught the 0.1.4 restart refusal; its startup check restored the previous version. 0.1.5 adds a regression for retained helper handles.

## 0.1.4
- Five actual dock designs, fourteen distinct presets, six surface shapes, seven icon shapes and nine background materials including image/pattern controls.
- Nine finite hover effects with configurable easing, movement, tilt, opacity, scale and duration. Floating gaps are transparent to input; recovery controls remain fixed.
- Permanent Restore suspends EMX; normal Windows and custom docks hand off during timed reveal. Screen-edge placement removes the outer gap.
- Resizable audio panel with persistent position/size, readable source names and honest no-timing/waiting states.
- GitHub in-app check/download/restart updater, checksum and package/version validation, file backup/rollback and startup acknowledgment. Private source and public compiled updates are separate.

- Installed Windows app picker with search and shell icons, so Store apps such as SoundCloud – Music & Audio can be pinned without finding an EXE.
- Strict AppsFolder target validation, installed-app registration check on launch and persistent/exportable native app identities.
- Native window AppUserModelID, packaged process identity and classic UWP core-child identity match running windows to their pins.
- Real SoundCloud launch and running-pin integration verified with no additional onscreen dock or taskbar visibility change.
- Startup --pin-app option adds an installed app through the same validated pin path; a running engine must use the picker.

## 0.1.2
- Readable dark dropdowns, selected/hovered items, sliders and scrollbars.
- Horizontal wheel scrolling and configurable wheel/arrows navigation; recovery controls outside overflow and bounded dock length.
- Reserved room for complete hover animations, circular/square/rounded/custom icon surfaces and LIVE/MIN/OPEN badges.
- Eight distinct presets with layout descriptions, preserving pin source/selection/order/icon overrides.
- Home auto-hide guidance and a remembered opt-in backed by the taskbar guardian, timed reveal and permanent restore.
- Maximized editor insets keep live dock overlays clear of editor controls.
- EMX Audio popout with real Windows master volume/mute and media-session source selection, metadata/artwork, transport, timeline/seek/shuffle/repeat where supported.
- Microsoft Windows SDK .NET projection via the Windows 10 2004 target; minimum supported OS is Windows 10 version 2004.
- Offscreen renderer/input regressions and a muted native media fixture. Running-app restore/minimize behavior is preserved.

## 0.1.1
- Three pin sources: all Windows taskbar shortcuts, user-selected Windows pins, or a custom library from scratch, with independent running-app visibility and original shell icons.
- Windows pin folder change notifications, durable selection/order, and icon overrides without modifying native pins.
- Fixed a two-step dock position update that briefly moved the window to the screen origin.
- Stable running-app order when foreground/z-order changes.
- One production engine across copies and different configuration directories.
- Rebindable timed native-taskbar reveal (default Ctrl+Alt+T, eight seconds, configurable 1–120 seconds), countdown restart and cancel on permanent restore.
- Dedicated reveal/restore/Studio controls outside the scrolling app list.
- Default verification runs offscreen. Interactive fixture/window/taskbar tests require an explicit test-session flag; safety probes no longer render another dock.
- Corrected the editor background and fixed recovery behavior for a canceled session-end query.

## 0.1.0 foundation
Separate native WPF product, real Windows event tracking and actions, pins, icons, four-edge dock, live customization, presets/profiles/themes and independent taskbar guardian. No Desktop Flow source edits.


- Always-visible EMX taskbar ON/OFF toggle and separately rebindable global shortcut, default Ctrl + Alt + L; single-key letter/digit/function-key bindings are supported, conflicts preserve the previous binding, and state persists across restart.
