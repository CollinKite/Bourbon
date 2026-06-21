<div align="center">

  # Bourbon 🥃 
  *Whisky, carried on*
  
  ![](https://img.shields.io/github/actions/workflow/status/CollinKite/Bourbon/SwiftLint.yml?style=for-the-badge)
</div>

## About

Bourbon is a community-maintained fork of [Whisky](https://github.com/Whisky-App/Whisky), the modern Wine wrapper for macOS. The original project is [no longer actively maintained](https://docs.getwhisky.app/maintenance-notice), so Bourbon picks up where it left off — same smooth pour, new bartender.

> **Note:** Bourbon is early in its life as a fork. Apps and games may break, and some infrastructure (Wine builds, auto-update) still needs to be migrated off the original Whisky servers. See [Migration notes](#migration-notes).

<img width="650" alt="Config" src="https://github.com/Whisky-App/Whisky/assets/42140194/d0a405e8-76ee-48f0-92b5-165d184a576b">

Familiar UI that integrates seamlessly with macOS

<div align="right">
  <img width="650" alt="New Bottle" src="https://github.com/Whisky-App/Whisky/assets/42140194/ed1a0d69-d8fb-442b-9330-6816ba8981ba">

  One-click bottle creation and management
</div>

<img width="650" alt="debug" src="https://user-images.githubusercontent.com/42140194/229176642-57b80801-d29b-4123-b1c2-f3b31408ffc6.png">

Debug and profile with ease

---

Bourbon provides a clean and easy to use graphical wrapper for Wine built in native SwiftUI. You can make and manage bottles, install and run Windows apps and games, and unlock the full potential of your Mac with no technical knowledge required. Bourbon is built on top of CrossOver 22.1.1, and Apple's own `Game Porting Toolkit`.

Translated on [Crowdin](https://crowdin.com/project/whisky).

---

## System Requirements
- CPU: Apple Silicon (M-series chips)
- OS: macOS Sonoma 14.0 or later

## Building

Bourbon is built using Xcode 15 on macOS Sonoma. All external dependencies are handled through the Swift Package Manager. Clone the repo and open `Whisky.xcodeproj` to get started.

## My game isn't working!

Some games need special steps to get working. Bourbon inherits Whisky's behaviour, so the original [Game Support wiki](https://github.com/IsaacMarovitz/Whisky/wiki/Game-Support) is still a good reference.

---

## Migration notes

As the new maintainer, these still point at the original Whisky infrastructure and need to be repointed to your own before they can be relied on:

- `https://data.getwhisky.app/Wine/...` — WhiskyWine builds & libraries download
- `https://data.getwhisky.app/appcast.xml` — Sparkle auto-update feed
- `https://getwhisky.app/` — project website link in-app
- `https://discord.gg/CsqAfs9CnM` — community Discord
- Homebrew cask (`whisky`) — not yet published for Bourbon

---

## Credits & Acknowledgments

Bourbon stands on the shoulders of [Whisky](https://github.com/Whisky-App/Whisky) by Isaac Marovitz and contributors, and the magic of several projects:

- [msync](https://github.com/marzent/wine-msync) by marzent
- [DXVK-macOS](https://github.com/Gcenx/DXVK-macOS) by Gcenx and doitsujin
- [MoltenVK](https://github.com/KhronosGroup/MoltenVK) by KhronosGroup
- [Sparkle](https://github.com/sparkle-project/Sparkle) by sparkle-project
- [SemanticVersion](https://github.com/SwiftPackageIndex/SemanticVersion) by SwiftPackageIndex
- [swift-argument-parser](https://github.com/apple/swift-argument-parser) by Apple
- [SwiftTextTable](https://github.com/scottrhoyt/SwiftyTextTable) by scottrhoyt
- [CrossOver 22.1.1](https://www.codeweavers.com/crossover) by CodeWeavers and WineHQ
- D3DMetal by Apple

Special thanks to Isaac Marovitz, Gcenx, ohaiibuzzle, and Nat Brown for the original Whisky and their support and contributions!

---

<table>
  <tr>
    <td>
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="./images/cw-dark.png">
          <img src="./images/cw-light.png" width="500">
        </picture>
    </td>
    <td>
        Bourbon doesn't exist without CrossOver. Support the work of CodeWeavers using our <a href="https://www.codeweavers.com/store?ad=1010">affiliate link</a>.
    </td>
  </tr>
</table>
