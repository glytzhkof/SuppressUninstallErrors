# SuppressUninstallErrors
How to suppress custom actions from running via a custom msiexec.exe command line switch.

- Build project (debug mode).
- Run: "1. Install.cmd" and run to install MSI.
- Run: "2. Uninstall_Normal.cmd" and run to uninstall MSI. There will be a message box.
- Run: "1. Install.cmd" to re-install MSI.
- Run: "3. Uninstall_SuppressError.cmd" to uninstall MSI with no custom actions running, hence no message box.

This is supposed to be a generic approach to suppress custom actions from running that cause problems during
installation, upgrade or uninstallation. It is just a mock-up.

