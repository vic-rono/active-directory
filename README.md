# ACTIVE-DIRECTORY

configuring active directory for domain management and adding users using a powershell script.<br>

Also provides users with domain passwords that will be used to connect to the internal network.

This lab contains a domain controller in the windows server 2019 that houses the [active-directory](https://en.wikipedia.org/wiki/Active_Directory).<br>


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

The server enables configuration of NAT and routing so that users in the internal network can reach the internet.<br>

The server also creates doman and configures dhcp for users to automatically get ip addresses.<br>

It can also assign the scope i.e specify ip addresses range.<br>

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------


  ## 1. Configuration summary
  
  Server manager dashboard showing roles and servers assigned.<br>
  
  ![roles and servers](https://user-images.githubusercontent.com/61822296/194907783-746cb5a9-a857-4728-9b83-7ce312fcfd23.png)<br>
  
  ## 2. Assigning default gateway and DNS server for the internal network<br>
       
  ![SERVER 19 INTERNAL](https://user-images.githubusercontent.com/61822296/194907788-2ac02a9b-90d6-4f7a-8c48-54907018760e.png)
  
  ## 3. Configuring AD DS
   
   ![AD DS](https://user-images.githubusercontent.com/61822296/194907794-8879a48a-ac26-463f-b9f5-b3ec8d447183.png)
  
  ## 4. Setting up the administrator
   
  

   
  
  ## 5. Running the createusers.ps1 powershell script to add 500 users to the active-directory, instead of manually adding them
      
![userslist](https://user-images.githubusercontent.com/61822296/222226872-f29dfdd6-e617-420e-b82b-978b5e985649.png)   

      
    
     
     
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------
 
  




