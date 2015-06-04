# CONNECTING PHYSICAL ANDROID DEVICE TO PC
### Instruction

This instruction is for Windows 7 x64 system.

Device:
1. Enable ADB on Android devices through Settings/About Phone
2. Enable USB debugging on Android Device (elsewhere phone will be not visible for PC)
PC:
3. Check in Android SDK Manager for 'Google USB Driver package'
4. Go to 'Manage Computer' (Computer/Manage)
5. Go to 'other devices' and right click connected device
6. Choose 'Update Driver Software > Browse computer for driver software > Pick up device from list'
7. Select 'Android Composite ADB Interface'
Device:
8. Look on device display / settings for: 'Allow USB debugging', check 'always allow from this computer'.
PC:
9. Go to 'Android SDK/platform-tools', and type 'adb devices'. Device should be listed as 'online'.

Now it should be possible to preview application from Android Studio on Device.