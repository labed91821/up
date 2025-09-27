Open PowerShell
Click the Start Menu, type PowerShell, then open it.

Copy and paste the code below, then press enter.

For Windows 8, 10, 11: 📌
irm https://get.activated.win | iex

If the above is blocked (by ISP/DNS), try this (needs updated Windows 10 or 11):
iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)

For Windows 7 and later:
iex ((New-Object Net.WebClient).DownloadString('https://get.activated.win'))

Script not launching❓Use Method 2.
The activation menu will appear. Choose the green-highlighted options to activate Windows or Office.

Done!
Info
HWID (Digital License) Method to Permanently Activate Windows
Ohook Method to Permanently Activate Office
TSforge Method to Permanently Activate Windows/ESU/Office

KMS38 Method to Activate Windows Till the Year 2038

Online KMS Method to Activate Windows/Office For 180 Days (Lifetime With Renewal Task)

Advanced Activation Troubleshooting

$OEM$ Folders For Preactivation


Fully Open Source and Based on Batch Scripts
Fewer Antivirus Detections
