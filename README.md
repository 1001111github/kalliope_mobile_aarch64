# kalliope_mobile_aarch64

Information, links, libraries and resources for building and using Kalliope on aarch64. 
Arch, Manjaro and Mobian all sort of supported, lol.

libttspico* Libraries

The follwoing libraries are not available in the Arch aarch64 repositories.
I did the following on an x86 Arch machine. I have not built debtap on aarch64 

debtap each package. During the build edit each package name and remove the "-git" from it
Additionally, while editing the build file for libttspico0 change aarch64/gnu/linux/glibc to just glibc
pacman -U the files produced by debtap
The library files will be in /usr/lib/aarch64-gnu-linux. Move them to /usr/lib
Or download the Arch packages at www.1001111.com/pinephone

Kalliope.desktop

A desktop icon to send a wakeup signal to Kalliope

phone.yml

A neuron to make phone calls
