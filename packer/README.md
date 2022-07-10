This folder contains all the necessary files for creating a custom Windows 10 base box, minus the packer.exe executable for building the box. It can be downloaded from the official site: https://www.packer.io/downloads.

The present files are meant to work with an ISO that is present on the host machine or, at least, in an external drive.

Additionally, some of the present variables might need to be configured. Among them, we can highlight the following ones:
- `iso_url`: the path to the ISO (either full or relative)
- `iso_checksum`: the checksum of your ISO
- `autounattend`: the path to the Autounattend.xml/Unattend.xml file, that is, the file for automatically filling the setup form
- `cpus`: the default CPUs for the machine
- `disk_size`: the default total disk size (in MB)
- `memory_size`: the default memory size

Regarding the Autounattend.xml files, several have been provided for different scenarios, though none might adapt to your needs. Check them first and consider if they need any modification performed.

All the files have been crafted taking as a reference the templates and other packer files present in the following repositories:
- https://github.com/jeffskinnerbox/Windows-10-Vagrant-Box
- https://github.com/joefitzgerald/packer-windows