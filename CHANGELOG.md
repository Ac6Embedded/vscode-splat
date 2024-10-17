# Change Log

All notable changes to the "splat" extension will be documented in this file.

## [1.0.7]

### New Features

- The board listing mechanism has been updated to dynamically adapt to the value set in the "Board Visualization Path" configuration.
- Added support for the FRDM-MCXN947 board, with initial functionality focused on GPIOs.

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