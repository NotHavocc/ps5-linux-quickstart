# PS5 Linux QuickStart

A setup wizard for Linux on the PlayStation 5 (Ubuntu / Debian based).

## Install

Open a terminal on the PS5 desktop and run:

```sh
curl -fsSL https://nothavoc.is-a.dev/ps5quickstart.sh | bash
```

Run it as your normal user, not with `sudo`. The wizard asks for your password when it needs it.

Run the same command again later to update to the newest version.

## What it does

Pick what you want in the window and press **Run Setup**.

**Essential**
- **Kernel patching:** builds and installs the patched PS5 kernel.
- **Steam and gamescope:** installs both.
- **DualSense over Bluetooth:** sets up the controller for Steam.
- **Steam autostart:** starts Steam when you log in.
- **Steam Deck UI:** launches Steam's Deck interface, optionally in gamescope.
- **Gaming Mode:** a Steam Deck-style session, with *Switch to Desktop*.

**Miscellaneous**
- **Live wallpaper:** a video wallpaper on the Ubuntu desktop (built-in or your own).

**Experimental**
- **MediaTek WiFi driver:** unstable, off by default.

**Fan/LED Control**
- Change the fan's target temperature.
- Pick a light bar preset.
- Test the buzzer.

## Uses

- [rmuxnet/ps5-linux-patches-1](https://github.com/rmuxnet/ps5-linux-patches-1): PS5 kernel patches and build script (a fork of [ps5-linux/ps5-linux-patches](https://github.com/ps5-linux/ps5-linux-patches)).
- [airkingbr/ps5-mt7921-wifi](https://github.com/airkingbr/ps5-mt7921-wifi): MediaTek MT7921 WiFi driver build.
- [jeffshee/gnome-ext-hanabi](https://github.com/jeffshee/gnome-ext-hanabi): live wallpaper extension for GNOME.
- [ValveSoftware/gamescope](https://github.com/ValveSoftware/gamescope): the compositor behind the Deck UI and Gaming Mode.
- [ChimeraOS/gamescope-session-steam](https://github.com/ChimeraOS/gamescope-session-steam): what the Gaming Mode session is modelled on.
- [PS5 Linux Guide](https://rmuxnet.gitlab.io/ps5-linux-guide/): DualSense Bluetooth notes.
