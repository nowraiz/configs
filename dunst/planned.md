# Planned Features:

### System

- Power Menu
    > Displays 4 notifications with timeout=0, formatted as (<icon>\n<label>), which run, upon clicked, the following commands:
        >> Reboot : systemctl reboot
        >> Shutdown : systemctl poweroff
        >> Lock Screen : betterlockscreen -l dimblur
        >> Logout : ??? (goes back to lightdm login screen)

- Password Manager Notifier
    > Shows a "Password for <site> copied to clipboard" notification.
    > Also shows a "Clipboard will be cleared in 10 seconds" notification.
    > Likely used with a bitwarden script

- OBS Recording Notifier
    > Displays notification for when OBS either starts or stops recording
    > (Will likely require integration of some OBS tool)

- Airplane Mode Notifier (For Laptop)
    > Displays Airplane Mode status upon button toggle 

- Bluetooth Notifier (For Laptop)
    > Displays whether Bluetooth is on, off, or paired

- Music Playing Notifier (in some form or another)
    > Displays "Now Playing" notification containing the title and artist of the song (hopefully art too)
    > Displays play/pause status.

- USB Plugged/Ejected Notifier
    > Might be partially already handled by nemo
