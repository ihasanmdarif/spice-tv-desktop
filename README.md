# Spice TV for your computer

Watch Spice TV on Mac, Windows or Linux. Video plays straight to your
computer, so you get a smoother picture with less buffering than in the
browser.

Sign in with your usual Spice TV username and password.

## Download

Get the newest version from the **[Releases page](../../releases/latest)**:

| Computer | File |
|---|---|
| Mac with Apple chip (M1 or newer) | [spice-tv-mac-arm64.dmg](../../releases/latest/download/spice-tv-mac-arm64.dmg) |
| Mac with Intel chip | [spice-tv-mac-x64.dmg](../../releases/latest/download/spice-tv-mac-x64.dmg) |
| Windows 10 / 11 | [spice-tv-win-x64.exe](../../releases/latest/download/spice-tv-win-x64.exe) |
| Linux | [spice-tv-linux-x86_64.AppImage](../../releases/latest/download/spice-tv-linux-x86_64.AppImage) |

Not sure which Mac you have? Apple menu → **About This Mac**. "Chip: Apple M…"
means Apple chip; "Processor: Intel" means Intel.

## Installing

The app is not yet signed with Apple or Microsoft, so your computer asks
you to confirm the first time you open it. This is expected.

### Mac

1. Open the `.dmg` and drag **Spice TV** into **Applications**.
2. Open Spice TV from Applications. macOS says it cannot check the app. Click **Done**.
3. Open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to Spice TV.
4. Confirm with your password. From then on it opens normally.

### Windows

1. Run `spice-tv-win-x64.exe`.
2. If you see "Windows protected your PC", click **More info**, then **Run anyway**.
3. Spice TV installs and opens. It appears in the Start menu.

### Linux

1. Make the file runnable: `chmod +x spice-tv-linux-x86_64.AppImage`
2. Run it: `./spice-tv-linux-x86_64.AppImage`

## Updating

**Windows and Linux** update themselves: when a new version is out, it
downloads in the background, you get a notification, and it installs the
next time you close the app. (Version 0.1.0 does not do this yet; install
0.1.1 or newer by hand once.)

**Mac** does not update itself yet. When a new version is posted here,
download it and drag it into Applications over the old one.
