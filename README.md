# 4th Gen HDMI Fuser Setup Guide

## Introduction

Welcome to the setup guide for the Dichen (Baan8K) 4th generation HDMI Fuser. This repository contains instructions for setting up and using the HDMI Fuser device, designed to facilitate DMA cheating by fusing HDMI signals from multiple sources. This repository also contains the software you need.
[I WILL BE ADDING A VIDEO GUIDE "SOON"]

## Ports

- **[HDMI]:** Connect to your main monitor.
- **[HDMI 1]:** Connect to your main PC output.
- **[HDMI 2]:** Connect to your radar/2nd PC output.
- **[USB Type C]:** For updating firmware and EDID.
- **[DC12V]:** Power (12V2A by default).

## Indicators

- **[D1]:** Power indicator (Constant on = normal).
- **[D2]:** Fusing on/off (LED on = fusing).
- **[H2]:** HDMI2 status (off means no input).
- **[H1]:** HDMI1 status (off means no input).

## Buttons

- **[Power]:** Power on/off.
- **[K1]:** Press to cycle between different resolutions.
- **[K2]:** Press to decrease the fuse "strength" level.
- **[K3]:** Press to set the fuse "strength" level to default.
- **[K4]:** Press to toggle fusing on/off.

## First Time Setup Guide

### Step 1: Get your monitor EDID and inject to fuser

1. Connect your main monitor using an HDMI 2.0 or HDMI 2.1 cable to your PC. (The values are different compared to if you use a DP cable)
2. Switch your monitor input to the HDMI signal from your PC and remember to change your refresh rate.
3. Download and run 'MonitorAssetManager Setup'.
4. Press launch once the install is finished.
5. Select the first display (displayed as 'real time'). (Check the name and make to make sure, if you have two monitors)
6. Go to File on the top left and save as a .bin file.

### Step 2: Inject the .bin File to Your Fuser

1. Connect the HDMI Fuser to your main PC using the USB Type C cable.
2. Plug in the power cable and turn on the HDMI Fuser.
3. You should see a new COM device in your device manager.
4. Open EDID.exe.
5. Select the correct COM port.
6. Select the resolution you want to inject your EDID.
7. Press the second option on the line under resolutions
8. Load configurations from the .bin file. (next to the blank box)
9. Press to inject (top right button); expect a black screen during injection.
10. Once injected, disconnect the USB Type C cable and connect all HDMI cables properly.

## Final Setup Steps

1. Make sure you have correct display on both main and 2nd PC.
2. Adjust resolutions and refresh rates in display settings. (to match the resolution of your main monitor)
3. Set the display mode to 'Extend' on the 2nd PC (default is 'Duplicate'). (You can press Win+P to change this)

This concludes the setup guide for your 4th generation HDMI Fuser. Enjoy your enhanced gaming experience!
