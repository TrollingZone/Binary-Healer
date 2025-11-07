# 📜 Changelog

## v2005.11.11 - Twin Helix Edition (Beta) - November 6, 2025

### 🎉 Major Update - Twin Helix Technology

**Twin Helix** = Two powerful recovery methods working together!

### 🚀 New Features

**🧬 Forensic Scan Mode (NEW!)**
- Professional forensic analysis technology
- **10x FASTER** than Raw Scan (30s-2min vs 10-30min)
- Advanced file system analysis
- Finds deleted file entries with full metadata
- Industry-standard recovery methods

**Multi-File System Support:**
- Windows drives (NTFS, FAT32, exFAT)
- USB drives and SD cards
- External hard drives
- Multiple drive types

**Unlimited Results Display:**
- **NO MORE 10,000 FILE LIMIT!**
- All scan results now displayed in table
- Tested with 173,999+ files successfully
- Smooth loading with progress updates
- All files visible and recoverable

**🎨 Enhanced UI/UX:**
- Modern dark sci-fi theme with smooth animations
- Fade-in effects for startup
- Animated progress bars with gradients
- Smooth hover effects on all interactive elements
- Better visual hierarchy and spacing
- Professional appearance

### ✨ Improvements

- New Forensic Scan button with purple/magenta accent
- Better scan mode organization
- Enhanced tooltips with speed comparisons
- Professional forensic capabilities
- Optimized table loading for large result sets
- Better progress feedback during result loading
- Fixed QPainter warnings from animation conflicts
- Improved graphics effect handling

### 🛠️ Technical

- Advanced forensic scanning engine
- Enhanced multi-threaded scanning
- Removed artificial display limits
- Optimized performance for large result sets
- Improved memory efficiency
- Fixed animation system to prevent QPainter conflicts
- Better graphics effect lifecycle management

### 🐛 Bug Fixes

- Fixed QPainter warnings caused by overlapping graphics effects
- Resolved "Painter not active" errors during animations
- Improved animation cleanup and resource management

---

## v2004.2.8 - Phoenix Byte Edition (Stable) - November 4, 2025

### 🎉 Stable Release

Stable release of Binary Healer - a sci-fi themed file recovery tool with raw disk scanning capabilities.

**Improvements from Beta:**
- Enhanced UI/UX with better visual hierarchy
- Improved table performance and column sizing
- Better tooltips with detailed scan mode information
- File counter display showing total files found
- Larger, more clickable buttons with hover cursors
- Cleaner table design without grid lines
- Optimized window sizing and minimum dimensions
- Better visual feedback throughout the app

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
