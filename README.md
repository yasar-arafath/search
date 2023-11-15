# Privacy-Based Virtual Search Engine

## How to Use This Repository

1. Clone the repository using the command: `git clone [repository-url]`

2. Open the cloned repository in your preferred code editor.

3. Follow the steps below to set up and use the virtual search engine on Azure:

   - **Step 1:** Create an Azure Active Directory.
   - **Step 2:** Create an Azure Virtual Desktop under the Azure Active Directory. Virtual Desktops are VDI-based desktops with a unique set of configurations and operating systems.
   - **Step 3:** Create a host pool inside the Azure Virtual Desktop, and create a session host in the host pool.
   - **Step 4:** Create a virtual network and subnets for a private and secure network for the session host.
   - **Step 5:** Create a network security group and network interface with inbound port rules to connect with the session host.
   - **Step 6:** Use Azure AD Domain Services to create a domain within Azure for hosting the virtual machine.
   - **Step 7:** Create an Azure storage disk with sufficient storage and capacity inside the session host to run the applications.
   - **Step 8:** Upload an MSIX package of the application to the session host. A desktop application is created for the search engine, and an MSIX package is generated.
   - **Step 9:** Connect to the application either using the RDP host or through the web interface.
   - **Step 10:** Access the application using the RDP host or the web interface, and use the search engine to query and crawl websites across the web.

4. Start searching using the virtual search engine!

## License

Copyright © 2022 Yasar Arafat. All Rights Reserved.

Licensed under the [MIT License](License.txt).
