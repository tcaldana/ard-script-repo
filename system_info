#!/bin/bash

# add Get UUID
echo "Please Copy & Paste the following 8 lines and email to osxadmin@smith.edu"
echo ""
echo "----------start copy here----------"
# get Ethernet MAC address
echo "MAC Address:"`/sbin/ifconfig en0 | awk '/ether/ { gsub(":", ""); print $2 }'`
echo ""
# get WiFi-Airport MAC address
echo "Wifi MAC address:"`/sbin/ifconfig en1 | awk '/ether/ { gsub(":", ""); print $2 }'`
echo ""
#networksetup -getcomputername
#networksetup -getcomputername
systemsetup -getcomputername
systemsetup -getlocalsubnetname
#networksetup -gethostname
#networksetup -getbonjourname
#scutil –get ComputerName
defaults read /Library/Preferences/com.apple.RemoteDesktop "Text1"
defaults read /Library/Preferences/com.apple.RemoteDesktop "Text2"
#defaults read /Library/Preferences/com.apple.RemoteDesktop "Text3"
#defaults read /Library/Preferences/com.apple.RemoteDesktop "Text4"
#echo `ioreg -l | grep IOPlatformSerialNumber|awk '{print $4}' | cut -d \" -f 2`
#
system_profiler SPHardwareDataType
#system_profiler SPHardwareDataType | grep "Serial Number"
#system_profiler | grep "r (system)"
#networksetup -getmacaddress en0
#sysctl machdep.cpu.brand_string
#sysctl hw.machine
#sysctl hw.model
#get UUID (ByHost) number
#echo "UUID"
#ioreg -rd1 -c IOPlatformExpertDevice | awk -F= '/(UUID)/ { gsub("[ \"]", ""); print $2 }'
#ioreg -rd1 -c IOPlatformExpertDevice | grep -E '(UUID)'
uname -a #prints all below (-mnrsv)
#uname -m #prints machine hardware name
#uname -n #prints nodename
#uname -p #prints machine processor architecture name
uname -r #prints OS release
uname -s #prints OS name
uname -v #prints OS version
sw_vers -productVersion
echo "----------end copy here----------"
echo ""
echo "Thanks!"
echo ""
exit 0
