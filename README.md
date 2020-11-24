# kalliope_mobile_aarch64

Information, links, libraries and resources for building and using Kalliope on aarch64. 
Arch, Manjaro and Mobian all sort of supported, lol.

<a href="https://forum.pine64.org/showthread.php?tid=12055">Build instructions for Mobian, Arch and Manjaro</a>

<b>libttspico* Libraries</b>
The following libraries are not available in the Arch aarch64 repositories.
I did the following on an x86 Arch machine. I have not built debtap on aarch64 

debtap each package. During the build edit each package name and remove the "-git" from it
Additionally, while editing the build file for libttspico0 change aarch64/gnu/linux/glibc to just glibc
pacman -U the files produced by debtap
The library files will be in /usr/lib/aarch64-gnu-linux. Move them to /usr/lib

<b>Kalliope.desktop</b>
A desktop icon to send a wakeup signal to Kalliope

<b>phone.yml</b>
A neuron to make phone calls

<b>51-gps.rules</b>
A PolicyKit ruleset that allows the GeoClue service to access the GPS

<b>lightdm-gtk-greeter.conf</b>
Configuration file for Lightdm Display Manager with on-screen keybord
