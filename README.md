
# WARNING!  THIS IS STILL IN TESTING!  PLEASE DONT USE!

*_I am still testing and writing this code.  It likely doesn't work fully and isn't fully documented._*

# [CarHacking.Tools](CarHacking.Tools)

[CarHacking.Tools](CarHacking.Tools) is a scripts collection of scripts to help jump start car research (and hacking?). All the scripts are designed to work on [Ubuntu 18.04](ubuntu.com).


# Included Tools

The following tools are installed and configured automatically: 

* Can-Utils
  * Website: https://github.com/linux-can/can-utils
* Canbus-Utils
  * Website: https://github.com/digitalbond/canbus-utils
* Cantact-App
  * Website: https://github.com/linklayer/cantact-app/
* Caringcaribou
  * Website: https://github.com/CaringCaribou/caringcaribou
* GNUradio
  * Website: https://www.gnuradio.org/
* c0f
  * Website: https://github.com/zombieCraig/c0f
* ICSim
  * Website: https://github.com/zombieCraig/ICSim
* KatyOBD
  * Website: https://github.com/YangChuan80/KatyOBD
* Kayak
  * Website: http://kayak.2codeornot2code.org/
* OBD-Monitor
  * Website: https://github.com/dchad/OBD-Monitor
* PyOBD
  * Website: http://www.obdtester.com/pyobd
  * Note: Need To Fix Install.
* SavvyCAN
  * Website: http://www.savvycan.com/
* Scantool
  * Website: https://www.scantool.net/
* Socketcand
  * Website: https://github.com/dschanoeh/socketcand
* UDSim
  * Website: https://github.com/zombieCraig/UDSim
* Wireshark
  * Website: https://www.wireshark.org/

# Install

## Virtual Machine

An OVA is avalibile on [CarHacking.Tools](CarHacking.Tools) to download.

[Alpha OVA](https://carhacking.tools/install/alpha/alpha180718/CarHackingDesktopAlpha.ova)

## Full Desktop

To Install The Full Desktop:
```
Git Clone
cd CarHackingTools
sudo chmod +x *.sh
./workstationinstall.sh
```

## Tools Only

To Install Only The Tools:
```
Git Clone
cd CarHackingTools
sudo chmod +x *.sh
./toolinstall.sh
```

## Warning
I likely don't know what I am doing and this could be done faster, better and simpler some other way. These scripts could also break your car (seriously) and make you cry.
