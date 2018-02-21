# Remotely Approving UAMDM
This is a POC of how to remotely enable UAMDM on machines running 10.13.2 or higher. It requires having remote access to a machine (via VNC or ARD) and having administrator privileges on the machine as well.

The basic setup steps needed are:

1. Open **System Preferences** --> **Security & Privacy** --> **Privacy**
2. Click the **Accessibility** option
3. Add, using the plus (+) button, the app **Script Editor** to allow it extra privileges over your machine
4. Close **System Preferences**
5. Run the downloaded **"Remotely Approve UAMDM.scpt"** from this repo
6. Your machine should now have an approved UAMDM status

This script will handle the following for you now:

1. Open **System Preferences**
2. Click the **Profiles** prefPane
3. Find the **Device Manager** profile
4. Click the **Approve** button(s)

![UAMDM Gif](./UAMDM.gif)
