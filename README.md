# Pentoo Overlay

This role adds the [pentoo Overlay](https://github.com/pentoo/pentoo-overlay) to the system.
Also adds necessary prerequisites like git. 

**Tasks/ROLE  Remove /var/db/repos/gentoo & gentoo.conf & reset repo to gentoo / and git offten more uodated.. 

<B> BAN HAMMER</B> if you pull alot... from RSYNC Mirrors 

** [ganto.gentoo_portage](https://galaxy.ansible.com/ganto/gentoo_portage)  adds keywords gentoo_portage__profile ie amd64/pentoo/binary  or arm64/dektop
*** other useful automations latter on , while i have my port conf blened.. in github etc , might not be ideal for fresh/bootstraped/docker runneres ie 
[binary-gentoo](https://github.com/hartwork/binary-gentoo) ie cheep vps debian etc this runs dockers 4 you

**Task Add or Ensure pntoo ovrlay is installed 

** and Symlink to pentoo-updater

** add a cronspec to call pentoo-updater ; 6 hours 

this is useful if you have a box just for building pentoo / binhost for custom respins of some packages 
Lets face it I like MMO's and after a while it becomes a real cluster/screw to cajole the RYZEN tower or laptop to 100% updated
#### ARM64 ie IOT som jobs on a 4 gig RPI take DAAAAAAAAAYYYYYS ...  thank god thiers newer faster HW with more ram... 
Sure Kali/Parrot run fine or are "Eassier" sometimes for a mobile pentesting box..  but EAT YOU OWN DOG FOOD as they say.. weres the Gentoo/Pentoo Spirit ? 
However why sit and EMERGE FOO-million packages or change profiles on embeeded HW or arm64 Docker by hand ... Jenkins/Ansible the GOAL POST. 
**
------------------
## License

[GPL-2.0 License](LICENSE)



-------------------
## Author Information
original Template Author 
[Dennis Lamm](https://github.com/expeditioneer/)

Newer Templated Derived [ @necrose99 ](https://github.com/necrose99)
