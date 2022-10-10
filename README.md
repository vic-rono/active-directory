# ACTIVE-DIRECTORY

configuring active directory for domain management and adding users using a powershell script.<br>

Also provides users with domain passwords that will be used to connect to the internal network.

This lab contains a domain controller in the windows server 2019 that houses the [active-directory](https://en.wikipedia.org/wiki/Active_Directory).<br>


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------


  1. Configuration summary<br>
  
  Dasboard server manager dashboard showing roles and servers assigned.<br>
  
  ![roles and servers](https://user-images.githubusercontent.com/61822296/194907783-746cb5a9-a857-4728-9b83-7ce312fcfd23.png)<br>
  
  2. Assigning default gateway and DNS server for the internal network<br>
       
  ![SERVER 19 INTERNAL](https://user-images.githubusercontent.com/61822296/194907788-2ac02a9b-90d6-4f7a-8c48-54907018760e.png)
  
  3. Configuring AD DS<br>
   
   ![AD DS](https://user-images.githubusercontent.com/61822296/194907794-8879a48a-ac26-463f-b9f5-b3ec8d447183.png)
  
  4. Setting up the administrator<br>.
    ![DOMAIN NAME](https://user-images.githubusercontent.com/61822296/194907762-5ff0f239-8e1a-4fcc-9747-fcfd121d7690.png)
    
    ![domainadmin](https://user-images.githubusercontent.com/61822296/194907769-0a25dd69-139a-4918-974d-4619c843d0f0.png)
   
  
  5. Running the createusers.ps1 powershell script to add 500 users to the active-directory, instead of manually adding them.<br>
      
     ![script](https://user-images.githubusercontent.com/61822296/194907786-16075bc2-df72-4ccf-aeb4-86d27cf3ca77.png)<br>
     
     The users as seen in the active-directory.<br>
      
     ![userslist](https://user-images.githubusercontent.com/61822296/194907792-14b7ef5b-da49-4737-8e00-b0c641069807.png)<br>
     
     
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------
 
  




