# Window-Server-Actve-directory-
The following lab is a demo of window server and the use of active directory, setting up users and computers, the lab also includes Group policy configurations, File sharing and security, DHCP and DNS and bits of Power shell scripting... the client virtual machine used in this lab is a windows 10 VM.

<h1>Networking</h1>
<p>
  We are using virtual box for the following lab.There are two adapters that come in to play, <b>Adapter 1</b> is set on NAT and is used to for updates and connection to the internet, <b>Adapter 2</b> is used for internal network.
 </p>
  <img width="1305" height="609" alt="Screenshot 2026-10-06 112845" src="https://github.com/user-attachments/assets/37d2d022-75f2-4ffd-ba48-d9413d1d0679" />

<h1>Server manager</h1>
<p>
  Once we all set up navigate to the server manager, Rename your server.
  In my case ill also change my second adapters IP address, this will act as a gateway for my client devices to connect to the domain. 
  Domain ending in a <b>.local</b> is used as a Top level domain in my lab. 
<p>
<img width="1020" height="640" alt="Screenshot 2026-10-06 114649" src="https://github.com/user-attachments/assets/874db5fb-4a4d-4ebb-8a26-c5c75c0fbcef" />

<h1>Active Directory</h1>
<p>
Below is the basic layout of Active Directory in a real world scenario.
The <b>Red block</b> indicates the forest/root of the the active directory, everything created fall under the forest. The <b>Blue block</b> shows the folders within the active directory, this organizers users,computers and servers. The folders are more well known as organizational units or OU. The <b>Purple block</b> is a user, these are people that are created and fall under this domain.  
</p>
<img width="976" height="598" alt="Screenshot 2026-10-06 151614" src="https://github.com/user-attachments/assets/ac74944c-997a-4577-abed-12d5b6f09325" />

<h2>User Creation</h2>
<p>
  A brief clip of user creation
</p>
https://github.com/user-attachments/assets/d8776b12-22c2-4e9d-af13-802d6fc3c004

<h1>Group Policy Objects</h1>





