# This Is Part Of The BT Wi-Fi Autologin Services Also Available For

 - Windows
 - OpenWRT 
 - Android (& Chromebook)
 
 ### More information available here:
 https://github.com/aidanmacgregor/BTWi-Fi_Autologin_-_OpenWrt_Linux_ChromeOS_Android_Macrodroid_Windows.EXE

# ![48 terminal-icon copy](https://user-images.githubusercontent.com/11254983/164985283-235c64c3-415e-4cb1-8ce9-8967c23add8e.png) Linux Bash Script
 
This is a shell script that is used to automatically log in to a BT Wi-Fi network. The script is designed to run continuously in the background, and it checks for internet connectivity by pinging a set of specified websites. If the internet is not available, the script will send an HTTP POST request to a specific URL with the user's login credentials in order to log in to the BT Wi-Fi network. The script defines several variables that are used to configure the behavior of the script, including the ACCOUNTTYPE, USERNAME, and PASSWORD variables, which are used to specify the user's account type and login credentials. The script then enters an infinite loop, in which it continually checks for internet connectivity by pinging a set of websites. If the internet is not available, the script will send an HTTP POST request to one of three URLs depending on the value of the ACCOUNTTYPE variable. The script also includes several optional features, such as logging the login attempts to a file and limiting the size of the log file.

# Features:

 - Simple Bash Script To Stay Online
 - Log File
 - Limit Log Size
    
## Terminal Running
![WSL2](https://user-images.githubusercontent.com/11254983/173451001-cce58162-7475-4322-9744-fb842ce40209.JPG)

## Linux Download
[Login Service](https://github.com/aidanmacgregor/BTWi-Fi_Autologin_-_Linux/releases)
