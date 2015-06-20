BIND DNS-Server - Basic Configuration
=====================================

### Introduction

Here you can find basic configuration files for the BIND DNS server.


### Commands

COMMON
* Check Configuration: sudo named-checkconf -z
* Restart BIND       : sudo service bind9 restart

DNS LOOKUP
* Forward: dig +noall +answer @192.168.2.2 server.berry.local
* Reverse: dig +noall +answer -x @127.0.0.1 192.168.2.2
* Windows: nslookup 192.168.2.2

BIND AUTO-START
* sudo update-rc.d bind9 defaults
* sudo update-rc.d bind9 remove



### Links

* [BIND DNS-Server unter Raspbian installieren und einrichten (Howto Anleitung)](http://www.blogging-it.com/bind-dns-server-unter-raspbian-installieren-und-einrichten-howto-anleitung/raspberry-pi/betriebssysteme-und-software.html)


### License
The license is committed to the repository in the project folder as `LICENSE.txt`.
Please see the `LICENSE.txt` file for full informations.


----------------------------------

Markus Eschenbach  
http://www.blogging-it.com
