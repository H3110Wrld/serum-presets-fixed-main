# Serum Preset Version Fixer

A simple Python script that fixes version compatibility issues for Serum presets.

## How to Use

1. **Download** the latest version of this tool as a ZIP archive and extract it to any convenient location.

2. **Right-click** inside the extracted folder (where you see `fix_version.py`) and select **"Open in Terminal"** (or "Open in PowerShell" / "Open Terminal").

3. **Prepare your presets:**
   - Copy your preset folder (or multiple folders) into the `presets` folder inside this tool.
   - If your preset pack has the `.Serum Pack` extension:
     - Rename it to `.rar`
     - Extract the archive into the `presets` folder.
   - Note: You can also place the `Samples` and `Tables` folders directly into your main Serum preset library.

4. In the opened terminal window, run the following command:

   ```bash
   python fix_version.py
