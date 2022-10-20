# fernyark

### Changing PC name

- GO to "local server"  

- Click on the server name : change name to your preferred one  
<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/changing%20name/Screenshot%20(3).png" width= 600>

- Restart the PC for the changes to take effect  




### Creating static IP

- Go to "local server"  

- Click on Ethernet  

- Right click and click on properties
<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/sratic%20ip/Screenshot%20(5).png" width=600>  

- Select IPV4 and click properties 
<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/sratic%20ip/Screenshot%20(6).png" width=600> 

- Manually configure the IP  
<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/sratic%20ip/Screenshot%20(7).png" width=600>  

- Also use the server address for the DNS server address  

- Restart the server for the changes to taje effect  




### Istalling Active Directory  


- Go to Dashboard  

- Click "Add a new feature"  
<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/active%20directory/Screenshot%20(8).png" width=600>

- Click next  

- In server role options, select Active Directory Domain Services  
<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/active%20directory/Screenshot%20(11).png" width=600> 

- Click add features and click install  
<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/active%20directory/Screenshot%20(12).png" width=600>
<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/active%20directory/Screenshot%20(14).png" width=600>





### Promoting to a Domain controller 
- Click on Promote this server to a domain controller  
<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/promoting/Screenshot%20(15).png" width=600>  

- Select "Add a new forest"  
<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/promoting/Screenshot%20(16).png" width=600>

- Set domain as **fernyark.local**  

- Make sure DNS and Global Catalog is selected  

- Type your password and click next  

- Confirm NETBIOS domain name and press next  

- Leave paths as defaults  

- Review your options and click next  

- Wait for the prerequisite check to finish and press **install**  





### Making the PC DHCP 
- Go to Dashboard

- Go to "Add roles and features"  
<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/DHCP/Screenshot%20(22).png" width=600>  

- Click next  

- Select DHCP server from the server role options  

- Click "Add features" and press next  

-<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/DHCP/Screenshot%20(25).png" width=600>  






### Creating Users  

- Click on **Tools**  

- Select Active Directory Users and Computers

<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/users/Screenshot%20(26).png" width=600> 

- Expand the domain and select Users  

<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/users/Screenshot%20(27).png" width=600>

- Right click on Users and select new  

<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/users/Screenshot%20(28).png" width=600> 

- Set up the first name, last name, login username and password.  

<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/users/Screenshot%20(29).png" width=600>

- User is now created  

<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/users/Screenshot%20(32).png" width=600>


### Creating an Administrative User

- Right click on the admistrative and click copy  

<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/admin/Screenshot%20(34).png" width=600>

- Fill in the user name and password

<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/admin/Screenshot%20(35).png" width=600>  

- User is now an admin with the following roles  

<img src="https://github.com/A2509/fernyark/blob/main/Screenshots/admin/Screenshot%20(36).png" width=600>
