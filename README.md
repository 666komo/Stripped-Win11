# Stripped Win11 by KOMO

This is my custom Windows 11 Pro N x64 .iso and it is bare metal friendly.
It does NOT include any bloatware, telemetry or data collection (and does not include any browser by default).

![image](https://user-images.githubusercontent.com/118112129/222959638-eb570b1d-5579-440b-a098-33516b86a711.png)

# Download

Download the ISO file from Mega:
https://mega.nz/file/fY1STZ7B#NHVV1I2ehVNyyc5VOiIXr6eSc58wlcXgmMuR7b3Phfo

# Installation

(It is recommended to use Rufus Utility to make bootable USB, because it skips data collection and it is able to make local user without hassle with Microsoft account bypass)

1. Install Windows as normal.
2. Pass the OOBE normally.
3. (Premade local account only) You will problably be prompted after restart to make password, skip this by pressing Enter key.
4. As you can probably see, MS is trying to force some things like Edge in your installation. We are going to get rid of that and install some apps by using CTT WinUtil.
   Simply type in PowerShell (as admin) this command:

   			irm christitus.com/win | iex

5. Install apps of your choice by using this utility.
6. (Recommended!) Go to Updates tab and hit the middle option. (This will make feature updates delay for 2 years, so only updates you will recieve are security updates)
7. I would recommend using some of the tweaks from this utility as long as you know what you are doing. (Only at your own risk!!!)
8. Thats it. Enjoy.

# Credits

All creds to Chris Titus for making this Utility because it is much more simple to operate with stripped down ISOs.
Thanks!

# There is still room for improvement!

There are still some things I want to change or delete. Make sure to watch this repo for updates!
