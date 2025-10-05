# EFS (Elastic File System)



##### Used for sharing files between multiple instances that can be accessed simultaneously in the same region.



1. create two instances with same key and same security group in same region.
2. add port nfs 2049 in the security group.
3. create EFS and select the security group in the network section inside the EFS.
4. Attach and mount the EFS through DNS run the nfs client in both instances terminal => instances are connected now. 
5. now u have access to files in both servers.
6. if we create a file prior connection establishment the file will be deleted from the directory.



