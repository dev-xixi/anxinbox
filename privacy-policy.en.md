---
layout: default
title: AnxinKit · Privacy Policy
permalink: /privacy-en/
---

# AnxinKit · Privacy Policy

**Effective date: April 17, 2026**
**Last updated: April 17, 2026**

This Privacy Policy ("Policy") explains how **AnxinKit** (Chinese name 安心工具箱, hereafter "the App", "we", "us") handles information when you use the App. Please read this Policy carefully before using the App. If you do not agree with any part of this Policy, please do not use the App.

---

## 1. Overview

AnxinKit is a fully **on-device** iOS utility suite. It includes — but is not limited to — document scanning, OCR, QR / barcode generation and recognition, color picking, unit conversion, password generation, a Pomodoro timer, local reminders, and a compass.

> **Core promise: the App does not collect, upload, or forward any of your personal information or any content produced by its tools. Everything is processed locally on your device.**

---

## 2. Data we process and why

The table below lists every device capability the App uses, and the purpose. **None of this data ever leaves your device** — there is no remote server.

| Feature | iOS capability used | Purpose | Leaves device? |
| --- | --- | --- | --- |
| Document scanning / photo | Camera | Capture and detect document edges | No |
| Live OCR / Text recognition | Camera, Vision framework | Recognize text inside the viewfinder | No |
| Scan / Barcode recognition | Camera | Decode QR / barcodes | No |
| Import from Photos | Photo library (only the picture you pick) | Decode QR codes inside the picture | No |
| Save photo | Photo library (write only) | Save captured photos / generated QR codes | No |
| Color picker | Photo library (only the picture you pick) | Sample pixel color from the image | No |
| Local reminders | Notifications (local) | Fire a local notification at the time you set | No |
| Pomodoro | Notifications (local), haptics | Notify when a phase ends | No |
| Compass / Level | Location (when in use), motion sensors | Compute true north / device tilt | No |
| One-tap Wi-Fi join | NetworkExtension (HotspotConfiguration) | Hand the scanned Wi-Fi to the OS for joining | No (handled by iOS) |
| Save contact | Contacts (write) | Save scanned vCard / MeCard as a contact | No |
| Add to calendar | Calendar (write) | Add scanned VEVENT as a calendar event | No |

We do **not** collect or store:

- Any identifying information such as your name, gender, birthday, email, phone number, ID card number or bank card number
- Your location, IP address, IDFA, or any device-unique identifier
- Any photo, text, QR code, or password content you capture, scan, recognize, or generate
- Your contacts, calendar events or Wi-Fi passwords

> The App does **not** require an account. It contains **no analytics SDKs, no advertising SDKs, and no third-party tracking**.

---

## 3. Permissions

The App uses the following iOS permissions, requested only when needed. You can revoke any of them at any time from **Settings → AnxinKit**:

- **Camera** — for taking photos, scanning, live OCR and document scanning.
- **Photo Library (read)** — only when you actively pick a picture for recognition or color sampling. We only read the picture you pick.
- **Photo Library (write)** — to save captured photos or generated QR codes.
- **Microphone** — only used implicitly by camera video sessions; the App does not record audio of its own.
- **Notifications** — only for local reminders that you scheduled. Never used for ads or marketing.
- **Location (when in use)** — only used by the compass to compute magnetic declination. The result never leaves your device.
- **Contacts (write)** — only when you choose to save a scanned vCard / MeCard.
- **Calendar (write)** — only when you choose to add a scanned event to your calendar.
- **Hotspot Configuration (NetworkExtension)** — only when you choose to join a scanned Wi-Fi network. iOS will display its own confirmation dialog; the password is not retained by the App.

---

## 4. On-device storage

So that you can come back to your work, some data is stored locally in the App's sandbox (`UserDefaults` or MMKV), including:

- Scan history (content, timestamp, favourite flag, tags)
- Reminder list and schedules
- Pomodoro session statistics
- Color palettes you create
- Your in-app preferences

This data never leaves your device. Uninstalling the App removes everything; you can also use the "Clear all" button inside each module.

---

## 5. Third parties

The App ("Toolbox" face) integrates **no third-party analytics, advertising, push or data-tracking SDKs**, and does not share information with any third party.

---

## 6. Children's privacy

The App is not directed to children under 13. We do not knowingly collect personal information from children. If you believe a child has used the App without your authorization, please contact us using the details below.

---

## 7. Data security

Because all data lives on your own device, security depends primarily on your device settings. We recommend:

- Set a passcode and enable Face ID / Touch ID
- Avoid leaving your scan / reminder history on shared devices
- Use Apple's Find My to remotely erase a lost device

---

## 8. Changes to this Policy

We may update this Policy from time to time. The "Last updated" date at the top will reflect changes. Material changes will be highlighted inside the App. Continuing to use the App after a change means you accept the updated Policy.

---

## 9. Contact us

For any questions, comments or complaints about this Policy, please contact us:

- Email: **xan001753@gmail.com**

We aim to reply within 15 working days.

---

> This English version is for reference only. In case of discrepancy, the **Chinese version prevails**.
> [中文版 »]({{ "/privacy/" | relative_url }})
