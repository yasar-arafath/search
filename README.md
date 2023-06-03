# A privacy based virtual search engine

##[Go to live](https://yasar-arafath.github.io/search)

##How to use this repo?

* Clone the repository first 'git clone'

* Once cloned,you can open the repository from any prefered code editer

* Open Azure
STEP 1: An Azure Active Directory is created
Step 2: An Azure Virtual Desktop is created under the Azure Active 
Directory.
Virtual Desktops are VDI-based desktops with a unique set of 
configuration and Operating Systems. These desktops are virtual 
machines with dedicated resources, applications, and user settings.
Step 3: A host pool is created inside the Azure Virtual Desktop and a
session host is created in the host pool.
Step 4: A virtual network and subnets is created for a private and secure 
network for the session host.
Step 5: A network security group and network interface is created with the 
Inbound port rules to connect with the session host
Step 6: Azure AD Domain Services is used to create an domain with Azure 
for hosting the virtual machine.
Step 7: An Azure storage disk is created with enough storage and capacity 
inside the session host to run the applications.
Step 8: An MSIX package of the application is uploaded to the session 
host.
A desktop application is created for the search engine and an MSIX 
package is created.
Step 9: The application is connected either using the RDP host or in the 
web interface.
Step 10: The application is accessed using the RDP host or through the 
web interface and the queries are searched to crawl websites across the 
web.
 
* search using the search engine!




## License
Copyright © 2022 yasar arafat. All Rights Reserved.
License under the [MIT](License.txt) License.
