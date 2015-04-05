# macgen -  OSX and Linux
Mac Address Generator for OSX and Linux


Must run as root for interface changes

    sudo ./macgen.py
  
# auto-assigning new mac to interface

    What interface?
    Interface: en0
    
    en0: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
      ether 54:26:96:70:3e:d7 
      inet6 fe80::5626:96ff:fe70:3ed7%en0 prefixlen 64 scopeid 0x4 
      inet 192.168.1.17 netmask 0xffffff00 broadcast 192.168.1.255
      nd6 options=1<PERFORMNUD>
      media: autoselect
      status: active
      
      
      ---------SYSTEM INFORMATION---------
      Time: 13:3:11 5/4/2015
      Kernel:   Darwin
      Local Machine Name: MacbookPro.local
      en0 MAC Address: 
      ether 54:26:96:70:3e:d7 
      ------------------------------------
      
      How many MAC addresses do you want to generate?
      Input number: 1
      
      
      54:26:96:7b:be:0c
      
      
      Assign 54:26:96:7b:be:0c to interface en0 ?
      Y or N:
      

#generating mac-address list
    What interface?
    Interface: en0
    
    en0: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
      ether 54:26:96:70:3e:d7 
      inet6 fe80::5626:96ff:fe70:3ed7%en0 prefixlen 64 scopeid 0x4 
      inet 192.168.1.17 netmask 0xffffff00 broadcast 192.168.1.255
      nd6 options=1<PERFORMNUD>
      media: autoselect
      status: active
      
      
      ---------SYSTEM INFORMATION---------
      Time: 13:3:11 5/4/2015
      Kernel:   Darwin
      Local Machine Name: MacbookPro.local
      en0 MAC Address: 
      ether 54:26:96:70:3e:d7 
      ------------------------------------
      
      How many MAC addresses do you want to generate?
      Input number: 3
      54:26:96:43:d1:33
      54:26:96:55:39:89
      54:26:96:5d:97:81
