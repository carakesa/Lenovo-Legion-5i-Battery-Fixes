# Lenovo-Legion-5i-Battery-Fixes


===================================================
* READ:   These instructions were written based on this https://github.com/SmokelessCPUv2/LenovoH2O-Unlocker bios unlocker.

* Latest BIOS and 2022 Model are not supported by the H2O Unlocker and instead require something like:  https://github.com/SmokelessCPUv2/SmokelessRuntimeEFIPatcher#lenovo-bios-unlock
 
* Please follow the directions for the SmokelessRuntimeEFIPatcher for newer Legion's and udpated BIOS releases
===================================================



Notes and utilities for fixing the excessive battery drain on Lenovo Legion Laptops due to Intel and ACPI &amp; ASPM settings


 This is applicable only to Intel Legions, AMD variants do not have the ASPM option and battery issue presenton the Intel versions.

Disclaimer: Use at your own risk. No warranty expressed or implied. You're responsible for your own choices, etc.

Beware dangerous options and menus ahead, if you don't know what you're doing.

Unlock the Bios with this tool: 

https://winraid.level1techs.com/t/tool-lenovo-h20-bios-unlocker-and-locker/38150

**Not sure if this still works on the latest (2022) Bios versions.

    Go to Advanced Settings

    Select ACPI Table/Features Control

    Then ACPI Settings

    Toggle "Native ASPM" to "Enabled"

    Save & Reboot

Windows Power Plans:  https://github.com/carakesa/Lenovo-Legion-5i-Battery-Fixes/blob/main/PowerPlan_INTEL_legion_18Jan22.zip


There's two folders in the zip. One is the 'original' (grabbed them from Lenovo's forums, not sure the exact origin) and then another that has my own tweaks applied. 

I use them with the Lenovo Legion Toolkit from Github ( https://github.com/BartoszCichecki/LenovoLegionToolkit ) instead of Vantage. This will allow Fn+Q changes to the power modes to adjust the Windows Plans change accordingly.

Personally, I keep Vantage installed, but disabled. So it doesn't run unless I want it to.

edit: Special thanks to the other contributors for writing the bios unlock utility, Legion Toolkit, and talking me through the process
