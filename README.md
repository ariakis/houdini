# Houdini

A script to bypass a whole bunch of WiFi captive portals (e.g. at hotels, cruise ships etc.)

This is the Houdini of WiFi ;)

# Dependencies

<ul>
  <li>create_ap (https://github.com/oblique/create_ap)</li>
  <li>aircrack-ng suite</li>
  <li>python 3</li>
  <li>bash</li>
</ul>

# Installation

<h3>General installation</h3> 

First install create_ap from github.

Then run this in terminal:

<pre>
<code>git clone https://github.com/ariakis/houdini/
cd houdini
chmod +x houdini
cd modules
chmod +x *
cd ..
</code>
</pre>

# How to use it

Just run houdini with

<code>
  ./houdini {name of access point once internet access is confirmed} {password of access point}
</code>

This will start scanning for associated MAC addresses. Once there are enough clients in airodump-ng, hit ctrl-c and then wait again :)

If it doesn't work at first, maybe try walking around with your device in order to gain more MAC addresses to check.

Please forgive ugly code, and enjoy!
