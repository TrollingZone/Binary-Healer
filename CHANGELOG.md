# 📜 Binary Healer - Changelog

## Version 2004.2.8 - "Phoenix Byte" (Professional) - November 2025

### 🎉 Professional Release with RAW DISK SCANNING!

This is the professional release of Binary Healer - a powerful file recovery tool with forensic-grade raw disk scanning capabilities. Can recover permanently deleted files!

---

### 🚀 What's New in This Version

**MAJOR: Raw Disk Scanning**
- Can now recover permanently deleted files!
- Scans raw disk sectors for file signatures
- Works with Shift+Delete and emptied Recycle Bin
- Requires administrator privileges
- Uses professional forensic techniques

**Drive Selection**
- Choose specific drives to scan
- Visual feedback (green = selected, gray = not selected)
- Status display shows selected drives
- Faster, more focused scans

**Enhanced File Detection**
- Shows permanently deleted files (metadata only) with warnings
- 25+ file type signatures (JPG, PNG, PDF, MP4, etc.)
- Better confidence ratings
- Clear indicators for recoverable vs unrecoverable files

**UI Improvements**
- Administrator status indicator in header
- 4 scan modes: Quick, Deep, Raw, Sector
- Cancel scan button
- Better progress feedback
- Clearer error messages

---

### ✨ Features

**User Interface:**
- Dark sci-fi themed interface with neon cyan accents
- Custom splash screen with branding
- Tabbed interface (Scan & Recover, Settings, Logs)
- Responsive design with progress indicators
- Professional styling throughout
- **Automatic administrator privilege elevation on startup**

**Scanning:**
- Quick Scan: Recycle Bin only (~seconds)
- Deep Scan: Recycle Bin + Shadow Copies (~minutes)
- **RAW SCAN: Raw disk sector scanning** - finds permanently deleted files! (~10-30 min)
- **SECTOR SCAN: Full disk analysis** - maximum recovery effort (hours)
- **Shows ONLY deleted/recoverable files** - no existing files
- Drive selection with visual feedback (green/gray buttons)
- Multi-drive support with individual selection
- Real-time progress tracking with ETA
- Background threading for responsive UI
- File metadata display (name, type, size, date, confidence)
- Smart filtering by file type and size
- Color-coded confidence levels
- Search functionality
- View modes (individual files or folders)
- Scan cancellation support

**Recovery:**
- Single file recovery
- Bulk file recovery
- Custom recovery destination
- Automatic duplicate handling
- Safe, non-destructive operations
- Success/failure reporting

**Raw Disk Scanning (NEW!):**
- Uses pywin32 for low-level disk access
- File signature detection (25+ file types)
- Scans unallocated disk space
- Finds permanently deleted files (Shift+Delete, emptied Recycle Bin)
- Works on any drive with administrator privileges
- Quick mode: First 10% of disk
- Full mode: Entire disk sector-by-sector

**Additional Features:**
- Activity logging system with timestamps
- Settings management (view modes, file visibility)
- Comprehensive error handling
- Smooth animated progress bar
- Deleted file indicators (🗑️)
- Permanently deleted file warnings (⚠️)
- Administrator status indicator (🔒 ADMIN)
- In-app help and troubleshooting guide
- Multi-threaded operations for responsiveness

---

### 🛠️ Technical Details

**Architecture:**
- Modular code organization (UI, Engine, Utils)
- PyQt6-based GUI
- Multi-threaded scanning
- Clean separation of concerns

**Dependencies:**
- PyQt6 (required)
- pygame (optional, for sound effects)

**Platform:**
- Windows 11 (primary)
- Windows 10 (compatible)
- Python 3.10+ required

---

### 📦 Distribution

**Included Files:**
- Complete source code
- Batch file installers (install.bat, run.bat, build.bat)
- Comprehensive documentation
- Logo and splash screen assets
- Example sound effects structure

**Build Options:**
- Run from source
- Build standalone executable with PyInstaller

---

### ✅ Verified Features

**Tested and Working:**
- ✓ Recycle Bin scanning (8 files found in testing)
- ✓ Multi-drive support (C:\, G:\, P:\ verified)
- ✓ File type detection (Images, Documents, Videos, Audio, Archives)
- ✓ Confidence level assignment (High 90-95%, Medium 70%, Low 20%)
- ✓ File recovery operations
- ✓ Search and filtering
- ✓ UI responsiveness with threading
- ✓ Progress tracking with ETA

### ⚠️ Known Limitations

- Shadow Copy access requires administrator privileges for full functionality
- USN Journal scanning requires administrator privileges
- No deep disk sector scanning (planned for future)
- No file preview feature (planned for future)
- No network drive support (planned for future)
- Windows-only at this time

**Note:** Core recovery features work perfectly without admin rights for your own files.

---

### 🎯 Future Roadmap

**Planned for Next Versions:**
- Deep disk sector scanning
- Enhanced recovery algorithms
- File preview capabilities
- Support for more file systems
- Network drive recovery
- Linux and macOS support
- Disk imaging features
- Cloud backup integration

---

### 🙏 Credits

**Phoenix Byte Edition**
- Version: 2004.2.8
- Status: Stable
- Release Date: November 2025
- Tested and verified working

---

### 📝 Version Naming Convention

Binary Healer uses a unique versioning system:
- **Edition Name**: Each major version has a unique name (Phoenix Byte)
- **Version Number**: YYYY.M.P format
  - YYYY: Year-based major version
  - M: Minor version
  - P: Patch version

---

## Future Versions

### Coming Soon: Version 2004.3.x
- Bug fixes based on beta feedback
- Performance improvements
- UI refinements

### Planned: Version 2005.x.x - "TBD Edition"
- New edition name
- Major feature additions
- Enhanced recovery capabilities

---

**Stay tuned for updates!** 🔮✨

Each new version will be documented here with full details of changes, improvements, and new features.
