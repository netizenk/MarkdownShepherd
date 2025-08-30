# Release Notes

## [25.3.4] - 2025-08-29

### Added
- Display file name without extension in file list.
- Prompt user to provide file name when creating new file
- Apply selected theme to editor windows as well
- Added context menu to file list.

### Download
- [Markdown Shepherd Setup File](https://raw.githubusercontent.com/netizenk/MarkdownShepherd/refs/heads/main/Releases/MarkdownShepherdSetup-25.3.4.exe)

## [25.3.3] - 2025-07-09

### Added
- Ability to create and save new markdown files.

### Download
- [Markdown Shepherd Setup File](https://raw.githubusercontent.com/netizenk/MarkdownShepherd/refs/heads/main/Releases/MarkdownShepherdSetup-25.3.3.exe)

## [25.3.2] - 2025-07-08

### Fixed
- Fixed version numbering

### Download
- [Markdown Shepherd Setup File](https://raw.githubusercontent.com/netizenk/MarkdownShepherd/refs/heads/main/Releases/MarkdownShepherdSetup-25.3.2.exe)

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
- [Markdown Shepherd Setup File](https://raw.githubusercontent.com/netizenk/MarkdownShepherd/refs/heads/main/Releases/MarkdownShepherdSetup-25.3.1.exe)
