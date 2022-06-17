<h1 align="center">Retevis RT-24</h1>
<h3 align="center">Configuration images, manuals, general documentation and .csv format frequency configurations.</h3>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/SamuelNetherway460/Retevis-RT24">
  <img src="https://img.shields.io/github/v/release/SamuelNetherway460/Retevis-RT24">
  <img src="https://img.shields.io/github/release-date/SamuelNetherway460/Retevis-RT24">
  <img src="https://img.shields.io/github/issues/SamuelNetherway460/Retevis-RT24">
  <img src="https://img.shields.io/github/downloads/SamuelNetherway460/Retevis-RT24/total">
</p>

## Description
Repository for the Retevis RT-24 digital radio. Contains all documents relating to the radio i.e., specs, manuals, etc. There is only 1 configuration consisting of the  PMR446 (licence free) channels.

## Configuration Status
| Configuration | Last Commit | Latest Release | Release Date |
| :---: | :---: | :---: | :---: |
| PMR446        | ![last-commit](https://img.shields.io/github/last-commit/SamuelNetherway460/Retevis-RT24/Config-PMR446) | ![version](https://img.shields.io/github/v/release/SamuelNetherway460/Retevis-RT24) | ![release-date](https://img.shields.io/github/release-date/SamuelNetherway460/Retevis-RT24) |

## Specs

### General
- Frequency: PMR446
- Channel: 16CH
- Working voltage: 3.7V DC
- Effective Radiated Power: 0.5 watts
- Operating temperature: -10℃~+50℃
- Antenna: Fixed
- Antenna impendence: 50Ω
- Scan: Yes
- VOX: Yes
- Battery Save: Yes
- Bandwidth: 12.5Khz
- CTCSS/DCS: Yes
- Low battery alarm: Yes
- Busy channel lock: Yes
- Working mode: Simplex
- Time-out-Time(TOT): 180s
- English/Chinese Voice: Yes
- Squelch Adjustment: Yes
- Weight(include battery): 193g
- PC program Protection: Yes
- Dimension: 230*62*34mm

### Receiver
- RF sensitivity: ≤0.2μV
- Occupied bandwidth: ≤16KHz
- Selectivity: ≥65dB
- Intermediation: ≥55dB
- Audio power: >500m W
- Audio distortion: ≤5%
- Frequency stability: 5ppm
- Current: 55mA(when standby) | 150mA (when working )
- Audio response: (300-3000Hz):+7~-12.5dB

### Transmitter
- Modulation type: 16K¢F3E
- Spurious radiation: ≤7.5μW
- Modulated noise: <-40dB
- Modulation distortion: <5%
- Frequency stability: 5ppm
- Max. Fr. deviation: ≤±5KHz
- Current: ≤1200mA
- Audio response: (300-3000Hz):+6.5~-14dB\
- Adjacent CH. power: ≥65dB
- Intermediation sensitivity: 8-12mv

## Chirp Radio Programming Guide
1. Download and install [Chirp](https://chirp.danplanet.com/projects/chirp/wiki/Home).
2. Download the source / radio images from the [Releases](https://github.com/SamuelNetherway460/Retevis-RT24/releases) page.
3. Launch Chirp.  
![Chirp Launched](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Chirp%20Launched.png)
4. Connect the Retevis RT24 to the PC using the USB programming cable.
5. Turn on the radio.
6. In the menu bar, click "Radio" and then "Download From Radio".  
![Download From Radio](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Download%20From%20Radio.png)
7. Select the correct Port, Vendor and Model using the drop down boxes.
8. Click "Ok".
9. Click "Ok".  
![Baofeng UV-5R Instructions](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Baofeng%20UV-5R%20Instructions.png)
10. Wait for Chrip to finish cloning the current radio programming.  
![Cloning Programming](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Cloning%20Programming.png)  
    The current programming will then be displayed.  
![Current Programming](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Current%20Programming.png)
11. In the menu bar, click "File", then "Save As".  
![Save Backup](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Save%20Backup.png)
12. Navigate the File Explorer and click "Save" to save a backup of the current radio configuration.  
![Save Radio Image](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Save%20Radio%20Image.png)
13. In the menu bar, click "File", then "Open".  
![Open Radio Image File Menu Bar](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Open%20Radio%20Image%20File%20Menu%20Bar.png)
14. Navigate the File Explorer and select the Radio .img file.  
![Navigate to Radio Image File](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Navigate%20to%20Radio%20Image%20File.png)
15. Click "Open".  
![Open Radio Image File](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Open%20Radio%20Image%20File.png)  
The radio image file should now be loaded.  
![Radio Image File Loaded](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Radio%20Image%20File%20Loaded.png)
16. Custom configurations such as welcome messages should now be made.
17. Once ready to upload to radio, in the menu bar click "Radio", then "Upload To Radio".  
![Upload to Radio](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Upload%20to%20Radio.png)
18. Select the correct Port and click "Ok".  
![Select Port](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Select%20Port.png)
19. Click "Ok" when the instructions are displayed.  
![Baofeng UV-5R Upload Instructions](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Baofeng%20UV-5R%20Upload%20Instructions.png)
21. The radio image file will now be applied to the radio.  
![Uploading to Radio](https://github.com/SamuelNetherway460/Retevis-RT24/blob/Documentation/res/Uploading%20to%20Radio.png)
23. Once the radio light has finished flashing, and the progress bar is complete / progress window has disappeared, the radio can be switched off and disconnected.
24. Radio programming is now complete and the radio is ready to be used.
