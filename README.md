# Houdini

A script to bypass WiFi captive portals (e.g. at hotels, cruise ships etc.)

# Requirements (kali install and update code):

<code>
apt install hostapd aircrack-ng python3
</code>

# Installation instructions

Run this code in terminal:
<code>
  git clone https://github.com/ariakis/houdini/ && cd houdini
  chmod +x houdini
  cd modules && chmod +x *
  cd ..
</code>

# How to use it

Then just run houdini with
<code>
  ./houdini {name of access point once internet access is confirmed} {password of access point}
</code>
and then wait. Once there are enough client mac addresses in airodump-ng, hit ctrl-c and then wait again :)

If it doesn't work at first, maybe try walking around with your device in order to gain more MAC addresses to check.

Please forgive ugly code, and enjoy!

# Credits

Ariakis
Aircrack
Hostapd
