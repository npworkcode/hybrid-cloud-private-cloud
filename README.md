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
 
 # Nutanix Prism - Central Plane of glass for Private, Public and Hybrid Cloud Management
 ![Nutanix Prism Central](/project1/images/2021-02-01-prism_central-2.jpg)
# Add NTP Server
![Use Nutanix Prism to Add an NTP Server](/project1/images/2021-02-01_054934-ntp_server_1.jpg)

# NTP Server Added using Prism
![NTP Server in Prism](/project1/images/2021-02-01_055156-ntp_servers_added.jpg)


# Configure DNS Name Server
![DNS Server in Prism](/project1/images/2021-02-01_055410-name_servers.jpg)

# Deploy Storage Container in Nutanix - Part 1
![Deploy Storage Container - Part 1](/project1/images/2021-02-01_060539-storage_container_1.jpg)

# Deploy Storage Container in Nutanix - Part 2
![Deploy Storage Container - Part 2](/project1/images/2021-02-01_060639-storage_container_2.jpg)


# Deploy Storage Container in Nutanix - Part 3
![Deploy Storage Container - Part 3](/project1/images/2021-02-01_060844-storage_container_3.jpg)

# Deploy Storage Container in Nutanix - Part 4
![Deploy Storage Container - Part 4](/project1/images/2021-02-01_060844-storage_container_4.jpg)

# Deploy Storage Container in Nutanix - Part 5
![Deploy Storage Container - Part 5](/project1/images/2021-02-01_060844-storage_container_5.jpg)
# Select the CentOS VM Image to store in the Storage Container
![Select CentOS VM Image](/project1/images/2021-02-01_061459-centos_disk_image.jpg)

# Add the CentOS VM Image to the Storage Container
![Add CentOS VM Image to Storage Container](/project1/images/2021-02-01_061557-centos_disk_image_2.jpg)

# Select the Windows VM Image to store in the Storage Container
![Select Windows VM Image](/project1/images/2021-02-01_061737-add_image-windows.jpg)

# Add the Windwos VM Image to the Storage Container - Part 1
![Add Windows VM Image to Storage Container - Part 1](/project1/images/2021-02-01_061737-add_image-windows_2.jpg)

# Add the Windwos VM Image to the Storage Container - Part 2
![Add Windows VM Image to Storage Container - Part 2](/project1/images/2021-02-01_062655-add_image_windows_3.jpg)

# Create Production Network - Part 1
![Create Prod Network - 1](/project1/images/2021-02-01_071517-create_prod_network_1.jpg)

# Create Production Network - Part 2
![Create Prod Network - 2](/project1/images/2021-02-01_071517-create_prod_network_2.jpg)

# Create Production Network - Part 3
![Create Prod Network - 3](/project1/images/2021-02-01_071517-create_prod_network_3.jpg)

# Create Production Network - Part 4
![Create Prod Network - 4](/project1/images/2021-02-01_071517-create_prod_network_4.jpg)

# Add Windows Image
![Add Windows](/project1/images/2021-02-01_113611-add_image_windows_4.jpg)

# Virtual Networks Created
![Virtual Networks](/project1/images/2021-02-01_114817_networks_created.jpg)

# Create Production VM - Part 1
![Prod VM - 1](/project1/images/2021-02-01_115123-create_vm.jpg)

# Create Production VM - Part 2
![Prod VM - 2](/project1/images/2021-02-01_115235-create_prod_vm2.jpg)

# Create Production VM - Part 3
![Prod VM - 3](/project1/images/2021-02-01_115356-create_prod_vm3.jpg)

# Create Production VM - Part 4
![Prod VM - 4](/project1/images/2021-02-01_115451-create_prod_vm_4.jpg)

# Display all Production VMs
![Prod VMs](/project1/images/2021-02-01_120311-prod_vms.jpg)

# Display all Development & Production VMs
![All VMs](/project1/images/2021-02-01_121740-all_vms_created.jpg)

# Create Protection Domain (Async DR) - Schedule for Development VMs
![Protection Domain - Dev](/project1/images/2021-02-01_122156-create_schedule_for_dev.jpg)

# Development VMs - Protection Domain
![Protection Domain - Dev - Success](/project1/images/2021-02-01_125308-dev-dr-1.jpg)

# Production VMs - Protection Domain
![Protection Domain - Prod - Success](/project1/images/2021-02-01_125440-create_prod-dr.jpg)
# Delete a Production DB VM
![Delete Prod DB VM](/project1/images/2021-02-01_125947-delete_db_prod.jpg)

# Restore Production DB VM from Snapshot
![Restore Prod VM from Snapshot](/project1/images/2021-02-01_130159-restore_snapshot.jpg)

# List of VMs and Restored VMs
![Restore Prod VM from Snapshot](/project1/images/2021-02-01_130326-list_vms_with_restored_vms.jpg)




#













![Private Cloud](/project1/images/0-start.jpg)

