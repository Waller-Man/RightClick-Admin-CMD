# RightClick-Admin-CMD

This repository provides a `.reg` file to add a **"Open CMD here as Administrator"** option to the right-click menu in Windows Explorer. This makes it quick and easy to launch a Command Prompt with elevated privileges directly from any directory, drive, or background space.

## 📁 Features

- Adds right-click option for:
  - Folders
  - Drives
  - Directory background
- Executes a PowerShell command to launch an elevated CMD with working directory set to the selected path.

## 📄 File

- `open-cmd-admin.reg`  
  Merges into `HKEY_CLASSES_ROOT` to inject context menu entries.

## ⚠️ Usage

1. Double-click the `.reg` file to merge into registry.
2. Confirm the UAC and registry prompts.
3. Right-click any folder, drive or Explorer background to see the new menu item.
4. Click to open CMD as Admin directly.

## 🛑 Disclaimer

Use with caution. Always back up your registry before applying any custom modifications.

## 🙌 Author

Created by [YourName]  
Inspired by system administration needs and convenience.
