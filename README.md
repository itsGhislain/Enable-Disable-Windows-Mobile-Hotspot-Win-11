# Enable-Disable-Windows-Mobile-Hotspot-Win-11
Registry files to disable and enable the Windows Mobile Hotspot policy on Windows endpoints.

## Purpose

This configuration is intended to reduce the risk of corporate network connectivity being shared with unauthorized or personal devices through Windows Mobile Hotspot.

## Files

- `Disable-Windows-Mobile-Hotspot.reg`  Disables the Windows Mobile Hotspot interface through a Windows policy.
- `Rollback-Windows-Mobile-Hotspot.reg` Removes the applied policy and restores the endpoint to its previous registry state.

## Registry Setting

```text
HKLM\SOFTWARE\Policies\Microsoft\Windows\Network Connections
NC_ShowSharedAccessUI
