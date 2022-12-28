# Video_Terminal
VT100 like terminal build from a cheap microprocessor kit (Infineon PSoC5LP)

This project describes a video terminal build around the CY8CKIT-059 from Cypress (now Infineon).
The BOM for this project is minimal:
- Old PS/2 keyboard, not with USB, but a 5-pin or 6-pin connector.
- A screen for the display. This can be an old monitor or a brand new LCD screen, but it needs a VGA input.
- The Cypress microprocessor kit
- A 16MHz quartz kristal
- 5 resistors for the video display
- Connectors for the keyboard and for the VGA display

To program the microprocessor, you will have to download PSoC Creator from the Infineon website (for free).
The kit can be plugged in to a USB slot in your computer to upload the program.

Open the archive from within PSoC creator and Build the data, then flash it in the microprocessor.

For more information, see Hackster.io

https://www.hackster.io/Pieter56/video-terminal-4891f0
