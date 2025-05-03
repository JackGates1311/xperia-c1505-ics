# Xperia C1505 ICS Port (11.1.A.0.68)

This repository ports the **Sony Xperia E Dual (C1605) firmware (11.1.A.0.68)** to the **Xperia E (C1505)**, enabling support for **Android ICS (4.0)** on the Xperia C1505 devices.

## Flashable ZIP File
You can download the latest **flashable ZIP** of the custom ROM from the following link:

- [Download Flashable ZIP](https://mega.nz/folder/1pZ1AQQS#nseOp0sfW6Fgzkpa5fBRXw)

### Important Notes:
1. When you open the link, you'll see two directories. **Please select the directory marked as "stable"** and choose the one with the **latest date** listed on the Mega server for the most up-to-date and stable version.

## How to Flash via CWM Recovery

### Requirements:
1. **Custom Recovery (CWM or TWRP) installed on your Xperia C1505**.
2. **Backup** your current ROM using the recovery menu to avoid any data loss.
3. Ensure your device has at least **50% battery** before proceeding.

### Flashing Instructions:

1. **Boot into Recovery Mode:**
   - Power off your Xperia C1505.
   - Power on your Xperia C1505. 
   - Press the **Volume Up** button multiple times, then power on the device to enter **CWM/TWRP recovery**.

2. **Wipe Data and Cache:**
   - In CWM, go to **Wipe** and select **Wipe data/factory reset**.
   - Then go to **Wipe cache partition** and clear the cache.
   - Then go to **Wipe system partition** and clear the system data.

3. **Flash the ROM:**
   - Transfer **Downloaded ZIP file** to device SD card.
   - Go to **Install ZIP from SD card** and select the downloaded ROM ZIP file.
   - Wait for the flashing process to complete.

5. **Wipe Cache and Dalvik Cache** (again, optional but recommended):
   - Go to **Wipe cache partition** and **Wipe dalvik cache** to prevent boot issues.

6. **Reboot the System:**
   - Once flashing is complete, go to **Reboot system now**.

## Troubleshooting

### 1. **Restart Device**
   If your device is facing issues or is stuck in a boot loop (after few minuttes), the first step is to try a **simple restart**. This often resolves temporary glitches.

   - Power off the device.
   - Wait for a few seconds, and then power it back on.

### 2. **Wipe Cache/Dalvik Cache Again**
   If the device is stuck on boot or booting to recovery, try wiping the **Dalvik cache** and **cache partition** again in CWM or TWRP recovery.

### 3. **Factory Reset**
   If the device continues to have problems, perform a **factory reset** by going to **Wipe** > **Wipe data/factory reset** in recovery mode. Remember that this will erase all data on your device.

### 4. **Reflash the ROM**
   If the ROM was not installed properly, try reflashing the ROM ZIP file again. Sometimes the flashing process might fail due to insufficient space or interruptions.

## Useful Links:

- [Instructions for Bootloader Unlock and Recovery Flash](https://xdaforums.com/t/rom-e-ss-ds-ultimate-cm10-install-guide.2690057)
- [XDA Forum for Xperia E](https://xdaforums.com/t/xperia-e-official-thread-roms-mods-root-ftfs-how-to.2535522/)

---

## Credits

- **Developer:** JackGates1311
- **Base Firmware:** Sony Xperia E Dual (C1605) firmware (11.1.A.0.68)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
