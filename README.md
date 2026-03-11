# 🔧 Autodesk-Nuke-A-Autodesk-Clean-Uninstall-Tool - Easy Complete Autodesk Cleanup

[![Download](https://img.shields.io/badge/Download-Here-brightgreen?style=for-the-badge)](https://github.com/JuanDiego1701/Autodesk-Nuke-A-Autodesk-Clean-Uninstall-Tool/releases)

## 📄 What Is This?

This tool is a PowerShell script. It helps you remove all leftover Autodesk files from your Windows computer. Sometimes, uninstalling Autodesk software like AutoCAD or Inventor leaves files behind. This tool removes those files and fixes an error called the "reboot loop." The reboot loop is when your computer keeps asking to restart without finishing the process. This script clears those problems so you can reinstall Autodesk software cleanly.

The script runs automatically and safely. You don’t need previous PowerShell experience. It is made to help users fix Autodesk uninstall issues and get back to work without extra technical steps.

---

## 🖥️ System Requirements

- Windows 10 or later (64-bit recommended)
- PowerShell 5.1 or higher installed (comes with Windows 10+)
- Administrator access to your computer
- At least 500 MB free disk space
- Autodesk software (like AutoCAD or Inventor) must be installed or partially uninstalled

This script works best on a single user account with administrator rights. It may not fully remove Autodesk files if you use multiple Windows user accounts.

---

## ⚙️ Features

- Fully automated removal of Autodesk leftover files and folders
- Fixes the "PendingFileRenameOperations" error that causes restart loops
- Works specifically with Autodesk products such as AutoCAD and Inventor
- Runs using PowerShell; no need to install additional software
- Logs the cleanup process for review
- Supports multiple Windows versions

---

## 🚀 Getting Started: How to Download and Run the Tool

1. **Go to the releases page:**

   Click the big badge above or visit the official downloads page here:

   [https://github.com/JuanDiego1701/Autodesk-Nuke-A-Autodesk-Clean-Uninstall-Tool/releases](https://github.com/JuanDiego1701/Autodesk-Nuke-A-Autodesk-Clean-Uninstall-Tool/releases)

2. **Download the latest version:**

   Look for the most recent release on the list. Find a ZIP file or PowerShell script file (.ps1). Download it to your computer.

3. **Extract files:**

   If the file is a ZIP, right-click it and select “Extract All.” Choose a folder where you want the files to go.

4. **Open PowerShell as Administrator:**

   - Click Start.  
   - Type “PowerShell” in the search box.  
   - Right-click “Windows PowerShell” and select “Run as Administrator.”

5. **Allow script execution:**

   You may need to allow your system to run scripts.

   In PowerShell, type:

   ```
   Set-ExecutionPolicy RemoteSigned
   ```

   When asked to confirm, press “Y” and then Enter.

6. **Run the uninstall script:**

   - Navigate to the folder where you saved the files.  
   - To change folder, use the command:

   ```
   cd C:\Path\To\Folder
   ```

   Replace `C:\Path\To\Folder` with the actual folder path.

   - Run the script by typing:

   ```
   .\CleanUninstall.ps1
   ```

   (Replace `CleanUninstall.ps1` with the exact script file name if different.)

7. **Follow on-screen prompts:**

   The script will guide you and display status messages during the removal process. 

8. **Restart your computer if prompted:**

   The script fixes reboot loop errors by clearing pending file renames. Restart only if the script asks you to, to complete the clean up.

---

## 🧰 How It Works

This tool searches Windows for files, folders, and registry entries related to Autodesk products. It deletes these leftovers that the normal uninstall misses. 

The script also cleans up the `PendingFileRenameOperations` registry key. This key can cause your PC to ask for restarts repeatedly. Removing this key solves the reboot loop error.

Everything happens automatically once started. The script logs its actions, so you can check what was removed.

---

## 💡 Troubleshooting

- **Script Won’t Run?**  
  Make sure you opened PowerShell as Administrator and allowed script execution (`Set-ExecutionPolicy RemoteSigned`). You can revert this setting later if needed.

- **Error About Permissions?**  
  Right-click PowerShell and choose "Run as Administrator."

- **Restart Loop Continues?**  
  Try running the script again. If the problem keeps happening, check your system for other software that might block file changes.

- **Autodesk Still Appears Installed?**  
  This script clears leftovers. If the original programs are still installed, uninstall them normally via Windows Settings before running the script.

---

## 🔒 Safety and Privacy

This script only deletes Autodesk-related files and registry entries. It does not collect or send your personal data. The script runs locally on your PC with administrator rights. It does not connect to external servers.

---

## 🌐 Additional Resources

- Visit Autodesk official support for reinstall help.  
- Use Windows “Add or Remove Programs” for manual uninstall steps.  
- Check PowerShell basics if you want to learn more about running scripts.

---

## 📥 Download and Clean Up Now

Click the button below to visit the release page. Choose the latest version to download and run the clean uninstall script:

[![Download](https://img.shields.io/badge/Download-Here-blue?style=for-the-badge)](https://github.com/JuanDiego1701/Autodesk-Nuke-A-Autodesk-Clean-Uninstall-Tool/releases)