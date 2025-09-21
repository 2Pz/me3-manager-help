# Troubleshooting

Use this guide to resolve common issues with ME3 Manager and Mod Engine 3.

## Quick checks

- Make sure you followed [Getting Started](getting-started.md) completely.
- Verify ME3 Manager and Mod Engine 3 are both on the latest stable versions.

## Mods are not loading

- Confirm the mod is listed and enabled in the Manager.
- Open the game via the Manager (not directly via steam).
- Try with only one mod enabled to rule out conflicts.
- Review the in-app console/terminal for ME3 output and errors.

## “ME3 not installed” or “ME3 not detected”

- Re-run the ME3 installation from [Getting Started](getting-started.md).

=== ":material-microsoft-windows: Windows"

    - Prefer the official Stable installer
    - Alternatively, let the Manager handle install using the Custom Portable option

=== ":material-linux: Linux / Steam Deck"

    - Use the Stable installation script
    - Ensure the Manager has permission to access the ME3 folder

## Permission or antivirus issues

- :material-microsoft-windows: Windows: allow the Manager and ME3 through Windows Defender/AV if they were quarantined.
- Avoid running as Administrator unless specifically required for a test.
- Keep the app installed in a user-writable location

## Gathering information for support

- Copy any error messages shown in the Manager’s console/terminal.
- Note your OS, game, and Manager version.
- List active mods and the order you enabled them.
