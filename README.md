# oldbetter
Old bettercap
Update:
This tutorial is up-to-date for last kali version 2020.1

Donwgrade instructions

If you have chosen the legacy deb package, follow this instructions to install it:

Requirements: wget

    Uninstall latest 2.x bettercap package
        ~# apt remove bettercap
    Install the ruby dependencies
        ~# apt install ruby-packetfu ruby-colorize ruby-net-dns ruby-em-proxy
    Install dpkg -i ruby-network-interface_0.0.1-0kali1+b1_amd64.deb
    Install dpkg -i ruby-rubydns_1.0.3-0kali1_all.deb
    Install dpkg -i bettercap_1.6.2-0parrot1_all.deb
    
    

Additionally, you may want as optional to mark the package as "hold" to avoid its update in order to keep the downgraded compatible version:

~# apt-mark hold bettercap
Important note. This downgrade method was tested only on Kali and Parrot Security Linux.
