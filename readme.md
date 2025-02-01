Arjienx Custom DNSTT Termux Script v.0.1.7x

requirement:                  
termux app from this github link.

for android 7, 8, 9, 10, 11, 12, 13, 14, 15.                  
https://github.com/termux/termux-app/releases/download/v0.119.0-beta.1/termux-app_v0.119.0-beta.1+apt-android-7-github-debug_universal.apk

for android 5, 6.                  
https://github.com/termux/termux-app/releases/download/v0.119.0-beta.1/termux-app_v0.119.0-beta.1+apt-android-5-github-debug_universal.apk

open termux app, execute code. allow access (storage permission).
```
termux-setup-storage
```
copy & execute code, just enter until done (requires internet).
```
curl --insecure -o install https://raw.githubusercontent.com/arjienx/termux/main/install && chmod +x install && ./install
```

```
'Installation Completed' will appear in the logs, If it's installed correctly.
for any unexpected errors, please capture and send full screenshots of the logs.

Usage:

type 'menu' and press enter to access the script interface.
to add a DNS or Nameserver, input the corresponding number from the menu and press enter.
to return to the 'main menu' simply press Enter.
in the main menu, pressing enter will immediately start query testing.
to stop DNS testing, press ctrl + c.


HTTP Custom:

tap the three dots in the top left corner of HTTP Custom, then go to 'Proxified Apps'.
enable both 'Proxified Apps' and 'Bypass Mode'.
ensure the 'Termux' app is selected to exclude it from the vpn tunnel.
run the 'Termux' app in the background to enhance stability.

enable/disable airplane mode, then test internet connection.
```

