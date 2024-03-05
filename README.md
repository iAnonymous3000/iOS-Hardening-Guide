# The Ultimate iOS Hardening Guide

## Table of Contents
1. [Introduction](#introduction)
2. [Choosing the Right Device: Device Selection and Biometric Security](#choosing-the-right-device-device-selection-and-biometric-security)
3. [Purchasing iOS Devices Anonymously](#purchasing-ios-devices-anonymously)
4. [Initial Setup and Apple ID: Best Practices](#initial-setup-and-apple-id-best-practices)
5. [Passcodes and Encryption](#passcodes-and-encryption)
6. [Enable Find My](#enable-find-my)
7. [Enable Automatic Updates](#enable-automatic-updates)
8. [Two-Factor Authentication](#two-factor-authentication)
9. [Optimizing Tracking and Location Services](#optimizing-tracking-and-location-services)
10. [Advanced Location Services and Tracking: Disabling for Privacy](#advanced-location-services-and-tracking-disabling-for-privacy)
11. [Biometric ID Considerations and Legal Implications](#biometric-id-considerations-and-legal-implications)
12. [Enhancing Lock Screen Security](#enhancing-lock-screen-security)
13. [Disable Control Center when locked](#disable-control-center-when-locked)
14. [Enable Stolen Device Protection](#enable-stolen-device-protection)
15. [Managing App Permissions](#managing-app-permissions)
16. [Disabling Tracking and Ad Tracking](#disabling-tracking-and-ad-tracking)
17. [Using VPN and Firewall for Enhanced Security](#using-vpn-and-firewall-for-enhanced-security)
18. [VPN and DNS Configurations for Enhanced Privacy](#vpn-and-dns-configurations-for-enhanced-privacy)
19. [Privacy-Focused Alternatives to Apple Apps](#privacy-focused-alternatives-to-apple-apps)
20. [Secure Messaging Apps](#secure-messaging-apps)
21. [Privacy-focused Browsers](#privacy-focused-browsers)
22. [Secure Email Providers](#secure-email-providers)
23. [App Sandboxing](#app-sandboxing)
24. [Secure Wireless Connections](#secure-wireless-connections)
25. [Threat Modeling](#threat-modeling)
26. [Security Auditing Tools](#security-auditing-tools)
27. [Siri Privacy Settings](#siri-privacy-settings)
28. [Securing iCloud Settings](#securing-icloud-settings)
29. [Safari Privacy and Security Settings](#safari-privacy-and-security-settings)
30. [Detailed Privacy Settings Adjustments](#detailed-privacy-settings-adjustments)
31. [Staying Secure with iOS Updates](#staying-secure-with-ios-updates)
32. [Physical Security Measures for Your Device](#physical-security-measures-for-your-device)
33. [The Risks of Jailbreaking](#the-risks-of-jailbreaking)
34. [Secure Backups](#secure-backups)
35. [Alternatives to Data Transfer and iCloud](#alternatives-to-data-transfer-and-icloud)
36. [Screen Time & Restrictions for Added Security](#screen-time--restrictions-for-added-security)
37. [Optimizing System Services for Privacy](#optimizing-system-services-for-privacy)
38. [Understanding and Using Lockdown Mode](#understanding-and-using-lockdown-mode)
39. [Learn to use Emergency SOS](#learn-to-use-emergency-sos)
40. [Enable USB Restricted Mode](#enable-usb-restricted-mode)
41. [Managing Emergency Alerts and Addressing False Privacy Warnings](#managing-emergency-alerts-and-addressing-false-privacy-warnings)
42. [Regular Updates and Revisions](#regular-updates-and-revisions)
43. [External Resources for Further Learning](#external-resources-for-further-learning)
44. [Feedback and Contributions](#feedback-and-contributions)

## Introduction
Welcome to the Ultimate iOS Hardening Guide! This guide is designed to enhance the security and privacy of iPhones and iPads for users at all levels, from beginners to advanced. We explore and explain Apple's security features, their limitations, and provide alternative solutions for robust privacy and security within the Apple ecosystem.

## Choosing the Right Device: Device Selection and Biometric Security
Select devices with features that meet your security needs. Understand the legal and security implications of biometric features like Touch ID and Face ID. Consider upgrading to a device with an A12 CPU or higher for improved security features and faster updates.

## Purchasing iOS Devices Anonymously
For anonymity, purchase iOS devices with cash at physical stores and avoid any setup or registration offered in-store.

## Initial Setup and Apple ID: Best Practices
Start with a new or factory reset device. Set up your Apple ID away from personal networks and use non-personal information for the account. During the initial setup, disable all connectivity options like Wi-Fi, Bluetooth, and cellular data.

## Passcodes and Encryption
- **Strong Passcode**: Opt for at least a 6-digit passcode, or better yet, an alphanumeric one for higher security.
- **Biometric Security**: Use Face ID or Touch ID with an understanding of the legal and privacy implications.
- **Advanced Options**: Turn off 'Simple Passcode' for more complex passcode options.
- **Data Protection**: Always enable data protection and keychain protection in your settings.

## Enable Find My
Enable Find My under `Settings → [Your Name] → Find My` to locate, lock, or erase your device remotely if it's lost or stolen.

## Enable Automatic Updates
Turn on automatic updates under `Settings → General → Software Update → Automatic Updates` to ensure your device always has the latest security patches.

## Two-Factor Authentication
Two-factor authentication adds a critical layer of security. It combines something you know (your password) and something you have (your device). Activate it under `Settings → [Your name] → Password & Security → Two-factor authentication`.

## Optimizing Tracking and Location Services
Privacy is key. Regularly check `Settings → Privacy & Security → Tracking` and toggle off 'Allow Apps to Request to Track'. Manage app permissions for location access under `Settings → Location Services`.

## Advanced Location Services and Tracking: Disabling for Privacy
Post-setup, regularly verify location and tracking settings, especially after updates. Consider disabling non-essential location services.

## Biometric ID Considerations and Legal Implications
Biometrics like Touch ID and Face ID are convenient but have legal implications. In some areas, using a passcode offers more legal protection. Consider scenarios where biometrics might be less secure than a passcode.

## Enhancing Lock Screen Security
Your lock screen can be a vulnerability. Limit accessible features from `Settings → Touch ID/Face ID & Passcode`. This helps protect personal information even when your phone is locked.

## Disable Control Center when locked
Disable access to Control Center when your device is locked under `Settings → Touch ID/Face ID & Passcode` to prevent unauthorized changes to settings.

## Enable Stolen Device Protection
Stolen Device Protection adds a layer of security when your iPhone is away from familiar locations, such as home or work, and helps protect your accounts and personal information in case your iPhone is ever stolen.

To turn on Stolen Device Protection, you must use two-factor authentication for your Apple ID and set up or enable the following on your iPhone: a device passcode; Face ID or Touch ID; and Significant Locations* (Location Services). You also need to have Find My turned on, and you can't turn it off while Stolen Device Protection is enabled.

When Stolen Device Protection is enabled, some features and actions have additional security requirements when your iPhone is away from familiar locations:

- **Face ID or Touch ID biometric authentication**: Some actions such as accessing stored passwords and credit cards require a single biometric authentication with Face ID or Touch ID — with no passcode alternative or fallback — so that only you can access these features.
- **Security Delay**: Some security actions such as changing your Apple ID password also require you to wait an hour and then perform a second Face ID or Touch ID authentication.

You can turn on Stolen Device Protection in Settings:

1. Go to Settings, then tap Face ID & Passcode.
2. Enter your device passcode.
3. Tap Stolen Device Protection, then turn Stolen Device Protection on or off.

If you'd like your iPhone to enforce the additional Stolen Device Protection security measures regardless of its location, choose "Always" under Require Security Delay. By default, the additional security measures are required only when your iPhone is away from familiar locations.

*Significant Locations is an option within Location Services: Settings > Privacy & Security > Location Services > System Services > Significant Locations.

## Managing App Permissions
Review app permissions regularly in your device settings, paying special attention to access to the microphone, camera, and location services.

## Disabling Tracking and Ad Tracking
To limit ad tracking, navigate to `Settings → Privacy & Security → Apple Advertising` and disable 'Personalized Ads'.

## Using VPN and Firewall for Enhanced Security
Protect against Wi-Fi hacking and mask your IP address with a reliable VPN. This is crucial for maintaining privacy on public networks.

## VPN and DNS Configurations for Enhanced Privacy
Choose a privacy-respecting VPN provider and configure it not to log your data. Use DNS services for additional filtering and privacy.

## Privacy-Focused Alternatives to Apple Apps
Consider using privacy-centric alternatives to native Apple apps, such as:
- Safari → Brave (see iOS browser comparison [here](https://privacytests.org/ios))
- iMessage → Signal
- iCloud → Proton Drive
- iCloud Keychain → Bitwarden
- Apple Calendar → Proton Calendar
- iCloud Private Relay (VPN) -> Proton VPN
- Apple Mail -> Proton Mail
- Apple Notes -> Standard Notes
- iCloud Photos -> ente

Each alternative is selected for its strong focus on user privacy and security features, like end-to-end encryption.

## Secure Messaging Apps
In addition to Signal, consider other secure messaging apps like Threema, Wire, or Wickr Me, which offer end-to-end encryption and additional privacy features.

## Privacy-focused Browsers
Besides Brave, other privacy-centric browsers worth considering include Firefox Focus and DuckDuckGo Privacy Browser, which have built-in tracking protection and ad-blocking features.

## Secure Email Providers
Apart from ProtonMail, other secure email providers like Tutanota or Mailfence offer end-to-end encryption and enhanced privacy features.

## App Sandboxing
iOS's app sandboxing contributes to the overall security of the device by isolating apps from each other and limiting their access to system resources.

## Secure Wireless Connections
Secure your wireless connections by using WPA3 encryption for Wi-Fi networks and avoiding unsecured public Wi-Fi hotspots.

## Threat Modeling
Assess your individual security needs based on your specific situation and potential threats you may face.

## Security Auditing Tools
Consider using security auditing tools like [iVerify](https://www.iverify.io) to check your device for security vulnerabilities and misconfigurations.

## Siri Privacy Settings
Manage Siri's access under `Settings → Siri & Search` for better privacy. Consider disabling 'Listen for "Hey Siri"' to minimize data sharing.

## Securing iCloud Settings
Regularly review your iCloud settings. Enable two-factor authentication and use end-to-end encryption where possible.

## Safari Privacy and Security Settings
Enhance your privacy in Safari by enabling Fraudulent Website Warnings and managing cookies effectively. Consider disabling JavaScript for added security.

## Detailed Privacy Settings Adjustments
Limit Siri's access and turn off notifications for sensitive apps. In Safari, use private browsing and disable suggestions—opt-out of analytics data sharing for enhanced privacy.

## Staying Secure with iOS Updates
Regularly update your iOS to the latest version to benefit from the newest security patches. Keep your apps updated as well.

## Physical Security Measures for Your Device
Never leave your device unattended in public places. Use features like Find My iPhone for theft recovery. Use a protective case, screen protector, and keep the device away from extreme temperatures.

## The Risks of Jailbreaking
Jailbreaking exposes your device to additional security risks. It's generally advised to avoid jailbreaking for maintaining device security.

## Secure Backups
Always use encrypted backups and regularly test backup restores to ensure data integrity.

## Alternatives to Data Transfer and iCloud
Explore secure cloud services like Proton Drive and prefer physical data transfers (like USB) over wireless ones for sensitive data.

## Screen Time & Restrictions for Added Security
Use Screen Time to enforce content and privacy restrictions, preventing unauthorized changes to your device settings. This is particularly useful if someone learns your device passcode.

## Optimizing System Services for Privacy
Fine-tune `Settings → Privacy & Security → Location Services → System Services`. Turn off non-essential services like `Location-Based Apple Ads` and `Significant Locations` to minimize location data collection.

## Understanding and Using Lockdown Mode
Lockdown Mode is designed for users at high risk of targeted cyber attacks. It limits certain functionalities to reduce the device's attack surface. Activate it under `Settings → Privacy & Security → Lockdown Mode`, but be aware that it will restrict many standard features. Familiarize yourself with Lockdown Mode and its implications.

## Learn to use Emergency SOS
Know how to activate Emergency SOS (press and hold the side button and either volume button) to quickly call for help and alert your emergency contacts.

## Enable USB Restricted Mode
Enable USB Accessories under `Settings → Touch ID/Face ID & Passcode` to prevent USB accessories from connecting when your device has been locked for over an hour.

## Managing Emergency Alerts and Addressing False Privacy Warnings
Understand that some government alerts may bypass your settings. Verify your settings if iOS flags a privacy warning due to DNS changes. Often, these can be dismissed for secure DNS setups.

## Regular Updates and Revisions

### Staying Current with iOS Developments
- **Evolving Security Landscape**: The realm of iOS security and privacy is continually evolving. New updates from Apple often introduce changes in features, settings, and security protocols.
- **Commitment to Relevance**: We are committed to keeping this guide updated with the latest information and best practices. This ensures that the advice and strategies provided here remain relevant and effective.
- **Recommendation for Readers**: We encourage readers to revisit this guide periodically. Staying informed about the latest updates and revisions will help you maintain the highest level of security and privacy on your iOS devices.
- **Community Input**: Your feedback and contributions are invaluable in keeping this guide comprehensive and up-to-date. Please feel free to suggest updates or new information that might be beneficial to include.

### Keeping Up with iOS Updates
- **Checking for iOS Updates**: Regularly check for and install the latest iOS updates on your device. These updates often contain crucial security patches and feature enhancements.
- **Reviewing Guide Updates**: After updating your iOS, revisit this guide to ensure that your security settings and practices align with any new changes introduced by the update.

## External Resources for Further Learning
- [Into the Cyberverse](https://alternativeto.net/list/34604/cyberverse) - The ultimate list of apps/services for better Security, Privacy and Anonymity
- [Personal Safety User Guide for Apple Devices](https://help.apple.com/pdf/personal-safety/en_US/personal-safety-user-guide.pdf): Apple's official guide is a comprehensive resource for anyone concerned about or experiencing technology-enabled abuse, stalking, or harassment. It offers practical steps to sever digital ties and utilize the built-in safety features of Apple devices.

## Feedback and Contributions
We welcome your suggestions and feedback. Please feel free to open an issue on this GitHub repository or submit a pull request with your contributions.
