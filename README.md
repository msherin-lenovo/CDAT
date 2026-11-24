**Step 1 – Extract the files**
Unzip the attached CDATv330.zip to any folder (e.g. your Desktop). Keep all files together — the "Templates" folder must stay in the same folder as the tool.

**Step 2 – Run the tool (choose one method)**

**Option A** – Easiest (recommended):

Open the folder and double-click CDATv330.exe.
Click Yes if prompted.
In the window that appears, type 1 and press Enter (collects all data).
Wait for it to finish.

**Option B** – PowerShell script:

Press the Windows key, type PowerShell, right-click it and choose Run as Administrator → Yes.

Type this and press Enter (type A if prompted):
"set-executionpolicy unrestricted"

Go to the folder where you extracted the files:
cd "C:\path\to\the\folder"
Run the tool:
.\CDATv330.ps1
Type 1 and press Enter (collects all data), then wait for it to finish.

**Step 3 – Send us the result**
A .zip file will be created in that same folder, named like:
Lenovo-CDAT330-All-1-[serial]-[model]-[date].zip
