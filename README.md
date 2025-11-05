# 🔮 Binary Healer - Phoenix Byte Edition

![Version](https://img.shields.io/badge/version-2004.2.8-blue)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey)
![Status](https://img.shields.io/badge/status-Beta-orange)

**Sci-fi themed file recovery tool for Windows**

Recover deleted files from Recycle Bin, Shadow Copies, and raw disk sectors.

---

## 🚀 Quick Start

1. Download from [Releases](../../releases)
2. Run as Administrator (for raw disk scanning)
3. Select drives to scan
4. Choose scan mode (Quick/Deep/Raw/Sector)
5. Recover your files

---

## ✨ Features

### 4 Scan Modes
- **Quick Scan** - Recycle Bin only (~seconds)
- **Deep Scan** - + Shadow Copies (~minutes)
- **Raw Scan** - + Raw disk sectors, finds permanently deleted files (~10-30 min) ⚡
- **Sector Scan** - Full disk forensic analysis (~hours) 🔬

### Smart Recovery
- Multi-drive selection
- Real-time progress with ETA
- Confidence ratings (High/Medium/Low)
- Search & filter by type/size
- Batch recovery
- Dark sci-fi UI theme

---

## 💡 What Can It Recover?

✅ **Recycle Bin files** (95%+ success)  
✅ **Shadow Copy versions** (70-90% if enabled)  
✅ **Permanently deleted files** (30-60% via raw scan)  
✅ **File signature detection** (JPG, PNG, PDF, MP4, etc.)

❌ **Cannot recover:** Overwritten data, formatted drives, physically damaged disks

---

## 📖 Usage

### Recently Deleted Files
1. Click **Quick Scan**
2. Wait a few seconds
3. Select files → **Recover Selected**

### Permanently Deleted (Shift+Delete)
1. Select the drive where files were deleted
2. Click **Raw Scan** (requires admin)
3. Wait 10-30 minutes
4. Recover found files

---

## 🐛 Troubleshooting

**No files found?**
- Quick Scan only finds Recycle Bin files
- Try Raw Scan for permanently deleted files
- Files may be overwritten if disk was used heavily

**Permission denied?**
- Right-click → Run as Administrator
- Raw/Sector scans require admin privileges

**Scan too slow?**
- Click **Cancel Scan** for partial results
- Try Quick or Deep Scan instead

---

## 💻 Requirements

- Windows 10/11
- 4GB RAM (8GB recommended)
- Administrator privileges (for raw scanning)

---

## 📝 Tips

- **Act fast** - Scan immediately after deletion
- **Stop using the drive** - Prevents overwriting
- **Try Quick first** - Escalate to Raw if needed
- **Enable Shadow Copies** - Automatic backups

---

## 🙏 Support

- 🐛 [Report Issues](../../issues)
- ⭐ Star the project
- 📥 [Download Latest](../../releases)

---

## 📄 License

Proprietary software. Free for personal use. See LICENSE for details.

---

<div align="center">

**Binary Healer v2004.2.8 Beta**

Made with ❤️ and Python

</div>
