# Parley

Discord, light. A small native Discord client for Windows 10 and 11, by PG.

**[Download the latest release](https://github.com/lilpatter/parley/releases/latest)**: `Parley_<version>_x64-setup.exe` installs it, `parley.exe` runs without installing.

More at [lilpatter.github.io/parley](https://lilpatter.github.io/parley/).

<p align="center"><img src="logo.png" width="128" alt="Parley's icon: the Discord mascot with wings, flying, on a dark tile." /></p>

## What it does

- **Servers, channels and DMs.** Read and send messages, replies, emoji, slash commands, attachments and invite cards.
- **Voice calls.** Voice channels and DM calls with Discord's own end-to-end encryption, noise suppression, per-person volume and global mute and deafen shortcuts.
- **Stays signed in.** Restart your PC and Parley is still signed in, even when it starts before your network is up.
- **QR sign-in.** Scan the code with the Discord app on your phone (Settings › Scan QR Code). The code refreshes itself, and if Discord asks for a captcha, Parley shows it so you can finish signing in.
- **Several accounts.** Save more than one and switch between them from the account menu.
- **Light.** One small exe: no Electron, no browser engine. It idles in the tray with almost no memory and no CPU.
- **Private.** Your session is encrypted with Windows' own data protection and never leaves your PC except to talk to Discord.

## Good to know

- Using a third-party client with your Discord account is against Discord's Terms of Service. Parley talks to Discord the way the web client does, but use it knowing that.
- Screen sharing and video aren't supported.

## Requirements

Windows 10 or 11. The captcha window uses the WebView2 runtime, which ships with Windows 11.

## Updates

Parley updates itself from this page's releases and checks each download against GitHub's SHA-256 digest. It asks before installing an update, and you can check by hand under Settings › About.

## Credits

Made by [PG](https://lilpatter.github.io). Based on [Litecord](https://github.com/Ak4ai/Litecord) by the Litecord Project, used under the MIT License (see [NOTICE](NOTICE)).

Not affiliated with Discord.

---

© 2026 PG. All rights reserved. Parley is free to download and use. Its source code is not public.
