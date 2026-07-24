# KoshaDrive 24.07.2026

<p align="center">
  <strong><font color="#58A6FF">A revolutionary file manager that stores files in the unlimited Telegram cloud.</font></strong>
</p>

**Version:** `ver.24.07.2026`

## Download

**Installer:** `KoshaDriveSetup_24.07.2026.exe`

---

## What's new in 24.07.2026

- **Cleaner Telegram cloud after DB normalization** — stale `#koshadrive_sys_db` and comments-database copies are pruned automatically when your local database is verified.
- **More reliable database open** — fixes interrupted schema migration (`filesystem_old_v12`) and incomplete-upload bookkeeping.
- **Simpler cross-device DB sync** — removed cloud HMAC signature checks and the signature-conflict dialog that could block legitimate restores.
- **Clearer no-license screen** — guided path to license settings or demo mode.
- **Color emoji in comments** — Twemoji icons in the emoji panel on Windows.
- **Help tip** — for very large uploads, you can bulk-send files via the Telegram client to **Saved Messages**, then organize them in KoshaDrive (not for **My Cloud** mode).

---

## Description

<img src="https://flagcdn.com/20x15/gb.png" alt="EN" width="20" height="15" align="top" /> **KoshaDrive** turns Telegram into your personal cloud drive on Windows — an Explorer-style file manager with a folder tree, thumbnails, drag-and-drop, and sync. Your files stay organized, not lost in chat history.

## Features

KoshaDrive is a **cloud file manager** for Windows: turn Telegram into a personal drive with an Explorer-like UI, folder tree, thumbnails, uploads, and sync.

### Cloud & virtual filesystem
- **Virtual FS** — folders and files in a tree, not buried in chat history.
- **Multiple storages** — My Cloud, Favorites, Saved Messages; switch workspaces easily.
- **Cloud scan** — reconcile local DB with Telegram; metrics for found / verified / new items.
- **File comments** and **colored folder icons** for quick navigation.

### Upload & download
- **Drag-and-Drop into the cloud** — drop files and entire folders from Explorer.
- **Smart large-folder uploads** — live prep progress, cancel anytime; resume after failures.
- **Downloads manager** — queue, pause, resume, background transfer control.
- **Drag-and-Drop outward** — pull files from the cloud into Windows and other apps.

### Browse & organize
- Views: **details, tiles, icons, Gallery** with zoom and cover-crop for photos/videos.
- **Search** and **sort**; **favorites** (stars).
- **Thumbnails** with retry on network errors — previews stay responsive.

### Recycle Bin (Windows-style)
- Deleted items go to a **Recycle Bin**; restore or purge permanently.
- Empty bin manually or on schedule.

### Security & licensing
- Encrypted local database (SQLCipher).
- Demo mode (14 days, one-time per install).
- License activation and remote policy checks.

---

## System requirements

- Windows 10/11 (64-bit)
- Telegram account
- Internet connection

## Support

- Telegram: [KoshaDrive chat](https://t.me/KoshaDrive_chat)
- Issues: use the support chat (this repo is releases-only)

## License

Proprietary. See the installer EULA.
