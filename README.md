# Remotely Approving UAMDM
This is a POC of how to remotely enable UAMDM on machines running 10.13.2 or higher. It requires having remote access to a machine (via VNC or ARD) and having administrator privileges on the machine as well.

The basic steps to do this are:

1. Open **System Preferences** --> **Security & Privacy**
2. Click the **Accessibility** option
3. Add, using the plus (+) button, the app **Script Editor** to allow it extra privileges over your machine
4. Open **System Preferences** --> **Profiles** preference pane
5. Select the **Device Manager** profile
5. Run the downloaded "Remotely Approve UAMDM.scpt" from this repo
6. Your machine should now have an approved UAMDM status

![UAMDM Gif](./UAMDM.gif)
