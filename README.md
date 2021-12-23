# Honor-MagicBook-X15-Hackintosh
Honor MagicBook X15 Hackintosh EFI
###About Honor MagicBook X 15
                
Device  | Status
------------- | -------------
| Intel i5-10210U  | Works Perfectly Fine & Power Management ON! |
| Intel UHD  | Works Perfectly Fine! |
| 2x4 2400MHz RAM  | Works Perfectly Fine! |
| 512GB KXG60ZNV512G NVMe  | Works Perfectly Fine! |
| Intel Wireless-AC 9560 160MHz Wi-Fi | Works Perfectly Fine! Using native Wi-Fi. |
| Intel Bluetooth  | Works! **Read Notes!** |
| Battery  | Works Perfectly Fine! **Read Notes!**   |
| I2C HID Touchpad | Works Perfectly Fine!  |
| Realtek ALC256 | Works Perfectly Fine! |

                
###Notes
- Change MLB, ROM etc. after installing macOS by using GenSMBIOS
- You may can't connect to Apple Devices on Bluetooth. Reason is Airportitlwm.kext. I use Airportitlwm.kext for native Wi-Fi. If you want to connect Apple Devices, you have to replace it with itlwm.kext and you have to use Heliport to use Wi-Fi.
- On Windows, when you limit battery percentage on PC Manager it also limits on macOS too. I didn't check time but at %74 battery i run 3 or 3.30 hours i guess, not sure.
- Tested 10.15.7 Catalina and 12.0.1 Monterey. Big Sur should work fine.
- OpenCore version is 0.7.6
