# Houdini

A script to bypass a whole bunch of WiFi captive portals (e.g. at hotels, cruise ships etc.)

This is the Houdini of WiFi ;)

# Dependencies

<li>bash</li></ul>

# Installation

<h3>General installation</h3> 

It's pretty easy! Just execute the following commands:

<pre><code>git clone https://github.com/ariakis/houdini/
cd houdini
chmod +x install
./install</code></pre>

Thats it!

# How to use it

Just run houdini with

<pre><code>./houdini {wireless interface name}</code></pre>

For example, if your interface was called <code>wlan0</code>, then you would run

<pre><code>./houdini wlan0</code></pre>

This will start scanning for associated MAC addresses. Once there are enough clients in airodump-ng, hit ctrl-c and then each mac collected will be checked. If one of the has internet access, you can either start a hotspot on your device (if you're nice and want to share) or just keep it all for yourself :)

If it doesn't work at first, maybe try walking around with your device in order to gain more MAC addresses to check.

Please forgive ugly code, and enjoy!

- ariakis
