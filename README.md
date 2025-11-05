# 🔮 Binary Healer - Professional File Recovery Tool

![Version](https://img.shields.io/badge/version-2004.2.8-blue)
![Edition](https://img.shields.io/badge/edition-Phoenix%20Byte-cyan)
![Status](https://img.shields.io/badge/status-Professional-green)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey)

**Recover files from Recycle Bin, Shadow Copies, and Temp folders**

*Bringing your data back to life* 🔮✨

---

## ⚡ What Binary Healer CAN Do

✅ **Recover files from Recycle Bin** (95%+ success)  
✅ **Find Shadow Copy versions** (70-90% success if enabled)  
✅ **RAW DISK SCANNING** - Find permanently deleted files! (30-60% success)  
✅ **File signature detection** - Recover files without names  
✅ **Show what was deleted** (even if data is gone)

## ⚠️ Requirements for Raw Disk Scanning

🔒 **MUST run as Administrator** for raw disk access  
⚡ **Works on non-system drives** (D:, E:, F:, external drives)  
⏱️ **Takes time** - 10-30 minutes for quick scan, hours for full scan

## ❌ What Binary Healer CANNOT Do

❌ **Cannot recover overwritten data** (if new files written to same location)  
❌ **Cannot recover from formatted drives** (file system destroyed)  
❌ **Cannot fix physically damaged drives**

---

## 📥 Quick Start

### Download & Run
1. Download `BinaryHealer-v2004.2.8.exe` from [Releases](../../releases)
2. Double-click to run
3. **Click "Yes"** when prompted for admin access (REQUIRED for raw disk scanning!)
4. Check header shows **"🔒 ADMIN"** in green
5. Select drives to scan (click to toggle green/gray)
6. Choose scan mode:
   - **Quick Scan** - Recycle Bin only (seconds)
   - **Deep Scan** - + Shadow Copies (minutes)
   - **Raw Scan** - + Raw disk sectors (10-30 min) ⚡ **Finds permanently deleted files!**
   - **Sector Scan** - Full disk (hours) 🔬 **Maximum recovery!**
7. Wait for scan to complete
8. Select files and click "Recover Selected"
9. Done!

> 🔒 **Admin required** for raw disk scanning and best results  
> 💻 **No Python needed** - Standalone executable

---

## 🚀 Scan Modes

### 🗑️ Quick Scan (Recycle Bin)
- **Speed:** ~Seconds
- **Scans:** Recycle Bin only
- **Best for:** Recently deleted files
- **Success Rate:** 95%+

### 🔮 Deep Scan (+ Shadow Copies)
- **Speed:** ~Minutes
- **Scans:** Recycle Bin + Shadow Copies + Temp files
- **Best for:** Older versions, comprehensive search
- **Success Rate:** 70-90%

### ⚡ Raw Scan (+ Raw Disk) **NEW!**
- **Speed:** ~10-30 minutes
- **Scans:** Everything + Raw disk sectors (first 10%)
- **Best for:** Permanently deleted files (Shift+Delete)
- **Success Rate:** 30-60%
- **Finds files after Recycle Bin emptied!**

### 🔬 Sector Scan (Deep Forensic) **NEW!**
- **Speed:** Hours
- **Scans:** Deep sector-by-sector analysis
- **Best for:** Maximum recovery effort
- **Success Rate:** 10-40%
- **Professional forensic recovery!**

---

## 🎯 Key Features

### Drive Selection **NEW!**
- ✅ Choose specific drives (C:\, D:\, E:\, etc.)
- ✅ Visual feedback (green = selected, gray = not selected)
- ✅ "Select All" / "Deselect All" buttons
- ✅ Status display shows selected drives

### Raw Disk Scanning **NEW!**
- ✅ Finds permanently deleted files
- ✅ File signature detection (JPG, PNG, PDF, MP4, etc.)
- ✅ Scans unallocated disk space
- ✅ Works after Recycle Bin emptied

### Smart Recovery
- ✅ Confidence ratings (High/Medium/Low)
- ✅ Real-time file discovery
- ✅ Search and filtering
- ✅ Batch recovery
- ✅ Automatic duplicate handling

### User Interface
- ✅ Dark sci-fi theme
- ✅ Smooth progress bar with ETA
- ✅ Activity logs
- ✅ Cancel long scans
- ✅ In-app help

---

## 📖 How to Use

### For Recently Deleted Files (Most Common)
1. Launch Binary Healer
2. Select drives (or keep all selected)
3. Click **"Quick Scan"**
4. Wait a few seconds
5. Select files and click **"Recover Selected"**

### For Permanently Deleted Files (Shift+Delete)
1. Launch Binary Healer
2. **Select only the drive** where files were deleted
3. Click **"Raw Scan"**
4. Wait 10-30 minutes
5. Look for "Recovered_*" files
6. Recover what you find

### For Maximum Recovery (Last Resort)
1. Launch Binary Healer
2. Select specific drive
3. Click **"Sector Scan"**
4. Confirm the warning (can take hours!)
5. Wait patiently
6. Review all findings
7. Recover everything possible

---

## 💡 Understanding File Recovery

### What Binary Healer CAN Recover

#### ✅ Files in Recycle Bin
- **How:** Normal delete (Delete key)
- **Success:** 95%+
- **Time:** Seconds
- **Mode:** Quick Scan

#### ✅ Shadow Copy Versions
- **How:** Windows backup feature
- **Success:** 70-90%
- **Time:** Minutes
- **Mode:** Deep Scan
- **Requires:** Shadow Copies enabled

#### ✅ Permanently Deleted Files
- **How:** Shift+Delete or emptied Recycle Bin
- **Success:** 30-60%
- **Time:** 10-30 minutes
- **Mode:** Raw or Sector Scan
- **Requires:** Admin, minimal disk use since deletion

### What Binary Healer CANNOT Recover

#### ❌ Overwritten Files
- New data written to same location
- Success rate drops rapidly over time
- Stop using drive immediately after deletion!

#### ❌ Formatted Drives
- File system structure destroyed
- Requires specialized tools

#### ❌ Physically Damaged Drives
- Hardware failure
- Requires professional data recovery service

---

## 📊 Confidence Ratings

### 🟢 High (90-95%)
- Files in Recycle Bin
- Shadow Copy versions
- Complete file data available
- **Excellent recovery chances**

### 🟡 Medium (60-70%)
- Raw disk scan findings
- Temp file copies
- Partial data available
- **Good recovery chances**

### 🔴 Low (20-30%)
- Zero-byte files
- Heavily fragmented
- Uncertain data
- **Limited recovery chances - worth trying**

---

## 🔍 Search & Filtering

### Search
- Type to search file names instantly
- Case-insensitive
- Real-time filtering

### File Type Filters
- **Images:** JPG, PNG, GIF, BMP, SVG, WebP, ICO
- **Documents:** PDF, DOC, DOCX, TXT, XLS, XLSX, PPT, PPTX
- **Videos:** MP4, AVI, MKV, MOV, WMV, FLV, WebM
- **Audio:** MP3, WAV, FLAC, AAC, OGG, M4A, WMA
- **Archives:** ZIP, RAR, 7Z, TAR, GZ, BZ2

### Size Filters
- < 1 MB
- 1-10 MB
- 10-100 MB
- \> 100 MB

### View Modes
- **Individual Files** - See each file separately
- **Folders Only** - Group by parent folder

---

## 🐛 Troubleshooting

### No Files Found?

**If using Quick Scan:**
- Files must be in Recycle Bin
- Try Deep Scan for Shadow Copies
- Try Raw Scan for permanently deleted

**If using Raw/Sector Scan:**
- Files may have been overwritten
- Too much time passed since deletion
- Disk was heavily used after deletion

### Scan Taking Too Long?
- Click **"Cancel Scan"** button
- Returns partial results
- Try Quick or Deep Scan instead

### Permission Denied?
- Run as administrator (right-click → Run as administrator)
- Some Recycle Bin folders need admin
- Raw/Sector scans require admin

### Recovery Failed?
- Check destination has write permissions
- Ensure enough disk space
- Try different destination folder

---

## ⚠️ Important Limitations

### Cannot Recover:
- ❌ Files deleted with Shift+Delete (unless found by Raw/Sector scan)
- ❌ Files after Recycle Bin emptied (unless found by Raw/Sector scan)
- ❌ Files from formatted drives
- ❌ Files overwritten by new data
- ❌ Encrypted files without key

### Best Practices:
1. **Act Fast** - Scan immediately after deletion
2. **Stop Using Drive** - Don't save new files
3. **Try Quick First** - Escalate to Raw/Sector if needed
4. **Enable Shadow Copies** - Automatic backup for future
5. **Regular Backups** - Prevention is better than recovery!

---

## 🎮 Interface Guide

### Tabs
- **🔍 Scan & Recover** - Main scanning interface
- **⚙️ Settings** - View options
- **📋 Logs** - Activity history
- **❓ Help** - Quick guide

### Scan Controls
- **Drive Selection** - Choose which drives to scan
- **Shadow Path** - Optional for Deep/Raw/Sector scans
- **4 Scan Buttons** - Quick, Deep, Raw, Sector
- **Cancel Button** - Stop long scans

### Results Table
- **File Name** - With 🗑️ icon for deleted files
- **Type** - File category
- **Size** - Human-readable size
- **Date** - Last modified
- **Confidence** - Color-coded rating
- **Path** - Full file location

---

## 📈 Performance

| Scan Mode | Time | Files Found | Admin Required |
|-----------|------|-------------|----------------|
| Quick | 5-30 sec | Recycle Bin | No |
| Deep | 1-5 min | + Shadow Copies | Recommended |
| Raw | 10-30 min | + Permanently deleted | Yes |
| Sector | 1-8 hours | Maximum recovery | Yes |

---

## 🔒 Security & Privacy

### Local Processing
- All scanning done on your computer
- No internet connection required
- Your data never leaves your machine

### Administrator Access
- Required for raw disk scanning
- Automatically requested on startup
- Can decline for Recycle Bin only

### Safe & Non-Destructive
- Never modifies original files
- Read-only operations
- Can't make things worse

---

## 💻 System Requirements

- **OS:** Windows 10/11
- **RAM:** 4GB minimum, 8GB recommended
- **Disk Space:** 100MB for app + space for recovered files
- **Permissions:** User-level (admin for raw scanning)
- **Drives:** Local drives (internal/external/USB)

---

## 📝 Version History

### v2004.2.8 - Phoenix Byte (Professional)

**New Features:**
- ⚡ Raw Scan mode with disk sector scanning
- 🔬 Sector Scan mode for deep forensic analysis
- 🎯 Drive selection with visual feedback
- ❌ Scan cancellation
- 📊 File signature detection (13+ types)

**Improvements:**
- Enhanced Recycle Bin scanning
- Better confidence ratings
- Improved UI with status displays
- Professional forensic capabilities

**Technical:**
- Raw disk access via Windows API
- File signature detection
- Multi-threaded scanning
- Cancellable operations

For detailed version history, see [CHANGELOG.md](CHANGELOG.md).

---

## 🙏 Support

- 🐛 **Bug Reports:** [GitHub Issues](../../issues)
- 💡 **Feature Requests:** [GitHub Issues](../../issues)
- 📥 **Download:** [Latest Release](../../releases)
- ⭐ **Star the Project:** Show your support!

---

## 📄 License

**Copyright © 2025 Binary Healer. All Rights Reserved.**

This is proprietary software.

**Permitted:**
- ✅ Download and use for personal use
- ✅ Report bugs and suggest features

**Not Permitted:**
- ❌ Reverse engineering
- ❌ Redistribution
- ❌ Commercial use without permission

---

## 🎯 Quick Tips

1. **Recently deleted?** → Quick Scan
2. **Shift+Delete?** → Raw Scan
3. **Recycle Bin emptied?** → Raw or Sector Scan
4. **Need old version?** → Deep Scan (Shadow Copies)
5. **Maximum effort?** → Sector Scan (be patient!)

**Remember:** The sooner you scan, the better your chances! 🚀

---

<div align="center">

**Binary Healer** - Phoenix Byte Edition v2004.2.8

Professional File Recovery with Forensic Capabilities

Made with ❤️ and Python

*Bringing your data back to life* 🔮✨

[⬆ Back to Top](#-binary-healer---professional-file-recovery-tool)

</div>
