# Nessus-Project

## Objective

- Learn how to identify target hosts on the network using three avenues Ping, ARP, and Nmap.
- Understand how DNS works
- Perform DNS enumeration
- Discover live hosts using various scanning tools
- Learn and practice enumeration using Nmap
- Set up and perform scanning using Nessus

### Skills Learned

- Utilizing Ping, ARP, and nmap tools to scan n=networks and machines
- using different flags for each tool to narrow down searches
- Learned zone transfers and enumerating subdomains
- Operating System Fingerprinting/Nmap Scripting Engine
- Vulerability scanning


### Tools Used

- Nessus
- Ping
- ARP
- Nmap
- DNSEum
- zonetransfer.me
- dnsrecon

## Steps

**Enumerating Subdomains**

1. On Kali Linux, I used the following commands to install DNSmap:


![Screenshot 2024-12-06 123213](https://github.com/user-attachments/assets/676a25fe-aa77-400c-a779-6b96a2533240)

![Screenshot 2024-12-06 123159](https://github.com/user-attachments/assets/c0be34bd-dfd4-45ee-805c-26818772aa9f)

2. Next, I ran the following commands to discover subdomains of duckduckgo.com:

![Screenshot 2024-12-06 123229](https://github.com/user-attachments/assets/4c95e540-a85a-47d8-b627-809068a57ff8)

![Screenshot 2024-12-06 123247](https://github.com/user-attachments/assets/47d0474e-cbb0-437c-b452-f6a78078ff68)


---------------------------------------------------------------------------------------------------------------------

**Network Scanning**

1. In the screenshots below I excuted some basic network scanning commands using ping, nmap, and ARP:



   ![Screenshot 2024-12-06 125039](https://github.com/user-attachments/assets/9b9fe6d9-3cbc-4a5e-abc6-4960d17378d0)


   ![Screenshot 2024-12-06 124941](https://github.com/user-attachments/assets/607e5ebf-0a75-47d1-89f5-88a7a11258d7)


   ![Screenshot 2024-12-06 124557](https://github.com/user-attachments/assets/f761ba3d-5ec6-4dcb-a5e6-1fb3086cfde1)

----------------------------------------------------------------------------------------------------------------------

**Vulnerability Scanning**

1. Below the screenshot shows a Exploit database used to gather information:

![Screenshot 2024-12-06 130017](https://github.com/user-attachments/assets/716039b9-74b1-4272-9dac-f2b93e6260cc)


![Screenshot 2024-12-06 130120](https://github.com/user-attachments/assets/b2a2a63c-4b2c-47d0-a687-8212e9ba3652)

2. The screenshots below show how you can search databases from the Kali Linux command line:


![Screenshot 2024-12-06 130311](https://github.com/user-attachments/assets/695aa68a-6c73-4877-99b0-db00539bc18c)


![Screenshot 2024-12-06 130501](https://github.com/user-attachments/assets/1898a834-b820-443b-81f3-c0af4363c6a2)


----------------------------------------------------------------------------------------------------------------------

**Installing and utilizing Nessus**


1. The screenshots below shows the downloading and installation of Nessus into Kali Linux:


![Screenshot 2024-12-06 131012](https://github.com/user-attachments/assets/1fc9761b-9f71-49d2-bfc7-b8ad48ba815d)




![Screenshot 2024-12-06 131455](https://github.com/user-attachments/assets/d4686716-f249-4e0c-9b61-d27a9d88aedd)



![Screenshot 2024-12-06 131554](https://github.com/user-attachments/assets/cb1051f7-43e8-45ed-ad28-e15b3a9c381c)





![Screenshot 2024-12-06 131655](https://github.com/user-attachments/assets/0050d74e-001c-4424-9035-0e353ef3243e)



---------------------------------------------------------------------------------------------------------------------------------


## Lab Excercises


**Excercise 1 - DNS Enumeration and Zone Transfers**

1. Log into Kali Linux, open a terminal amd execute the following command to view a list of parameters needed to use DNSRecon and attempt to retrive DNS records of the target :


![Screenshot 2024-12-06 132339](https://github.com/user-attachments/assets/944ad42f-f85f-44c3-9486-652a2d234f3f)


---------------------------------------------------------------------------------------------------------------------------



2. On Kali Linux Execute the host zonetransfer.me command. Next, use the host -t zonetransfer.me command to enumerate the Name Servers for the target domain:


![Screenshot 2024-12-06 134935](https://github.com/user-attachments/assets/dee74c33-0aba-4878-abd3-609f2d7ec351)

-----------------------------------------------------------------------------------------------------------------------

3. Use the following command to query the domain name using one of the name servers found in previous step:

![Screenshot 2024-12-06 135123](https://github.com/user-attachments/assets/37c5ba84-f45e-4243-9f7e-f2bb7b0a8dd5)




![Screenshot 2024-12-06 135305](https://github.com/user-attachments/assets/7c1ccb51-52d8-46a9-99cb-a4921f579147)


---------------------------------------------------------------------------

4. Lastly, to automate the process of DNS zone transfer, use DNSEnum tool:



![Screenshot 2024-12-06 135355](https://github.com/user-attachments/assets/e5b3e359-5a6d-48c6-8aa1-9f8b3f2b15ee)



![Screenshot 2024-12-06 135405](https://github.com/user-attachments/assets/8d3f3ba9-5c15-4a83-86fb-cb14df95978c)






**Excercise 2 - Nmap**


1. Try three basic Nmap commands:


![Screenshot 2024-12-06 135917](https://github.com/user-attachments/assets/d8d2cf4f-0dbb-4b5e-b254-0ff63b69e165)


![Screenshot 2024-12-06 140059](https://github.com/user-attachments/assets/d12ac4be-43e8-4f35-925f-718974f9b9da)



![Screenshot 2024-12-06 140232](https://github.com/user-attachments/assets/f1508928-98ca-4f51-821c-aa7f87db48ca)




-----------------------------------------------------------------------------------------------------------------------

**Conclusion**

In conclusion, this project provided good inroduction to the most common tools and techniques needed for enumeration and active reconnaissance. This project played a huge role in helping cultivate the hacker mindset. 


