# VivobookS14-X411UF-hackintosh-mojave
Mac OS Mojave in X411UF model of ASUS Vivobook S14

What's working:
-Audio (Voodoo HDA kext with DSDT patches)
-Display (Setting brightness to lowest makes the screen black, but I can live with that hahahah)
-GPU - Fully Hardware accelerated Intel Integrated Graphics (UHD 620)
-HDMI
-ACPI battery percentage
-USB ports - Inject USB kext works OOTB
-Touchpad (I guess but I'm not sure if the gestures are right, not familiar with Mac OS touchpad gestures yet.
Everything else.

Not Working:
-Discrete GPU - NVIDIA Geforce MX130 isn't supported in Mac OS, no DSDT or SSDT patch can make this work.
-Fingerprint Sensor (This one actually works, but I disabled it via kext and DSDT patch because it doesn't register any fingerprint. *maybe apple uses different fingerprint algorithm*.
-Wi-Fi and Bluetooth - lols RTL8822BE isn't supported at all. And has the same fate as my Discrete GPU.
