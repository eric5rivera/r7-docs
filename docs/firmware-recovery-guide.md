# Guide to Recovering Firmware on Your MOTOTRBO Two-Way Radio

This guide provides step-by-step instructions for performing a firmware recovery on your MOTOTRBO two-way radio. Firmware recovery resets the radio to its factory default settings, allowing you to reprogram it from scratch. Follow these steps carefully to ensure a successful recovery without damaging your device.

## Prerequisites
Before starting, ensure you have the following:
- A backup of your current codeplug file (the radio's configuration data).
- A fully charged battery or a stable, uninterrupted power supply.
- Access to the MOTOTRBO Customer Programming Software (CPS).
- Administrative privileges on your computer.
- The appropriate firmware version for your radio model.

## Step-by-Step Instructions

### 1. Back Up Your Codeplug
- Save your current codeplug file to a secure location, such as an external drive or cloud storage.
- Verify the backup to ensure it’s complete and accessible in case you need to restore it later.

### 2. Download the Correct Firmware
- Log in to the official MOTOTRBO portal (or your organization’s software management system).
- Navigate to the software or entitlements section.
- Search for the firmware version compatible with your radio model.
- Download the firmware file to your computer.

### 3. Install the Firmware
- Locate the downloaded firmware file.
- For optimal compatibility, right-click the file and select **Run as Administrator** to initiate the installation.
  - Depending on your Windows version, double-clicking may also work, but running as an administrator is recommended.
- Allow the installation to complete without interruption.

### 4. Prepare the Radio
- Connect your MOTOTRBO radio to your computer using the appropriate programming cable.
- Ensure the radio has a fully charged battery or is connected to a reliable power source to prevent interruptions during the recovery process.

### 5. Launch CPS and Initiate Recovery
- Open the MOTOTRBO Customer Programming Software (CPS).
- Navigate to the **Device** menu and select **Recover**.
- The CPS will scan for available firmware packages and display them in a table.
- From the dropdown menu, select the firmware version you downloaded.

### 6. Perform the Firmware Recovery
- Click to proceed with the recovery process.
- **Do not disconnect the radio, close the CPS, or interrupt the computer** during the recovery, as this could render the radio inoperable (commonly known as "bricking").
- If a prompt about requiring a tuner appears, you can safely ignore it, as it’s not necessary for this process.
- Wait for the CPS to display a **"Recovery Successful"** message, which may take a few minutes.

### 7. Verify and Program
- After a successful recovery, your radio will be reset to its factory default codeplug.
- You can now use the CPS to program the radio with your desired settings or restore a previously saved codeplug.

## Important Notes
- **Avoid Interruptions**: Ensure a stable power source and do not interfere with the computer or radio during the recovery process to prevent potential damage.
- **Firmware Compatibility**: Always verify that the firmware version matches your radio model to avoid compatibility issues.
- **Regular Backups**: Make it a habit to back up your codeplug before performing any firmware updates or recoveries.
- **Troubleshooting**: If the recovery fails, double-check the firmware version, cable connections, and power supply. Retry the process, ensuring all steps are followed precisely.

## Additional Tips
- Keep your CPS software updated to the latest version for improved compatibility and features.
- If you’re unsure about any step, consult the official MOTOTRBO documentation or contact technical support for your radio model.
- Consider testing the radio after recovery to ensure it functions correctly before reprogramming.

This guide is designed to help you safely recover your MOTOTRBO radio’s firmware. By following these steps, you can reset your device and prepare it for fresh programming, ensuring optimal performance.