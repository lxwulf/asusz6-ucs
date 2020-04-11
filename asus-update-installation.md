# Asus Update Installation

## Preinformation

I assume that you have already rooted your asus zenfone 6 and you know what you are doing. The manual is no guarantee that it works and errors can occur. It is all at your own risk. You need root permissions for the script. The script will delete all google apps which are preinstalled from the stock rom.

List of google apps:

* Google Duo
* Google Photos
* Google Chrome
* Youtube
* Google Drive
* Google Calendar
* Gmail
* Google Play Music
* Google Play Movies & TV

---------------------------------------------------------

## Installation Steps

1. Download Zip from the official ASUS website\
&rightarrow; <https://www.asus.com/us/Phone/ZenFone-6-ZS630KL/HelpDesk_BIOS/>
2. Reboot in recovery mode
   > you can do this with adb `adb reboot recovery`
3. Give your lockscreen pin or password in for decrypt your internal storage
4. go to your folder with all three zips `ASUS-Update-Zip`, `TWRP-Zip` and `Magisk-Zip`
5. Flashing
   &rightarrow; You really need to follow the right installation order!
   1. `ASUS-Update-Zip`
   2. `TWRP-Zip`
   3. `Magisk-Zip`
   4. `Magisk-Zip`
&nbsp;
   > Yes, you need to flash the `Magisk-Zip` twice because of the system structure. Android has a new update system structure with two boot partition slots (A/B). At the first run you just installed it in the activated slot (maybe A) but this is now changed due the update. In the second run magisk is installing in the none active slot (maybe B) which also the update resides.
6. Reboot
7. Remove all apps you didnt want from the google apps package.
