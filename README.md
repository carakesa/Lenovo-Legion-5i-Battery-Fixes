# Lenovo-Legion-5i-Battery-Fixes
Notes and utilities for fixing the excessive battery drain on Lenovo Legion Laptops due to Intel and ACPI &amp; ASPM settings


 This is applicable only to Intel Legions, AMD variants do not have the ASPM option and battery issue presenton the Intel versions.

Disclaimer: Use at your own risk. No warranty expressed or implied. You're responsible for your own choices, etc.

Beware dangerous options and menus ahead, if you don't know what you're doing.

Unlock the Bios with this tool: https://winraid.level1techs.com/t/tool-lenovo-h20-bios-unlocker-and-locker/38150

**Not sure if this still works on the latest (2022) Bios versions.

    Go to Advanced Settings

    Select ACPI Table/Features Control

    Then ACPI Settings

    Toggle "Native ASPM" to "Enabled"

    Save & Reboot

Apply power plans.

PowerPlans:  There's two folders inside it. One is the 'original' (grabbed them from Lenovo's forums, not sure the exact origin) and then another that has my own tweaks applied. I use them with the Lenovo Legion Toolkit from Github instead of Vantage. So Fn+Q changes power modes, and the Windows Plans change accordingly as well.Vantage is still installed, but disabled. So it doesn't run unless I want it to.

edit: Special thanks to SmokelessCPU for writing the bios unlock utility and talking me through the process!
