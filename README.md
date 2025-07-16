# Python Utility Programs Collection

A comprehensive collection of useful Python utility programs for various system administration and file management tasks.

## Overview

This collection includes 10 different utility programs that can help with common computing tasks:

1. **File Organizer** - Automatically organize files by extension
2. **Password Generator** - Generate secure passwords with customizable criteria
3. **Duplicate File Finder** - Find and manage duplicate files
4. **System Information** - Display comprehensive system information
5. **File Backup Tool** - Create and manage file backups
6. **Text File Analyzer** - Analyze text files for statistics and content
7. **Directory Size Calculator** - Calculate and analyze directory sizes
8. **File Renamer** - Batch rename files with various patterns
9. **Image Resizer** - Resize and convert images (requires Pillow)
10. **Log File Cleaner** - Clean and manage log files

## Installation

1. **Clone or download** this repository to your local machine

2. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the main menu:**
   ```bash
   python main.py
   ```

## Requirements

- Python 3.6 or higher
- psutil (for system information)
- Pillow (for image processing)

## Individual Program Usage

You can also run each utility program individually:

```bash
python file_organizer.py
python password_generator.py
python duplicate_finder.py
# ... etc
```

## Features

### 🗂️ File Organizer
- Automatically sorts files into folders by extension
- Supports custom directory selection
- Safe file moving with error handling

### 🔐 Password Generator
- Generate passwords with customizable length and character sets
- Password strength analysis
- Option to exclude ambiguous characters
- Support for different character types (uppercase, lowercase, numbers, symbols)

### 🔍 Duplicate File Finder
- Fast duplicate detection using MD5 hashing
- Interactive deletion with file preview
- Supports recursive directory scanning
- Shows potential space savings

### 💻 System Information
- Comprehensive system details (CPU, memory, disk, network)
- Real-time monitoring capabilities
- Process information and resource usage
- Cross-platform compatibility

### 💾 File Backup Tool
- Create full or compressed (ZIP) backups
- Exclude patterns support
- Backup scheduling simulation
- Restore functionality with undo information

### 📝 Text File Analyzer
- Detailed text analysis (word count, character count, etc.)
- Batch analysis of multiple files
- Search functionality across files
- Reading time estimation
- Word frequency analysis

### 📊 Directory Size Calculator
- Calculate directory sizes with file/folder counts
- Find largest files and directories
- Compare two directories
- Generate detailed size reports
- Find and clean empty directories

### ✏️ File Renamer
- Batch rename with regex patterns
- Case conversion (lowercase, UPPERCASE, Title, camelCase, snake_case, kebab-case)
- Sequential numbering
- Add/remove prefixes and suffixes
- Change file extensions
- Preview before applying changes
- Undo functionality

### 🖼️ Image Resizer
- Resize images while maintaining aspect ratio
- Batch processing capabilities
- Create thumbnails
- Convert between image formats (JPEG, PNG, BMP, TIFF, WEBP)
- Detailed image information display
- Quality control for compression

### 🗄️ Log File Cleaner
- Clean old and large log files
- Archive logs with compression
- Log rotation functionality
- Bulk operations support
- Configurable age and size limits

## Usage Examples

### File Organization
```bash
python file_organizer.py
# Enter the path to the directory you want to organize
# Files will be moved to subdirectories based on their extensions
```

### Password Generation
```bash
python password_generator.py
# Choose length, character types, and other options
# Get a secure password with strength analysis
```

### System Monitoring
```bash
python system_info.py
# View comprehensive system information
# Monitor CPU and memory usage in real-time
```

## Safety Features

- **Preview Mode**: Most operations show what will happen before execution
- **Undo Functionality**: File renaming operations can be undone
- **Backup Verification**: Backups are verified before original files are modified
- **Error Handling**: Comprehensive error handling for file operations
- **Permission Checking**: Respects file system permissions

## Supported Platforms

- Windows
- macOS
- Linux

## File Structure

```
PythonProgram/
├── main.py                 # Main menu launcher
├── file_organizer.py       # File organization utility
├── password_generator.py   # Password generation utility
├── duplicate_finder.py     # Duplicate file finder
├── system_info.py         # System information display
├── backup_tool.py         # File backup utility
├── text_analyzer.py       # Text file analysis
├── dir_size_calc.py       # Directory size calculator
├── file_renamer.py        # Batch file renaming
├── image_resizer.py       # Image processing utility
├── log_cleaner.py         # Log file management
├── requirements.txt       # Python dependencies
└── README.md             # This file
```

## Contributing

Feel free to contribute to this project by:
- Adding new utility programs
- Improving existing functionality
- Fixing bugs
- Adding new features
- Improving documentation

## License

This project is open source and available under the MIT License.

## Troubleshooting

### Common Issues

1. **Import Errors**: Make sure you've installed all requirements:
   ```bash
   pip install -r requirements.txt
   ```

2. **Permission Errors**: Run with appropriate permissions for file operations

3. **Path Issues**: Use absolute paths when possible, especially on Windows

4. **Missing Dependencies**: Some features require specific libraries:
   - System information requires `psutil`
   - Image processing requires `Pillow`

### Getting Help

If you encounter issues:
1. Check that all dependencies are installed
2. Verify file paths are correct
3. Ensure you have necessary permissions
4. Check Python version compatibility (3.6+)

## Future Enhancements

Planned features for future versions:
- GUI interface using tkinter
- Configuration file support
- Scheduled task integration
- Network utilities
- Database management tools
- Email utilities
- Web scraping tools

---

**Note**: Always backup important data before using file manipulation utilities!
