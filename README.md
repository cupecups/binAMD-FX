# binAMD-FX
about AMD FX opencore hackintosh

![alt text](
https://github.com/cupecups/binAMD-FX/blob/c198d1c31083b7741350dcf04ebe9f87355af614/Screenshot%202023-01-29%20at%2016.24.12.png)

![alt text](https://github.com/cupecups/binAMD-FX/blob/main/hehe.png)

on mac os ventura you need replace OS DMG from Apple silicon IPSW, and add cryptexfixup.kext to allow mac os booting without AVX 2

##how to?
F7A915A0-7E42-4517-AEC1-2BE63C1E4A47

mount preboot disk

ls /Volumes/Preboot
(to get uuid disk preboot)


ls -l /Volumes/Preboot/E7D7993E-5EEC-4091-97C0-73ECA4A5080C/cryptex1/current/os.dmg


cp /Users/cupecups/Desktop/UniversalMac_13.0_22A5331f_Restore

cp /Users/cupecups/Desktop/UniversalMac_13.0_22A5331f_Restore/OS.dmg /Volumes/Preboot/E7D7993E-5EEC-4091-97C0-73ECA4A5080C/cryptex1/current/os.dmg

ls -l /Volumes/Preboot/E7D7993E-5EEC-4091-97C0-73ECA4A5080C/cryptex1/current/os.dmg

ls -l /Volumes/Preboot/E7D7993E-5EEC-4091-97C0-73ECA4A5080C/cryptex1/current/
