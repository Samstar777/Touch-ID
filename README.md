# Touch-ID / Biometrics

This Touch ID Extension Attribute identifies whether your Mac hardware supports Touch ID. If Touch ID is not supported, the attribute will indicate 'Unsupported.' On the other hand, if your Mac hardware does support Touch ID, the attribute will provide a list of User IDs enrolled for Touch ID unlock or indicate that Touch ID is not enabled for unlock.

# Touch ID User List Script

This script, written in zsh, lists all users enrolled in Touch ID with "unlock with fingerprint" enabled on macOS.

## Usage

Simply upload the xml on your Jamf Pro instance to check for active Touch ID users.

## Prerequisites

Make sure you have the necessary permissions to upload the xml, and ensure that your system supports Touch ID.

## Compatibility

The script detects the macOS version and adjusts its behavior accordingly.

For macOS 14: Uses Biometrics functionality
For macOS 13 and earlier: Uses Touch ID functionality

## Installation

Simply upload Touch-ID xml to Jamf Pro > Computer Management > Extension Attribute.


## Author

Salim M. Ukani AKA Samstar777

## License

This project is licensed under the MIT License - see the LICENSE file for details.


