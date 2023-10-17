# MQ-Installation-on-Shared-Storage

** IBM MQ Installation on Shared Storage(NFSv4) on RHELv8.8**
      1). OS Prerequisites
              i. create the mqm userid 
              ii. set the 'nofile' values in '/etc/security/limits.conf' file.
              iii. set the 'noproc' values in '/etc/security/limits.d/20-proc*.conf' file
      2). Mount the NFS shared storage on the server and add them in '/etc/fstab' as permanen mount point, Where MQv9.3.0.2 going to install and also ensure that NFSv4 installed on NFS Server. 
      3). Make sure, we have enough disk space for all the '/', '/home', '/opt', '/tmp'.
      4). Copy the MQ Installables on the server.
      5). Install MQ
      
                        
