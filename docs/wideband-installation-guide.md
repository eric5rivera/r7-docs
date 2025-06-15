# Guide to Installing a MOTOTRBO 20/25 kHz Wide Band Entitlement Key

This guide provides detailed instructions for installing a 20/25 kHz Wide Band Entitlement Key on your MOTOTRBO two-way radio using Customer Programming Software (CPS) Generation 2. Follow these steps carefully to ensure a successful installation and avoid issues with your entitlement key.

## Important Notes
- As of June 2023, Motorola Solutions no longer supports Entitlement ID (EID) key installation on CPS Generation 1 (up to CPS 16, version 828). This guide applies to CPS Gen 2 only.
- The entitlement key is tied to the computer’s hard drive where it is installed. Choose your computer carefully, as the key will not work if the hard drive is replaced or reformatted.
- Ensure you follow all steps precisely to avoid losing the entitlement key due to installation errors.

## Prerequisites
Before beginning, confirm you have:
- A Motorola Solutions account for authentication.
- CPS Gen 2 installed on a desktop computer (tablets or tethered devices are not supported).
- A MOTOTRBO radio connected to the computer via a programming cable.
- A stable internet connection with no VPN active.
- A geographically based IP address in the United States.
- The 20/25 kHz Wide Band Entitlement Key (EID) provided by Motorola Solutions.
- Administrative privileges on your computer.

## Step-by-Step Instructions

### 1. Prepare Your Computer
- **Disable Firewall and Antivirus**: Temporarily turn off all firewall and antivirus software to allow communication with Motorola’s servers. Ensure no ports are blocked on your router.
- **Avoid VPN**: Disconnect any VPN services, as they may interfere with the authentication process.
- **Clean CPS Installation**: Verify that CPS Gen 2 is installed and free of issues. Update to the latest version if necessary.

### 2. Authenticate with Motorola Solutions
- Open a web browser and navigate to `connect.motorolasolutions.com`.
- Log in with your Motorola Solutions account credentials.
- Request a one-time verification code, which will be sent to the email address registered with your account.
- Enter the 6-digit code on the `connect.motorolasolutions.com` page.
- Upon successful entry, you’ll see a confirmation message: “MSI Authentication Portal - Success!”
- Your authentication is valid for 18 hours. Complete the installation within this timeframe, or you’ll need to reauthenticate.

### 3. Connect the Radio
- Connect your MOTOTRBO radio to the computer using the appropriate programming cable.
- Ensure the radio is powered on and properly recognized by CPS Gen 2.

### 4. Install the Entitlement Key in CPS Gen 2
- Open CPS Gen 2 on your computer.
- Navigate to the **Menu** and select **Licenses**.
- Choose **Register Application Features** (do not select Device Features).
- Enter the Entitlement ID (EID) for the 20/25 kHz Wide Band key:
  - To avoid errors, **copy and paste** the EID directly from the source, ensuring no extra spaces or characters are included.
- Click **Register** to submit the EID.
- After registration, click **Activate** to enable the entitlement key.
- The process requires an active internet connection to communicate with Motorola’s servers.

### 5. Verify the Installation
- Go to the **Configuration Menu** in CPS Gen 2 and select **View Feature Sets**.
- Locate the 20/25 kHz Wide Band entitlement field. It should display **PURCHASED**, confirming successful installation.
- If the status is incorrect, double-check the EID and repeat the registration process.

## Troubleshooting Tips
- **Authentication Issues**: If you can’t log in to `connect.motorolasolutions.com`, verify your Motorola Solutions account credentials or request assistance from Motorola’s support team.
- **EID Registration Fails**: Ensure the EID is entered correctly without extra spaces. Confirm your internet connection and that firewall/antivirus settings are disabled.
- **CPS Not Responding**: Restart CPS Gen 2 and reconnect the radio. Ensure you’re using a desktop computer with no VPN active.
- **Key Not Working**: Verify the EID is for CPS Gen 2 and matches your radio model. Contact your Motorola Solutions representative if issues persist.

## Additional Recommendations
- **Backup Your Configuration**: Before making changes, save your radio’s current codeplug to avoid data loss.
- **Document Your EID**: Store the EID in a secure location, as it cannot be recovered if lost.
- **Regular CPS Updates**: Keep CPS Gen 2 updated to ensure compatibility with new features and entitlement keys.
- **Choose a Reliable Computer**: Since the key is tied to the hard drive, use a stable, long-term computer for installation.

## Warnings
- Do not interrupt the registration or activation process, as this may invalidate the EID.
- Avoid installing the key on a computer that may need reformatting or replacement soon.
- Ensure compliance with Motorola Solutions’ licensing terms to avoid issues with key activation.

By following this guide, you can successfully install the 20/25 kHz Wide Band Entitlement Key on your MOTOTRBO radio, enabling wideband functionality for your communication needs.