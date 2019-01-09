# LE-8.2.5-WG
Libreelec compiled with wireguard support

This contains a compiled version of Libreelec 8.2.5 for a Raspberry 2 or 3 with support for Wireguard.

WireGuard® is an extremely simple yet fast and modern VPN that utilizes state-of-the-art cryptography. It aims to be faster, simpler, leaner, and 
more useful than IPsec, while avoiding the massive headache. It intends to be considerably more performant than OpenVPN. WireGuard is designed as 
a general purpose VPN for running on embedded interfaces and super computers alike, fit for many different circumstances. Initially released for 
the Linux kernel, it is now cross-platform and widely deployable. It is currently under heavy development, but already it might be regarded as 
the most secure, easiest to use, and simplest VPN solution in the industry. See <a href="https://www.wireguard.com/" target="_blank">the 
wireguard website</a>.

LibreELEC is a lightweight ‘Just enough OS’ Linux distribution purpose-built for Kodi on current and popular mediacentre hardware. We forked from 
the OpenELEC project in March 2016 when it became clear the original project could no longer operate effectively with one person in charge, and 
with that one person refusing to communicate or listen to other team members (untested changes in public releases was a frequent source of 
friction). Since forking our team has grown, but retains a strong focus on stable development. We also believe passionately in the long-term 
value of collaboration and upstreaming code instead of hoarding patches, and we participate actively with other Open Source projects and the 
ecosystem of regular and drive-by contributors that surround us. LibreELEC remains Kodi oriented but we too have been forked to provide the 
stable JeOS base for Plex Embedded, Lakka, and a number of single-purpose IoT and maker projects. See <a href="https://libreelec.tv/" 
target="_blank">the Libreelec website</a>.

Because a raspberry is a device with a CPU which cannot deliver hi-speed throughput using (for example) OpenVPN I have re-compiled Libreelec with 
Wireguard support in it.

<u>Note!</u> The wg-quick binary is not available, you should bring up your tunnel using the wg tool as the manual on the Wireguard website. 

## Speed

Sending a 100mb file through the tunnel, both ends connected to the internet using a fibre optic link:

100MB.bin           100%   95MB  10.6MB/s   00:09
