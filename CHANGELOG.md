# 📜 Changelog

## v2005.11.12 - Twin Helix Edition (Beta) - November 8, 2025

### 🚀 New Features

**🌐 Network Drive Support (NEW!):**
- ✨ **Scan Network Drives** - Full support for mapped network drives (Z:, Y:, etc.)
- 🔗 **UNC Path Support** - Automatically converts drive letters to UNC paths (\\\\server\\share)
- 🗑️ **Network Recycle Bin** - Scans ONLY deleted files in network drive Recycle Bin
- ➕ **Manual Drive Input** - Add network drives manually with persistent storage
- 💾 **Saved Configuration** - Manual drives saved to config file (manual_drives.json)
- ➖ **Remove Drives** - Remove manually added drives from configuration
- 🔍 **Quick/Deep Scans** - Work perfectly on network drives (602 files found!)
- 💾 **Drive Type Icons** - Visual indicators for Network (🌐), Local (💻), USB (💾), CD (💿)
- 📊 **Multi-Drive Recovery** - Recover deleted files from any drive type
- 🔄 **Refresh Drives** - Button to detect newly mapped network drives

**Enhanced UI/UX:**
- ✨ **Row Numbers** - Results table now shows row numbers (1, 2, 3...) for easy reference
- 🎨 **Modern Section Headers** - Gradient backgrounds with accent borders
- 📊 **Enhanced File Counter** - Prominent display with gradient background
- 🎯 **Better Button Styling** - Larger borders, rounded corners, hover effects
- 🌈 **Improved Visual Hierarchy** - Clear sections with consistent styling
- 🌐 **Drive Type Tooltips** - Detailed information for each drive
- 💫 **Professional Appearance** - Polished, modern interface

**Performance Improvements:**
- ⚡ Faster table rendering for large result sets (200k+ files)
- 🚀 Optimized memory usage during scans
- 💨 Smoother scrolling and sorting

**🔬 Advanced File Carving (NEW!):**
- 📁 **50+ File Types** - Expanded from 25 to 50+ supported file signatures
- 🎯 **Header/Footer Detection** - Professional file reconstruction with start/end markers
- ✅ **File Validation** - Integrity checking for JPEG, PNG, GIF, PDF, ZIP formats
- 🧬 **Smart Size Estimation** - Accurate file size calculation using format-specific heuristics
- 📊 **Better Confidence Scoring** - High (95%), Medium (65%), Low (30%) based on validation
- 🔍 **Fragment Detection** - Identifies file fragments in unallocated space

**Enhanced File Support:**
- 📁 Images: JPEG, PNG, GIF, BMP, TIFF, PSD, WebP, ICO
- 📄 Documents: PDF, DOCX, XLSX, PPTX, DOC, XLS, RTF, ODT
- 🎬 Videos: MP4, AVI, MKV, MOV, WMV, FLV, WebM, MPG
- 🎵 Audio: MP3, WAV, FLAC, AAC, OGG, M4A, WMA
- 📦 Archives: ZIP, RAR, 7Z, TAR, GZ, BZ2
- 💾 Executables: EXE, DLL, SYS, MSI
- 🗄️ Database: SQLite, MDB, ACCDB

**Scanning Enhancements:**
- 🌐 Network drive scanning support (all modes)
- 🧬 Improved Forensic Scan accuracy
- 🔮 Better Deep Scan pattern recognition
- ⚡ Faster Quick Scan with caching
- 🎯 More detailed progress tracking
- 💾 Better drive detection and enumeration

**Recovery Improvements:**
- 💾 Better duplicate file handling
- ✅ Enhanced recovery verification
- 📊 Batch recovery progress tracking
- 🎯 Smarter file naming on recovery

### 🐛 Bug Fixes

- **Fixed app freeze on double-click** - Added safe file info preview
- **Fixed QPainter errors** - Disabled startup animations to prevent conflicts
- **Fixed network drive detection** - Multiple fallback methods to ensure all drives detected
- Fixed table sorting performance with large datasets
- Improved error handling for permission issues
- Better stability during long scans
- Enhanced animation cleanup
- Disabled table editing to prevent UI freezing

### ✨ Improvements

- Better user feedback during operations
- More detailed scan statistics
- Enhanced error messages
- Improved logging system

---

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
