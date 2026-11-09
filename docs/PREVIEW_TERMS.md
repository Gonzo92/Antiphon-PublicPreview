# Antiphon Public Preview Terms — Owner Review Candidate

**STATUS: OWNER/LEGAL REVIEW REQUIRED. NOT APPROVED FOR PUBLICATION.**

This document is a release-preparation draft, not legal advice. It must not be presented as approved terms until the owner and legal reviewer have completed the items in the approval checklist below.

**Version:** preview-terms-0.1.0-review-1
**Date:** 2026-11-09
**Product:** Antiphon Public Preview 0.1.0, Windows x64

## 1. Independently developed proprietary software

Antiphon is independently developed and maintained by Mateusz Gałązka (GNZ). It is proprietary software, not open-source software. No source-code license is granted by this document or by the Public Preview download. No MIT, Apache, GPL or other open-source license applies to the Antiphon application code.

## 2. Free Public Preview

The Public Preview is provided free of charge for evaluation. There is no purchase price, subscription, trial countdown, license key, activation server or expiry date. Access does not create an entitlement to future versions, features or support.

## 3. Preview limits

The compiled Public Preview channel enforces these limits:

- **Two distinct physical Android devices per session.** Public Preview execution is limited to M1 and M2. M3/M4 Device Lanes execution is not enabled.
- **Two hours of active Night Run execution per session.** Paused time is excluded. The limit applies to Classic Night Run and Device Lanes active execution.
- **Unlimited separate sessions.** The limits apply per session, not to the total number of sessions.
- At a limit, new admission closes and existing bounded STOP, cleanup, restoration and quarantine behavior applies. A limit is not a successful test result.

Device Lanes is limited to verified M1/M2 topologies. Data Connectivity and Network Toggle are available for Classic execution but are not qualified for Device Lanes. Network Recovery, Reboot Recovery, unsupported custom operations and M3/M4 Device Lanes are outside Public Preview.

## 4. Evaluation status; no guarantee of uninterrupted operation

The software is supplied for evaluation and testing. To the maximum extent permitted by applicable law, it is provided without a guarantee of uninterrupted, error-free or uninterrupted operation, without a guarantee that every device, driver, network, operator or Android version will work, and without a guarantee that a page, app, call or stream will load, play or remain connected. Nothing in these terms excludes or limits rights or liabilities that cannot lawfully be excluded or limited.

## 5. Operator responsibilities

The operator is responsible for:

- using only devices, SIMs, phone numbers, accounts, URLs and network environments that the operator owns or is authorized to test;
- complying with applicable law, the device/network operator's terms, and the terms of any third-party service used by a testcase;
- supervising initial runs and CALL workflows;
- protecting test data, credentials and personal information;
- ensuring that calls, messages, browsing, streaming and data use are authorized and lawful.

No root access is required or assumed. Do not use Antiphon to intercept communications, defeat access controls or conduct unlawful surveillance.

## 6. Ownership and intellectual property

Antiphon, its name, visual identity, documentation, compiled application and associated materials are owned by Mateusz Gałązka (GNZ) and are protected by applicable intellectual-property laws. Copyright © 2026 Mateusz Gałązka. All rights reserved.

Third-party components remain the property of their respective owners and are governed by their own licenses. See the third-party notices supplied with the release.

## 7. Permitted use and redistribution

Subject to these terms, you may install and use the unmodified Windows installer on computers that you own or control for personal or internal evaluation of the Public Preview.

You may share a link to the official release page. You may not, without prior written permission from the owner:

- sell, rent, lease, sublicense or commercially exploit the installer or the application;
- redistribute, mirror, bundle, republish or make the installer available from another website or product;
- modify, adapt, merge or create derivative works from the compiled application;
- remove or obscure copyright, license or third-party notices.

You may not reverse engineer, decompile or disassemble the application except to the extent that applicable law expressly permits it despite this restriction.

Extended Preview access is available on request. No automated entitlement or commercial licensing system is claimed.

## 8. Local data and privacy

The application does not include a telemetry, analytics or advertising SDK, does not require an account and does not automatically upload settings, scripts, Results, diagnostics or device data to the owner. Execution evidence, scripts, settings and diagnostics are stored locally in the locations shown by the application. Support bundles are generated locally and are shared only if the operator chooses to share them.

The application communicates with Android devices through the operator's local ADB setup. Testcases may open websites, apps or streaming services, and those third-party services receive network traffic according to their own terms and privacy policies. A public URL or network probe is not a claim that the owner collects that traffic.

Local Results and diagnostics can contain device identifiers, phone numbers, URLs, SSIDs/BSSIDs, paths and other sensitive data. The operator must review them before sharing. No general anonymization guarantee is made.

## 9. What is not included

Public Preview does not include: a Linux release (Linux is in development), an installer signing certificate, a clean-machine or broad hardware compatibility certification, M3/M4 Device Lanes execution, Device Lanes qualification for Data Connectivity or Network Toggle, Network Recovery, Reboot Recovery, CALL KPI values from a verified production modem collector, an AI Analyst, a commercial licensing service, or a guarantee of overnight/unattended reliability.

## 10. Third-party components

Bundled third-party components and their license terms are listed in the accompanying third-party notices. External requirements such as Android Platform Tools/ADB, a device USB driver, YouTube or a browser, and Windows are not bundled unless the release explicitly says so. Their own terms apply.

## 11. Feedback and contact

Feedback and defect reports may be sent to **galaz92@gmail.com** or through **https://github.com/Gonzo92**. Include the build/channel, the exact action and sanitized evidence. Do not include real phone numbers, credentials or private device data. No response time or support level is guaranteed.

## 12. Changes and acceptance

The owner may update these terms for a later preview or release. The version and date shown above identify this review candidate. Acceptance recorded by the First Run Experience records the displayed version and UTC timestamp locally; it does not replace owner/legal approval of these terms.

## Owner/legal approval checklist

Publication remains blocked until the owner/legal reviewer records decisions on:

1. Approval of this exact text and version.
2. The governing-law and venue clause, which is intentionally not invented here.
3. The intended redistribution permission and any commercial-use restriction.
4. The privacy wording against the actual release payload.
5. Approval of the third-party notices and the bundled dependency inventory.
6. Approval of the video distribution rights if the promotional video is to be published.
7. The unsigned-installer/SmartScreen disclosure.
