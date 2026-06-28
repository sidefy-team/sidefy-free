# Sidefy Trial

Official download and update feed for **Sidefy Trial** — the free edition of Sidefy for macOS.

This repository hosts release artifacts (ZIP, DMG) and the Sparkle appcast. It is **not** the application source code.

https://github.com/user-attachments/assets/2678f9c7-f6d9-46bc-a7bf-6a18ae06054e

## Download

Get the latest build from [GitHub Releases](https://github.com/sidefy-team/sidefy-trial/releases).

Requirements: **macOS 14.0 or later**.

## Updates

Sidefy Trial checks for updates automatically via Sparkle.

- Feed URL: `https://raw.githubusercontent.com/sidefy-team/sidefy-trial/main/release/trial-static/appcast.xml`

## Trial vs full version

Sidefy Trial is a feature-limited edition. The full version is available on the Mac App Store.

| Feature | Trial | Full (App Store) |
|--------|-------|------------------|
| Rules | Up to 5; SideScript import & export not available | Unlimited; available |
| Rule templates | Not available | Available |
| RSS feeds | Up to 5; OPML import & export not available | Unlimited; available |
| GitHub repos | Up to 5 | Unlimited |
| Custom / online plugins | Up to 5 combined (built-in plugins excluded) | Unlimited |
| Advanced settings | Not available | Available |
| AI translation | Not available | Available |
| SideScript advanced editing | Not available | Available (requires experimental features) |
| MCP / local server | Not available | Available (requires experimental features) |
| iCloud sync | Not available | Available |
| Experimental features | Not available | Available |
| Updates | Sparkle (GitHub distribution) | App Store updates |

## Repository contents

| Path | Purpose |
|------|---------|
| `release/trial-static/appcast.xml` | Sparkle update metadata |
| GitHub Releases | Signed, notarized ZIP and DMG builds |

Release packages are built from the private Sidefy source repository and published here for distribution only.

## License and user terms

**Sidefy is proprietary software.** Copyright © 2025–2026 ØYNN. All rights reserved.

There is **no open-source license** for the application, its source code, or release binaries in this repository. Do not treat this repo as granting rights to copy, modify, redistribute, or sublicense the software beyond what ØYNN expressly allows.

### Sidefy Trial (this repository)

Use of Sidefy Trial downloaded from GitHub is governed by **ØYNN’s proprietary end-user terms**: you may install and run the official trial build and receive updates through the Sparkle feed provided here. Redistribution, repackaging, or commercial use of trial builds without permission is not allowed.

### Sidefy full version (Mac App Store)

The full version purchased on the Mac App Store is licensed under:

1. **Apple’s Licensed Application End User License Agreement** (Standard EULA or any custom EULA published on the App Store for Sidefy), and  
2. **ØYNN’s proprietary rights** as the copyright holder (© ØYNN).

Apple’s EULA governs your App Store purchase and use of the full app; it does not open-source Sidefy or grant rights to the source code.

### Third-party components

Libraries and assets bundled inside the app remain subject to their respective third-party licenses. See **About → Third-Party Dependencies** in the app.

## Support

For bugs and feedback about Sidefy Trial, open an issue in this repository.

For the full App Store product, use App Store support channels or the developer’s official contact methods.

---

**Sidefy** and **Sidefy Trial** are products of ØYNN. This repository is for official trial distribution only.
