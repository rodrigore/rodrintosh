### Fix autoreconnect bluetooth pair devices

``` bash
sudo defaults write /Library/Preferences/com.apple.Bluetooth.plist  FastConnectReadyDevices -array-add  '01-29-b5-19-4a-81'
```
