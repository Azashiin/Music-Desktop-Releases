# Changelog

What is new and improved in Music Desktop.

## 2.0.5 — Lyrics, themes and Last.fm — October 11, 2026

### Lyrics on Remote

- Open the current track’s lyrics from **Lyrics** in the centre of Remote’s top bar. The button stays grey when lyrics are unavailable.
- YouTube Music lyrics are supplemented by LRCLIB. When timings exist, the current line is highlighted and scrolls with playback.
- Tap a line to seek, resume following after manual scrolling, and adjust a timing offset in 50 ms steps.
- The source stays visible: original sync in grey, estimated **Synced by MusicDesktop** timings in red.

### Automatic lyrics — EXPERIMENTAL

- An optional engine locally analyses a full listen when lyrics exist without timings. YouTube Music or LRCLIB timings keep priority.
- Download the engine separately with per-file byte, percentage and speed tracking; cancel, resume or remove it in settings.
- Browse analysed tracks in a dedicated window, try a result or delete it. Saved results are used for future listens.
- Status shows lyric lookup, received audio and processing stages. Fixed crashes when stopping analysis and handling vocal isolation.
- **This feature remains experimental** and OFF by default. Audio capture requires Windows 11; models take several GB, and processing uses CPU and memory. Accuracy varies by track; millisecond accuracy is not guaranteed. No audio is sent to a recognition service.

### Your queue and playlists

- Reorder upcoming tracks in Remote by dragging them or using move controls.
- Access playlists from the YouTube Music account connected on your PC: private creation by default, renaming, deletion and removing a song.
- Add the current track to a playlist from the player. Fixed confirmations and refreshes after creating playlists or adding tracks.

**The mobile features above require MusicDesktop Remote 1.0.5 or a compatible version.** Remote remains in Android closed testing; the PC installer does not include the mobile app. [Join the test](https://musicdesktop.net/en/remote.html).

### Last.fm

- Connect your account in **Settings → Last.fm**, authorise MusicDesktop in your browser, then enable recording.
- The current track appears on your profile. Tracks longer than 30 seconds are scrobbled after half their duration actually listened to, or four minutes for longer tracks.
- Sends run on the PC even with the phone closed. Pending listens are protected under Windows and resume when Last.fm is available again.
- Stop recording or disconnect at any time. No audio is sent to Last.fm.

### Themes and settings

- Three themes: **MusicDesktop**, **Akyraïs** (pure white and lavender) and **Asashiin** (deeper black and electric purple).
- Aligned navigation icons, revised wording and redesigned Streamer/Automatic lyrics settings.
- A prominent **EXPERIMENTAL** label at the top of Automatic lyrics settings.

### Updates and Streamer

- New in-app download tracking: file name, size, received bytes, percentage and speed.
- A downloaded update stays ready until you choose to restart. Its signature is checked before installation.
- Update notifications appear after the app has loaded.
- Streamer **ON/OFF** switch in the top bar. Streamer starts OFF each time, preserving your settings and OBS links.
- Existing overlays and Deckboard/Stream Deck extensions remain compatible.

Download **Music.Desktop_2.0.5_x64-setup.exe** for 64-bit Windows 10/11. Lyrics models are optional and downloaded separately. Preferences, Remote pairings and installed models are preserved during a normal update.

## 2.0.4 — MusicDesktop Remote compatibility fix — October 8, 2026

- Restored current-track information, artwork, progress and playback-state updates in Remote after 2.0.3.
- Message format compatible with the existing mobile application and relay.
- Existing pairings are preserved; install the update on the PC.

## 2.0.3 — Streamer Update — October 7, 2026

- Streamer Mode and OBS/Streamlabs overlays, with six layouts and six editable styles.
- New Studio: live preview, grouped settings, controls and guide in English and French.
- Customizable gradients, borders, artwork shape, typography and progress.
- Independent drafts before saving to OBS, with existing configuration compatibility.
- MusicDesktop Deckboard and Elgato Stream Deck extensions with live button states.
- New playback, volume, Mini Player and Streamer Mode shortcuts.
- Optional local service, with separate OBS display and extension control access.

## 2.0.2 — A more practical, optimized Mini Player — October 4, 2026

- Four Mini Player layouts: Classic, Square, Compact and Mini.
- Preview without a track playing, preset positions and remembered placement.
- Optimized animated artwork and progress, with updates stopped while content is hidden or retracted.
- Memory-saving mode activates when the main window is minimized, while playback continues.
- Optimized playback tracking with responsive track changes and controls.

## 2.0.1 — More controls for MusicDesktop Remote — October 3, 2026

- Remote’s For You tab shows recommendations from the YouTube Music session open on the PC.
- Turn repeat-one and shuffle on or off from your phone to control playback on the PC.
- The installer asks before closing MusicDesktop if it is still open during an update.

## 2.0.0 — A refreshed MusicDesktop — September 30, 2026

- A new MusicDesktop interface keeps YouTube Music in a separate view. Settings and controls remain available while it loads.
- The startup screen shows the connection state and lets you retry if YouTube Music is temporarily unavailable.
- Pair MusicDesktop Remote with your PC using a QR code or temporary code, then approve the phone in MusicDesktop.
- From a paired phone, control playback, search for tracks and browse the queue of the YouTube Music session open on your PC.
- YouTube Music remains the only available music platform in this version; SoundCloud and Bandcamp are planned for later.

## 1.2.9 — Easier every day — September 25, 2026

- Music Desktop can start with Windows, opening its window or staying in the background.
- Choose whether the app closes or keeps running when you close its window.
- Shortcuts work even when you are using another app.
- The mini player remembers where you placed it and whether “Always on top” is on.
- If Music Desktop is already open, launching it again shows its window instead of opening a second one.
- Music Desktop now appears in the Start menu.
- The YouTube Music scrollbar is no longer visible.

## 1.2.8 — Settings stay where they belong — September 22, 2026

- Fixed an issue that kept the Settings window always on top for no reason.
- You can now choose the app shortcuts.

## 1.2.7 — Settings that feel simpler — September 22, 2026

This update makes the small everyday things feel more natural: your settings, mini player, and updates are right where you expect them.

- Settings have been redesigned with a clearer, better-organized interface, so every option is easier to find.
- The mini player is always one click away from the top bar.
- You can check for a new version, install it, and see what changed in one place.
- Your Discord activity stays personal: views and likes are hidden by default, but you can choose to show them.
- Even in a small window, settings stay easy to browse with discreet scrolling.

## 1.2.6 — Language Update — September 21, 2026

Music Desktop is now available in French and English.

- Choose the language you prefer in Settings.
- After restarting, menus, the mini player, notifications, and settings use your selected language.
- Choose Music Desktop’s language during installation, then change it whenever you like from Settings.

## 1.2.5 — A more lively mini player — September 21, 2026

This update makes the mini player more pleasant to use every day, with a more immersive presentation and more reliable controls.

> If you are already using version 1.2.4, download and install this version once from GitHub. Future updates will then install automatically.

- A new visual atmosphere: track artwork now animates the mini player background and follows track changes.
- Clearer playback: controls have been refined, volume is available in one gesture, and returning to the main window is easier.
- Finally reliable progress: displayed time, the progress bar, and volume follow what is actually happening in YouTube Music more closely, even between tracks.
- More personal Discord activity: when enabled, the artwork for the track you are listening to can appear in your activity.
- A more discreet update notification that fits better inside the application.

## 1.2.4 — Built-in updates — September 21, 2026

- Check for new versions directly from the application settings.
- Download, progress, and installation after your confirmation.
- Every update package is verified with a cryptographic signature before it is installed.

## 1.2.3 — September 20, 2026

- Added an option, off by default, to remove all local data during uninstallation.
- Repair now checks essential files and restores only those that are missing or damaged.

## 1.2.2 — September 20, 2026

- New end-of-installation screen with useful options selected by default: launch the app, create a desktop shortcut, and add Music Desktop to the taskbar.

## 1.2.1 — September 20, 2026

- Added Akyraïs Studio’s visual identity to the installer.

## 1.2.0 — September 20, 2026

- Installation for every user of the computer, with a Windows permission prompt.
- Existing installations are detected, with update, maintenance, and uninstall options.
- Added the Music Desktop logo to the application, installer, and Windows shortcuts.

## 1.1.0 — September 20, 2026

- Visual refresh of the installer for a clearer, more polished presentation.
- High-definition welcome illustration.

## 1.0.0 — September 20, 2026

- First public release of Music Desktop.
- Dedicated Windows window for YouTube Music.
- Always-accessible mini player, notification area, and optional Discord Rich Presence.
