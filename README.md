## Create a Private Cloud solution to protect the key revenue generator an E-commerce web Application from failure events


### Solution must:
1) Prepare and handle failure events
2) Mitigate downtime for customers
3) All VMs must be protected against failure

 ## Tasks Completed
 
 1) Deploy and protect three virtual machines for the test environment
 2) Deploy and protect three virtual machines for the production environment
 3) Three virtual machines are Web Server VM (Linux), Application Server (Linux) and Database Server (Microsoft SQL on Windows
 
 
 ## Solution Implemented

 1) 1 vCPU and 4 GB of RAM</li>
 2) Configure NTP using pool.ntp.org</li>
 3) Configure Domain Name Service DNS 8.8.8.8</li>
 4) Create new Storage container Images to store Windows and CentOS virtual disk images</li>
 5) Use naming convention of db-prod for Production VM and db-dev for Testing DB VM</li>
 6) Set replication schedule of 1 hour</li>
 7) Test solution by deleting the production database and restore to ensure application continuity</li>
 
 
![Private Cloud](/project1/images/0-start.jpg)
