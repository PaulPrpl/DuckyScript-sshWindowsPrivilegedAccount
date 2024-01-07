# DuckyScript-sshWindowsPrivilegedAccount

This is a simple Ducky Script that installs an OpenSSH server on the tested machine and then creates a privileged user.

You can edit the password and username directly in the script; the defaults are "WinUpdate" and "changeme."

Powershell is required on the targeted machine. This script only works on Windows and has been tested on Windows 10.

Please note that the group 'Administrators' can vary depending on the machine's locale. The opened terminal won't close after the test.

You'll need a BadUSB device (like Rubber Ducky, CactuS WHID HID, FlipperZero), and an unlocked session with admin privileges must be present on the targeted machine.

**Use this script only for testing or demonstration purposes. You are solely responsible for your actions.**
