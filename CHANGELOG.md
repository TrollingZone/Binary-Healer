# 📜 Changelog

## v2004.2.8 - Phoenix Byte Edition (Beta) - November 4, 2025

### 🎉 Initial Release

First public release of Binary Healer - a sci-fi themed file recovery tool with raw disk scanning capabilities.

---

### ✨ Features

**Scan Modes:**
- Quick Scan - Recycle Bin only (~seconds)
- Deep Scan - Recycle Bin + Shadow Copies (~minutes)
- Raw Scan - Raw disk sector scanning for permanently deleted files (~10-30 min)
- Sector Scan - Full disk forensic analysis (~hours)

**Recovery:**
- Multi-drive selection with visual feedback
- Real-time progress tracking with ETA
- Confidence ratings (High/Medium/Low)
- Search and filter by type/size
- Batch recovery with duplicate handling
- File signature detection (25+ types)

**UI:**
- Dark sci-fi themed interface
- Smooth animated progress bar
- Activity logging
- Scan cancellation
- Administrator status indicator
- In-app help guide

---

### 🐛 Bug Fixes

- Fixed PyQt6 compatibility issue causing startup crash
- Improved status bar messaging during scans
- Better handling of large result sets (300k+ files)
- Enhanced overflow warnings for display limits

---

### 🛠️ Technical

- PyQt6-based GUI
- Multi-threaded scanning
- Raw disk access via pywin32
- File signature detection
- Modular architecture

---

### ⚠️ Known Issues

- Display limited to first 10,000 files (all files still recoverable)
- Raw/Sector scans require administrator privileges
- Shadow Copy access may need admin for other users' files

---

### 📝 Notes

This is a BETA release. Please report bugs and feedback via GitHub Issues.

Recovery success depends on disk usage after deletion. Act fast for best results!
