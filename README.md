# Hack59 HHKB Keymap

This repository provides a `.json` and a `.layout` file that allow you to configure the Hack59 keyboard with an HHKB-style layout using [VIA Online](https://www.usevia.app/).

---

## Requirements
- A browser with WebHID support (for example: Chrome, Edge, Brave).  
  Note: Firefox is not supported.  
- Hack59 keyboard connected via USB.

---

## Instructions

1. Open [VIA Online](https://www.usevia.app/).

2. Connect the keyboard:  
   - If the Hack59 is not detected on the start page:  
     - Open the **Settings** tab.  
     - Enable **"Show Design Tab"**.  
     - Switch to the new **Design** tab.  
     - Select **V2** and upload the `.json` file from this repository (`EPOMAKER_Hack59.json`).  
     - The Hack59 should now be available for connection.

3. Apply the layout:  
   - Open the **Configure** tab.  
   - In the left menu, select the third icon (Save/Load).  
   - Upload the `.layout` file from this repository (`epomaker_hack59_HHKB.layout`).  

4. After uploading, the Hack59 will be configured with the HHKB layout.

---

## Files
- `EPOMAKER_Hack59.json`: Board definition for VIA.  
- `epomaker_hack59_HHKB.layout`: HHKB keymap for Hack59.  

---

## Notes
- Make sure to use a browser with WebHID support.  
- If the keyboard is not detected, try another USB cable or port.
