# Sidefy Free Edition

Official download and update feed for the **free edition** of [Sidefy](https://apps.apple.com/app/id6751482006) for macOS — feature-limited, not time-limited.

This repository hosts release artifacts (ZIP, DMG) and the Sparkle appcast. It is **not** the application source code.

https://github.com/user-attachments/assets/2678f9c7-f6d9-46bc-a7bf-6a18ae06054e

## Download

Get the latest build from [GitHub Releases](https://github.com/sidefy-team/sidefy-free/releases).

Requirements: **macOS 14.0 or later**.

## Updates

The free edition checks for updates automatically via Sparkle.

- Feed URL: `https://raw.githubusercontent.com/sidefy-team/sidefy-free/main/release/free-static/appcast.xml`

## Free edition vs full version

The free edition is feature-limited. The full version is available on the [Mac App Store](https://apps.apple.com/app/id6751482006).

| Feature | Free | Full (App Store) |
|--------|------|------------------|
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
| `release/free-static/appcast.xml` | Sparkle update metadata |
| GitHub Releases | Signed, notarized ZIP and DMG builds |

Release packages are built from the private Sidefy source repository and published here for distribution only.

## License and user terms

**Sidefy is proprietary software.** Copyright © 2025–2026 ØYNN. All rights reserved.

There is **no open-source license** for the application, its source code, or release binaries in this repository. Do not treat this repo as granting rights to copy, modify, redistribute, or sublicense the software beyond what ØYNN expressly allows.

### Free edition (this repository)

Use of the free edition downloaded from GitHub is governed by **ØYNN’s proprietary end-user terms**: you may install and run the official free build and receive updates through the Sparkle feed provided here. Redistribution, repackaging, or commercial use of free-edition builds without permission is not allowed.

### Sidefy full version (Mac App Store)

The full version purchased on the Mac App Store is licensed under:

1. **Apple’s Licensed Application End User License Agreement** (Standard EULA or any custom EULA published on the App Store for Sidefy), and  
2. **ØYNN’s proprietary rights** as the copyright holder (© ØYNN).

Apple’s EULA governs your App Store purchase and use of the full app; it does not open-source Sidefy or grant rights to the source code.

### Third-party components

Libraries and assets bundled inside the app remain subject to their respective third-party licenses. See **About → Third-Party Dependencies** in the app.

## Support

For bugs and feedback about the free edition, open an issue in this repository.

For the full App Store product, use App Store support channels or the developer’s official contact methods.

---

**Sidefy** is a product of ØYNN. This repository is for official free-edition distribution only.
