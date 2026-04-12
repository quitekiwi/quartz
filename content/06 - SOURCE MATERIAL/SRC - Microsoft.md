# SRC — Microsoft

**Folder:** 05 - SOURCE MATERIAL
**Supporting:** [[Microsoft]]

---

## Windows Telemetry — Official Documentation

**Microsoft — Data Collection Summary**
https://www.microsoft.com/en-us/privacy/data-collection-windows
Official categorisation of Required 
vs Optional telemetry. Confirms 
Required data collected regardless 
of user preference.

**Microsoft Learn — Configure Diagnostic Data**
https://learn.microsoft.com/en-us/windows/privacy/configure-windows-diagnostic-data-in-your-organization
Technical documentation of telemetry 
system. Enterprise controls documented. 
Consumer limitations acknowledged.

**DiagTrack Service**
Connected User Experiences and Telemetry.
Documented in Microsoft technical 
architecture papers.
Note: Security researchers confirm 
the Diagnostic Data Viewer shows 
a fraction of what DiagTrack 
actually transmits.

---

## Microsoft Recall

**Original Announcement — May 2024**
Microsoft Build Conference, May 20, 2024.
Feature described: screenshot every 
few seconds, AI processing, 
searchable database.

**TotalRecall — Alexander Hagenah**
Tool demonstrating unencrypted 
database vulnerability.
GitHub: github.com/xaitax/TotalRecall
Confirmed: database stored in 
plaintext, extractable.

**Forrester — Jeff Pollard Quote**
"A built-in keylogger and screenshotter 
that perfectly captures everything 
you do on the machine is a 
tremendous privacy nightmare."
Via: Computerworld
https://www.computerworld.com/article/2123524/windows-recall-a-privacy-nightmare.html

**UK Information Commissioner's Office**
Formal letter to Microsoft 
regarding Recall safeguards — 
May 2024. Confirmed by ICO.

**Recall Relaunch — April 2025**
Kevin Beaumont analysis — DoublePulsar:
https://doublepulsar.com/microsoft-recall-on-copilot-pc-testing-the-security-and-privacy-implications-ddb296093b6c
Independent security researcher 
review of updated version. 
Confirmed improvements. 
Noted remaining concerns 
around biometric access requirements.

**Signal Response to Recall**
Signal implemented black screen 
on Windows screenshots — 
only available defence against 
Recall capture.
Via: Proton Blog
https://proton.me/blog/disable-windows-recall

**Expert Quote — Digital Watch Observatory**
"The system undermines the security 
of encrypted apps like WhatsApp 
and Signal by storing anything 
shown on screen, even if it 
was meant to disappear."
https://dig.watch/updates/microsoft-recall-raises-privacy-alarm-again

---

## How To Disable Recall

**Proton — Step by Step Guide**
https://proton.me/blog/disable-windows-recall
Settings → Privacy & Security → 
Recall & Snapshots → 
Toggle off Save Snapshots → 
Delete Snapshots

**Group Policy (Enterprise):**
User Configuration → 
Administrative Templates → 
Windows Components → Windows AI → 
Allow Recall to be enabled → Disabled

---

## Privacy Tools

**O&O ShutUp10++**
https://www.oo-software.com/en/shutup10
Free. No installation required. 
Granular Windows privacy settings 
beyond what Settings provides.

**WPD — Windows Privacy Dashboard**
Open source telemetry control tool.

---

## Still To Source

- [ ] Full scope of DiagTrack 
  data transmission — 
  independent network level 
  analysis needed #investigate
- [ ] Microsoft / OpenAI data 
  retention policies for 
  Azure AI interactions — 
  not publicly disclosed #investigate
- [ ] LinkedIn cross-referencing 
  with Microsoft account data — 
  confirm technical architecture #investigate
- [ ] Recall rollout timeline 
  beyond Copilot+ PCs — 
  monitor for updates #investigate
