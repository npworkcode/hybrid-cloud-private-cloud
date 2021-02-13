<h2>Create a Private Cloud solution to protect the key revenue generator an E-commerce web Application from failure events</h2>
<br>
<h3>Solution must:</h3>
<ol>
  <li>Prepare and handle failure events</li>
  <li>Mitigate downtime for customers</li>
  <li>All VMs must be protected against failure</li>
 </ol>
 <br>
 <h2>Tasks Completed</h2>
 <ol>
  <li>Deploy and protect three virtual machines for the test environment</li>
  <li>Deploy and protect three virtual machines for the production environment</li>
  <li>Three virtual machines are Web Server VM (Linux), Application Server (Linux) and Database Server (Microsoft SQL on Windows</li>
 </ol>
 <br>
 <h2>Solution Implemented</h2>
 <ol>
  <li>1 vCPU and 4 GB of RAM</li>
  <li>Configure NTP using pool.ntp.org</li>
  <li>Configure Domain Name Service DNS 8.8.8.8</li>
  <li>Create new Storage container Images to store Windows and CentOS virtual disk images</li>
  <li>Use naming convention of db-prod for Production VM and db-dev for Testing DB VM</li>
  <li>Set replication schedule of 1 hour</li>
  <li>Test solution by deleting the production database and restore to ensure application continuity</li>
 </ol>
 <br>
 ![Private Cloud](/project1/images/0-start.jpg?raw=true)
