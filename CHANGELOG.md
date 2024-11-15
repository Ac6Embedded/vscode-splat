# Change Log

## [1.0.8]

### New Features

- **Splat Support on macOS**:  
Splat is now fully supported on Visual Studio Code for macOS! Users can seamlessly install and configure Splat directly within the VS Code environment. Handling for cases where Mono is not installed has been added, ensuring smoother setup. Dependency versioning is now implemented to enhance reliability. For detailed installation steps, see the updated README.

- **Command-Line Mode for Splat**:  
Added the ability to run Splat without a graphical interface. This allows users to integrate Splat more effectively into automated workflows or use it in headless environments.

### Enhancements

- **Splat Interface Updates**:  
  - Removed the "Update Dependencies" button to simplify the UI.  
  - Improved the gdb detection function for better reliability and usability.  

### Bug Fixes

- Fixed minor bugs related to window management on macOS.  
- Resolved compatibility issues for older macOS versions.  

## [1.0.7]

### New Features

- The board listing mechanism has been updated to dynamically adapt to the value set in the "Board Visualization Path" configuration.
- Added support for the FRDM-MCXN947 board, with initial functionality without GPIOs.

### Bug Fixes

- Various bug fixes have been implemented to improve overall stability and functionality.

## [1.0.6]

- Quickfix to update to new templates version 

## [1.0.5]

- Fix simulation exit when failure detected
- Add dependencies version detection 
- Fix GDB finder on windows
- Update templates sources

## [1.0.4]

- Better feedback on dependencies installation (terminal and notification)
- Improve installation scripts with error handling
- Add GDB detection for project with C_CPP.default.compilerPath setting
- Block multiple instance of Renode for the same debug session

## [1.0.3]

- Quickfix not fatal error message when installing templates on Windows

## [1.0.2]

- Fix on file installation on Windows
- Remove unused folder from vsix

## [1.0.1]

- Initial release