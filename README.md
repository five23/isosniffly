# isosniffly

## Command line tool to scan Linux ISOs for post-install exploits and phishing attempts

### The theory: anybody can make a Linux distro, and phishers are all over it.

#### The goal: a GUI application where you simply drag and drop a suspected Linux ISO file; the application will then perform a clean room install using a VM and do a CRC check of all the dependent packages. Finally the distribution will continue to run headlessly for 24 hours with fake/emulated network traffic, in this way hoping to capture the distro when it 'phones home.'
