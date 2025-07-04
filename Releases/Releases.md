# Release Notes

## [25.3.1] - 2025-07-04

### Added
- Initial release of MarkdownShepherd
- File history management with appsettings.json persistence
- Theme support with multiple themes and palettes
- Markdown document viewing and printing
- File search functionality
- Auto-refresh capability with configurable interval

### Fixed
- Fixed file removal issue where removed files were being added back to history
- Added proper file locking mechanism to prevent concurrent access to appsettings.json
- Improved timer management during file operations

### Technical Details
- Implemented thread-safe file operations using lock mechanism
- Added proper cleanup of resources in finally blocks
- Improved error handling and user feedback
- Enhanced UI responsiveness during file operations 

### Download
- [Markdown Shepherd Setup File](https://github.com/netizenk/MarkdownShepherd/blob/main/Releases/MarkdownShepherdSetup-25.3.1.exe)
