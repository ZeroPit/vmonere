vmonere
=======================
[![Build Status](https://drone.io/github.com/dcsolvere/vmonere/status.png)](https://drone.io/github.com/dcsolvere/vmonere/latest)

Monitor the virtual machine and host resource usage starting from very minimal duration


##vmonere command line interface
vmonere is a wrapper CLI for virtual machine monitoring and resource usage comparison effectively. Vmonere framework enables user to monitor
the real time guest and host resource usage.

The following are the core functionalities of the vmonere CLI:
```
usage: vmonere [-h] [-v]
               
     {adddomain,removedomain,list,dominfo,hostinfo,removehost,addhost,getip,setsmtpserver,setfrommailaddress,addsupportmail,monitorgraph}
```

##Commands
Option | Specification
------------ | -------------
adddomain | add new domain to vmonere
removedomain | remove the deomain from vmonere
list | list existing domain
dominfo | domain information
hostinfo | host information
getip | get domain ip
monitorgraph | monitor domain usage through vmonere

##Licensing
vmonere is licensed under MIT License. See LICENSE for full license text.
