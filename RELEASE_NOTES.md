# Antiphon Public Preview 0.1.0

**Release channel:** Public Preview  
**Application version:** 0.1.0-preview  
**Platform:** Windows x64, self-contained  
**Installer:** `Antiphon-PublicPreview-0.1.0-preview-x64-Setup.exe`  
**SHA-256:** `589d6d5d8eb8daf102a9ba88dbd15665ac5a3b5bdaca7acc23c2c693643bf9a2`

## What is included

- Classic Sequential Night Run.
- Device Lanes for verified M1/M2 with independent per-device queues and shared CALL.
- Browsing, Streaming and coordinated MO/MT CALL workflows.
- Safe Pause / Resume / STOP with same-device verification and cleanup evidence.
- Results, timelines, metrics where available, logs and local diagnostics.
- Editable YAML testcases and five installed starters.
- First Run Experience with Preview Terms acceptance and local environment readiness.

Browsing starter defaults to Wikipedia, BBC, CNN and Reuters in order with `visitsPerLoop: 4`, so each URL is visited once per logical loop. Streaming defaults to the official Kapitan Bomba channel live route; broadcast availability and actual playback are not guaranteed. The Universal CALL starter intentionally contains a placeholder that must be replaced with an authorized destination.

## Public Preview limits

- Maximum two distinct physical devices per session (M1 and M2).
- Maximum two hours of active Night Run execution per session; paused time is excluded.
- Unlimited separate sessions.
- No subscription, trial countdown, license key or activation.

The compiled Public Preview channel enforces the device and active-time limits. M3/M4 Device Lanes, Network Recovery, Reboot Recovery and unqualified Device Lanes operations are not included.

## Windows prerequisites

- Windows x64 supported by .NET 10/WPF.
- Android Platform Tools/ADB installed separately; it is not bundled.
- A compatible device USB driver.
- Authorized Android devices with developer options and USB debugging enabled.
- Authorized test numbers, SIMs, accounts, URLs and network environments.

## Install

1. Download the installer from the GitHub Release.
2. Verify its SHA-256 against `checksums/SHA256SUMS.txt`.
3. Run the per-user installer. It creates Start Menu shortcuts for the application and the manual.
4. Keep or choose the Scripts directory. Existing user YAML is never overwritten; missing starters are created.
5. Launch Antiphon, complete First Run and verify **Settings → About**.

The installer preserves user settings, scripts and Results outside the application directory during upgrade and uninstall.

## Known limitations

- The installer is **unsigned**. Windows SmartScreen may warn. Verify the SHA-256; do not disable security protections to bypass a warning.
- Clean-machine, multi-DPI, Defender and broad hardware-matrix acceptance are incomplete.
- Device Lanes is limited to verified M1/M2. Data Connectivity and Network Toggle are Classic-only and not Device Lanes-qualified.
- Network Recovery, Reboot Recovery, M3/M4 Device Lanes and unsupported custom operations are outside Public Preview.
- CALL KPI values remain unavailable; unavailable measurements are not reported as zero.
- Browsing acceptance means Android accepted the navigation command, not that a page loaded.
- Streaming may fail if the live broadcast is offline, the YouTube handler is absent or connectivity is unsuitable.
- Linux is in development and is not part of this release.

## License and notices

Antiphon Public Preview is proprietary freeware, not an open-source release. Its source code is not publicly distributed. Free use is limited to personal or internal testing and evaluation. Third-party components remain subject to their respective licenses; see `THIRD_PARTY_NOTICES.md`. Preview Terms version 0.1.0 are included in the installer and public documentation.

## Feedback

Use the GitHub issue tracker or email **galaz92@gmail.com**. Include the build/channel, exact action and sanitized evidence. Do not include real phone numbers, credentials or private device data.
