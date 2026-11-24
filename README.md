# FTflow — SV5BYP Edition

FTflow r171 is the full-package continuation of FTFlow: portable Windows x64 amateur-radio digital-mode software based on MSHV, with the existing weak-signal modes plus RTTY Bot and CW Bot.

## Download and run

1. Open [FTflow r171](https://github.com/sv5byp/FTFlow/releases/tag/r171).
2. Under **Assets**, download **FTflow-SV5BYP-r171-Windows-x64-portable.zip**.
3. Extract the **complete ZIP** into a new folder on disk or USB and run **FTFlow.exe**.

No setup or installer is required. Keep every included file/subfolder together. Configure your callsign, soundcards and radio/PTT connection for the computer you use.

## Existing users

Migration to r171 requires the **full ZIP**; the older two-program-file updater cannot deliver the new clock helper, CW model and automation runtime. Close the old instance and retain a backup of settings and ADIF logs. **Do not replace only an EXE.** Legacy releases and their updater channel remain available; this full-package release is downloaded manually.

## RTTY and CW

Editable F1-F12 macros, DSP, automatic/manual CW speed, adjustable receive AFC, optional multichannel receive text and selected-station automatic QSO. Unknown callsigns are shown as unknown. A callsign click selects one station without transmitting. Optional Slots/RTTY Bot/CW Bot access levels remain as provided by the application.

## Optional clock synchronization

Automatic synchronization defaults **OFF** in a new profile. The user enables it from **Features > Clock synchronization > Automatic every10minutes**, and the choice is saved. The complete package includes the updated **FTFlow-Time.exe**. First activation may ask once for Windows permission. The optional feature requires Windows10/11 with built-in Windows PowerShell5.1 and displays before/after measurements, sources and verification status.

## Credits and source

Based on MSHV by Hrisimir Hristov, LZ2HV. Original credits, map attribution and GNU GPL license are retained. DeepCW by VE3NEA is MIT-licensed; its license/attribution are included. Source accompanies each release. See the release notes for validation scope and operating requirements.
