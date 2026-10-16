# Yap: private voice dictation for Mac, Windows and Android

Hold a shortcut, speak, and let go. Yap turns your speech into clean, punctuated text and types it into the app you are using: email, documents, chat, browsers, terminals and coding agents. Speech recognition runs on your own device, so your recordings are not uploaded.

**[Download Yap](https://yapapp.cc/download?utm_source=github&utm_medium=readme&utm_campaign=github-readme-oct2026)** · [Website](https://yapapp.cc/?utm_source=github&utm_medium=readme&utm_campaign=github-readme-oct2026) · [Pricing](https://yapapp.cc/pricing?utm_source=github&utm_medium=readme&utm_campaign=github-readme-oct2026) · [Support](https://yapapp.cc/support?utm_source=github&utm_medium=readme&utm_campaign=github-readme-oct2026)

![Yap dictating into an app on a Mac](press/yap-mac-dictate-anywhere.png)

This repository hosts the Windows and Android installers of each release, plus press images. Yap is a commercial app, not open source.

## Download

| Device | Requirements | Get it |
|---|---|---|
| Mac | Apple silicon (M1 or later), macOS 13 or later | [Download for Mac](https://yapapp.cc/download?utm_source=github&utm_medium=readme&utm_campaign=github-readme-oct2026) (Developer ID signed and Apple notarized) |
| Windows | Windows 10 or 11, 64-bit (x64) | [Latest installer](https://yapapp.cc/api/desktop/download?platform=windows) |
| Windows on Arm | Windows 11 on Snapdragon and other Arm64 PCs, native build | [Latest Arm64 installer](https://yapapp.cc/api/desktop/download?platform=windows&arch=arm64) |
| Android | Android 10 or later | [Latest APK](https://yapapp.cc/api/desktop/download?platform=android) |
| iPhone | iOS 17 or later | [Public beta on TestFlight](https://testflight.apple.com/join/uc2u5VXe) |

Each link always points to the newest verified release. Older installers are attached to the [releases](https://github.com/founden-bot/yap-releases/releases), with SHA-256 checksums in each release's notes. Setup steps for every device: [yapapp.cc/download](https://yapapp.cc/download?utm_source=github&utm_medium=readme&utm_campaign=github-readme-oct2026).

## How it works

- **Mac:** hold Fn, speak, release. Press Fn + Space to keep recording hands-free, then tap Fn to finish.
- **Windows:** hold Ctrl + Win, speak, release. Press Space while holding to keep recording hands-free.
- **Phone:** the Yap keyboard puts the same dictation in every app.
- Yap adds punctuation and capitals and removes filler words such as "um" and "uh".
- It types where your cursor is, including terminals and coding agents such as Claude Code. It never types into password fields.
- Press Esc to stop a recording and keep it in History instead of typing it.

![Yap's dictation history on a Mac](press/yap-mac-history.png)

## Private by design

- Speech recognition runs on your device (NVIDIA Parakeet). Your audio is never uploaded.
- After a one-time download of the speech model (about 0.7 GB on Windows and Android, 1.4 GB on a Mac), dictation works offline.
- Your dictation history stays on your device, where you can search, copy or delete it.

## Languages

25 European languages, detected from each recording with no setting to change: Bulgarian, Croatian, Czech, Danish, Dutch, English, Estonian, Finnish, French, German, Greek, Hungarian, Italian, Latvian, Lithuanian, Maltese, Polish, Portuguese, Romanian, Russian, Slovak, Slovenian, Spanish, Swedish and Ukrainian.

## Pricing

- **3 free days** from the first time you open the app, with no account and no card.
- Then a **10-day trial** with a card.
- Then **USD 6.90 a month or USD 69 a year**. One subscription covers your Mac, your Windows PCs and your phone. Cancel anytime.

## Questions

**Is Yap open source?** No. Yap is a paid app made by O-mega Enterprise, Inc. This repository only hosts installers and images.

**Is there an Intel Mac or Linux version?** No. Yap runs on Apple silicon Macs, Windows 10 and 11 (x64 and Arm64), Android, and iPhone (beta).

**Why does Windows say "Windows protected your PC"?** The Windows installer is not code-signed yet. Choose More info, then Run anyway. It installs for your account only, with no administrator rights, and keeps itself up to date with signed updates.

**Where do I get help?** [yapapp.cc/support](https://yapapp.cc/support?utm_source=github&utm_medium=readme&utm_campaign=github-readme-oct2026). Please do not open issues here for support.
