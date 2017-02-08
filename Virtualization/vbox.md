# Virtualbox notes
Virtualbox is an opensource tool from (originally) Sun Microsystems, and now Oracle.

- [Installation of Vboxtools with CentOS and RHEL](#vboxinstall)

###Installation of VboxTools with CentOS and RHEL 
<a name vboxinstall>

1. Possible Caveats
    - No network connection:
        - use `ip address` to confirm the network interface is mounted and the DHCP client has cought parameters. If not, use `dhclient enp0s3` to do so. In order to make it permanent at the next reboot, edit `/etc/sysconfig/network-scripts/ifcfg-enp0s3` and change `ONBOOT=` value from "no" to "yes"
    - Missing libraries

     

1. Pre requisites

    Centos/RedHatEntrepriseLinux installation with 
        -   epel-release installed 
        -   either 'Devel Group' installed or
            cpp, make, kernel-devel, gcc, perl and their dependances    
    
    
1. Mounting the drive
    
1. Installation and compilation
    