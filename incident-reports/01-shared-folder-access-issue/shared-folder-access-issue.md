# Shared Folder Access Issue

## Incident
User was unable to access shared folder on Windows workstation.

## Symptoms
- Access denied when attempting to open shared folder
- Shared folder existed on system

## Troubleshooting Steps
1. Verified folder existed
2. Verified sharing was enabled
3. Checked folder permissions
4. Identified missing user permissions

## Root Cause
The user account had been removed from the folder permission list.

## Resolution
Re-added user permissions and restored Full Control access.

## Skills Practiced
- Windows file sharing
- Permission troubleshooting
- User access restoration
