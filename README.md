# Homelab

# Pre requisites: 
- Downloading Windows Server 2025 iso file
- Install it in Virtual Machine such as Oracle VirtualBox

<img width="959" height="438" alt="image" src="https://github.com/user-attachments/assets/4ce186e7-f8ae-47a3-9caa-4586893e2d46" />

- After installing change the name of the server to a sensible name such as FileServer01

<img width="805" height="637" alt="image" src="https://github.com/user-attachments/assets/963a6337-f4b6-4628-b839-18a48b27a432" />

- Configure Windows Updates

# Make a Homelab:

First of all open up Server Manager:

<img width="1026" height="768" alt="image" src="https://github.com/user-attachments/assets/40d2b998-dd4b-4401-a696-b8074b51c1f2" />

- Click on Manage
- Choose Add Roles and Features
- Choose Role-based and Next

<img width="788" height="559" alt="image" src="https://github.com/user-attachments/assets/d751b2bf-845d-45ac-bfc8-40e51006eb25" />

- Select the server and click Next:

<img width="787" height="561" alt="image" src="https://github.com/user-attachments/assets/37bc306e-f35a-41c6-a4a7-3aa9e6cd1f2b" />

- Select the Active Directory Domain Controller:

<img width="788" height="562" alt="image" src="https://github.com/user-attachments/assets/215943bb-c1cb-4326-84d8-19d93d097223" />

- This shows the tools that will be installed click on Add Features then Next:

<img width="421" height="441" alt="image" src="https://github.com/user-attachments/assets/7e752a08-240a-4cd6-b4b1-a237cf86f8b1" />

- Finally Install

<img width="794" height="564" alt="image" src="https://github.com/user-attachments/assets/a7ad3816-1bc0-48a7-82e2-ff720c1276f9" />

- After installation is done we need to promote this server into domain controller:

<img width="793" height="566" alt="image" src="https://github.com/user-attachments/assets/8fe4cee4-7538-49e4-b880-ae103b70df74" />

- Choose Add a new forest and here where we type in the domain name for the server we call it homelab.local then click Next

<img width="764" height="563" alt="image" src="https://github.com/user-attachments/assets/6ced7d46-9241-4eba-9f53-c4530f360357" />

- Click install then the server will reboot automatically





