# Kali Nethunter for Xiaomi Redmi Note 3 Pro
![Kali NetHunter](https://raw.githubusercontent.com/offensive-security/kali-nethunter/master/images/nethunter-git-logo.png)

## A project by Offensive Security
The Kali Linux NetHunter project is the first Open Source Android penetration testing platform, created as a joint effort between the Kali community member “BinkyBear” and Offensive Security. NetHunter supports Wireless 802.11 frame injection, one-click MANA Evil Access Point setups, HID keyboard (Teensy like attacks), as well as BadUSB MITM attacks – and is built upon the sturdy shoulders of the Kali Linux distribution and toolsets.
<ul>
<li>802.11 Wireless Injection and AP mode support with multiple supported USB wifi cards.</li>
<li>Capable of running USB HID Keyboard attacks, much like the Teensy device is able to do.</li>
<li>Supports BadUSB MITM attacks. Plug in your Nethunter to a victim PC, and have your traffic relayed though it.</li>
<li>Contains a full Kali Linux toolset, with many tools available via a simple menu system.</li>
<li>USB Y-cable support in the Nethunter kernel – use your OTG cable while still charging your Nexus device!</li>
<li>Software Defined Radio support. Use Kali Nethunter with your HackRF to explore the wireless radio space.</li>
</ul>

# Documentation and Attack Descriptions
Attack descriptions as well as some documentation to get you started with the installation and setup of Kali NetHunter can be found at https://github.com/offensive-security/kali-nethunter/wiki.

# Is Kali NetHunter an Android ROM?

Kali Linux NetHunter is **not** a ROM but is meant to be installed over an existing stock/factory image of Android. It can also be installed over some Cyanogenmod based ROMs depending on device support. It is heavily based on using custom kernels and only supports a select number of devices.
We're relying on you, the community, to port your devices for the full Kali NetHunter experience.

# Devices supported:
Xiaomi Redmi Note 3 Pro [Snapdragon Version] (kenzo)

# DOWNLOAD
-[Full CM13 with custom kernel integrated]: https://www.dropbox.com/s/j218tos8iv8pf2y/kali-cm-13.0-20161114-UNOFFICIAL-kenzo.zip<br>
-[Patch for system to Add firmware etc]: https://www.dropbox.com/s/oz9bsqd2oqgqvqh/additional-system-patch-nethunter-kenzo-marshmallow-20161114_134739.zip<br>
-[Kalifs full]: https://www.dropbox.com/s/l7lf6uk52wi3iit/nethunter-kenzo-marshmallow-kalifs-full-20161114_134636.zip<br>

# INSTALLATION INSTRUCTIONS
1) WIPE DATA, CACHE, DALVIK CACHE<br>
2) Flash kali-cm13.0<br>
3) Flash OpenGapps for arm64<br>
4) Reboot<br>
After first boot return into recovery mode and :<br>
1) Flash additional-system-patch<br>
2) Flash nethunter-kenzo-marshmallow-kalifs-full<br>
3) Reboot<br>

# Conclusion
I'm not responsible for bricked devices, dead SD cards

# XDA
