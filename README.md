# apps-to-use-with-root-or-shizuku-android

> **⚠️ Disclaimer:** This repository is a collection of links and information about apps that can be used with **Shizuku** or **root** access on Android. The apps and repositories listed here are created and maintained by their respective developers. **The creators of any referenced app or repository, the creator of Shizuku, and the creator of this repository are not responsible for any damage, data loss, device issues, boot loops, or other problems that may result from using these apps or modifying your device.** Use root/Shizuku features carefully and make sure you understand what an app is doing before granting it elevated access.

## How this list is organized

The list is split into two main sections:

1. **Shizuku** — apps that can use Shizuku to access Android APIs and permissions that normally require ADB or elevated access.
2. **Root** — apps that require or can take advantage of traditional root access.

Apps may appear in more than one section when they support both Shizuku and root.

---

# Shizuku

## Apps

### App Management & Debloating
- **Canta** — debloat and uninstall system apps using Shizuku.
  - Repository: `samolego/Canta`
  - Shizuku: ✅
  - Root: ❌
- **Hail** — freeze, disable, and manage apps.
  - Repository: `aistra0528/Hail`
  - Shizuku: ✅
  - Root: ✅

### System Utilities
- **ShizuTools** — a collection of Android tools built around Shizuku.
  - Repository: `legendsayantan/ShizuTools`
  - Shizuku: ✅
  - Root: ❌
- **VolumeManager** — advanced volume-management utility.
  - Repository: `yume-chan/VolumeManager`
  - Shizuku: ✅
  - Root: ❌
- **Android-Screener** — Android system/device utility tooling.
  - Repository: `jiesou/Android-Screener`
  - Shizuku: ✅
  - Root: ❌

### Package Management & Installation
- **InstallerX-Revived** — advanced Android package installer.
  - Repository: `wxxsfxyzm/InstallerX-Revived`
  - Shizuku: ✅
  - Root: ❌

### Calling & System Features
- **ShizuCallRecorder** — call-recording utility built around Shizuku capabilities.
  - Repository: `kitsumed/ShizuCallRecorder`
  - Shizuku: ✅
  - Root: ❌

### Terminal & Advanced Tools
- **Termux Shizuku Tools** — tools for using Termux together with Shizuku.
  - Repository: `jecis-repos/termux-shizuku-tools`
  - Shizuku: ✅
  - Root: ❌

### Resources
- **awesome-shizuku** — curated collection of Shizuku-compatible apps and resources.
  - Repository: `timschneeb/awesome-shizuku`
  - Shizuku: ℹ️ Resource list
- **Shizuku API** — official API repository for developers building Shizuku-enabled apps.
  - Repository: `RikkaApps/Shizuku-API`
  - Shizuku: ℹ️ Developer resource

---

# Root

## Apps

### System Management & Modules
- **Magisk Module Manager** — manager for Magisk modules.
  - Repository: `Androidacy/MagiskModuleManager`
  - Root: ✅
- **SystemlessDebloater** — systemless debloating utility for rooted Android devices.
  - Repository: `zgfg/SystemlessDebloater`
  - Root: ✅
- **SystemlessDebloater (Magisk Modules Alt Repo)** — alternate repository for the SystemlessDebloater module.
  - Repository: `Magisk-Modules-Alt-Repo/SystemlessDebloater`
  - Root: ✅

### Privacy & App Management
- **Green2Priv** — root-oriented privacy and application-management tooling.
  - Repository: `K3V1991/Green2Priv`
  - Root: ✅

---

## App Entry Format

When adding an app, use this format:

### App Name
- **Type:** Shizuku / Root / Both
- **Category:** System & Device Management / Customization / Privacy & Security / Utilities / etc.
- **Description:** Short explanation of what the app does.
- **Repository:** `owner/repository`
- **Shizuku:** ✅ / ❌ / ℹ️
- **Root:** ✅ / ❌ / ℹ️
- **Notes:** Any important compatibility, Android-version, or permission information.

## Important

- Always check what permissions an app requests before granting Shizuku or root access.
- Root access can give an application extremely broad control over the device.
- Shizuku is generally less privileged than full root, but an app using Shizuku can still perform powerful operations.
- Compatibility can vary between Android versions, manufacturers, and ROMs.
- Prefer official project pages and repositories when downloading apps.
