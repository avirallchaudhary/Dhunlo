# DHUNLO

**DHUNLO** is a modern, cross-platform music streaming application featuring an elegant Liquid Glass user interface, background playback, playlist management, lyrics integration, and synchronized listening.

* **Current Android Version:** 1.0.2
* **Android Version Code:** `158`
* **Package Identifier:** `com.metrolist.music`
* **Platform:** Android (Release APK)

---

## Download & Installation

The official signed Android release package is hosted directly in this repository:

* **APK File:** [`DHUNLO-v1.0.2-release.apk`](DHUNLO-v1.0.2-release.apk)
* **Fallback Alias:** [`Dhunlo.apk`](Dhunlo.apk)
* **File Size:** ~15.08 MB (15,811,929 bytes)
* **APK SHA-256 Checksum:**
  ```text
  4935111D26CD8F682FD461DB85998B1BA6F8608F9B95CF02B823F4FAF9CDE977
  ```
* **Signing Certificate SHA-256:**
  ```text
  33b85da983e857e90511fffaeef596993d8ffaff1e62941cfb48412e7fd2bbaa
  ```

### Installation Steps

1. Download **[`DHUNLO-v1.0.2-release.apk`](DHUNLO-v1.0.2-release.apk)** to your Android device.
2. If prompted, allow your browser or file manager permission to install unknown apps (*Settings > Apps > Special app access > Install unknown apps*).
3. Open the downloaded `.apk` file and tap **Install** (or **Update**).
4. Launch **DHUNLO** from your home screen or app drawer.

*Note: In-place updates from previous DHUNLO releases preserve existing database records, downloaded music, playlists, and user settings.*

---

## What's New in v1.0.2

* **Playback & Stability Improvements:**
  * Fixed unexpected playback interruptions during screen-off audio playback.
  * Improved recovery after temporary network disconnections via automatic retry budgets.
  * Faster next-track transitions and preloading latency optimizations.
  * Faster audio-to-video mode switching with stream pre-resolution.
  * Fixed video-mode screen timeout behavior via `FLAG_KEEP_SCREEN_ON`.
  * Improved release UI scrolling responsiveness and artwork loading performance.

---

## Corresponding Source Code

In compliance with the **GNU General Public License v3.0** (GPL-3.0), the complete, verifiable corresponding source code snapshot for **DHUNLO v1.0.2** is published at:

* **Source Repository Tag:** [https://github.com/avirallchaudhary/Dhunlo-Source/tree/v1.0.2](https://github.com/avirallchaudhary/Dhunlo-Source/tree/v1.0.2)

This release tag contains the exact multiplatform source code, assets, and Gradle build configurations that produced the distributed APK.

### Source Documentation & Verification
* **[LICENSE](LICENSE):** Complete GNU General Public License v3.0 text.
* **[NOTICE.md](NOTICE.md):** Detailed legal notices, upstream attribution, and third-party permissive licenses.
* **[BUILDING.md](https://github.com/avirallchaudhary/Dhunlo-Source/blob/v1.0.2/BUILDING.md):** Complete build prerequisites, SDK/NDK requirements, and compilation instructions.
* **[PROVENANCE.md](https://github.com/avirallchaudhary/Dhunlo-Source/blob/v1.0.2/PROVENANCE.md):** Source-to-APK provenance audit record, commit mapping, and verification procedures.

---

## License & Upstream Attribution

DHUNLO is distributed under the **GNU General Public License v3.0** (GPL-3.0). See the [LICENSE](LICENSE) file for complete license terms.

* Based upon and derived from the open-source project [Metrolist](https://github.com/MetrolistGroup/Metrolist) (baseline v14.0.1).
* Original project copyright &copy; Metrolist contributors.
* DHUNLO modifications and branding copyright &copy; 2026 DHUNLO contributors.
* For complete third-party component licenses and modification notices, see [NOTICE.md](NOTICE.md).
