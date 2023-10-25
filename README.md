# binAMD-FX
about AMD FX opencore hackintosh

![alt text](https://github.com/cupecups/binAMD-FX/blob/main/hehe.png)

on mac os ventura you need replace OS DMG from Apple silicon IPSW, and add cryptexfixup.kext to allow mac os booting without AVX 2

# how to??

## for example mac os ventura 13.0 22A5331f

1. mount preboot disk

ls /Volumes/Preboot
(to get uuid disk preboot)


2. ls -l /Volumes/Preboot/E7D7993E-5EEC-4091-97C0-73ECA4A5080C/cryptex1/current/os.dmg
## E7D7993E-5EEC-4091-97C0-73ECA4A5080C (is preboot UUID)

3. cp /Users/cupecups/Desktop/UniversalMac_13.0_22A5331f_Restore

4. cp /Users/cupecups/Desktop/UniversalMac_13.0_22A5331f_Restore/OS.dmg /Volumes/Preboot/E7D7993E-5EEC-4091-97C0-73ECA4A5080C/cryptex1/current/os.dmg

5. ls -l /Volumes/Preboot/E7D7993E-5EEC-4091-97C0-73ECA4A5080C/cryptex1/current/os.dmg

6. ls -l /Volumes/Preboot/E7D7993E-5EEC-4091-97C0-73ECA4A5080C/cryptex1/current/
