## Cloud Provider:
  * Amazon
## Instances:
  * 34.248.85.125 - ec2-34-248-85-125.eu-west-1.compute.amazonaws.com
  * 34.249.143.145 - ec2-34-249-143-145.eu-west-1.compute.amazonaws.com
  * 34.252.98.137 - ec2-34-252-98-137.eu-west-1.compute.amazonaws.com
  * 52.210.133.119 - ec2-52-210-133-119.eu-west-1.compute.amazonaws.com
  * 52.215.87.122 - ec2-52-215-87-122.eu-west-1.compute.amazonaws.com
## Linux Release:  
* [ec2-user@ip-172-31-25-246 ~]$ cat /proc/version

* Linux version 3.10.0-514.21.2.el7.x86_64 (mockbuild@x86-037.build.eng.bos.redhat.com) (gcc version 4.8.5 20150623 (Red Hat 4.8.5-11) (GCC) ) #1 SMP Sun May 28 17:08:21 EDT 2017

## File System Capacity:  

* [ec2-user@ip-172-31-17-209 ~]$ df -h

    * Filesystem      Size  Used Avail Use% Mounted on
    * /dev/xvda2       70G  1.9G   69G   3% /

## Yum repolist enabled:  
* [root@ip-172-31-25-246 ec2-user]# yum repolist enabled
* Loaded plugins: amazon-id, rhui-lb, search-disabled-repos
* repo id                                                         repo name                                                                      status
* !rhui-REGION-client-config-server-7/x86_64                      Red Hat Update Infrastructure 2.0 Client Configuration Server 7                     6
* !rhui-REGION-rhel-server-releases/7Server/x86_64                Red Hat Enterprise Linux Server 7 (RPMs)                                       14,473
* !rhui-REGION-rhel-server-rh-common/7Server/x86_64               Red Hat Enterprise Linux Server 7 RH Common (RPMs)                                228
* repolist: 14,707

## List /etc/passwd: 

* [root@ip-172-31-29-94 ec2-user]# cat /etc/passwd | egrep 'saturn|haley'
* saturn:x:2800:2800::/home/saturn:/bin/bash
* haley:x:2900:2900::/home/haley:/bin/bash

## List /etc/group: 
* [root@ip-172-31-29-94 ec2-user]# cat /etc/group | egrep 'comets|planets'
* comets:x:2901:haley
* planets:x:2902:saturn




