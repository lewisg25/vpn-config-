# vpn-config-
# vpn-config
<h1>Analyzing the Impact of a VPN on IP Address Behavior</h1>

![Screen Shot 2023-10-26 at 10 25 58 AM](https://github.com/Courela23/vpn-config/assets/136120929/92abb410-7d7b-4c51-b7a7-ee531e5e9d33)

A VPN, or Virtual Private Network, is a technology that encrypts and secures your internet connection, providing privacy and protection from potential threats. It also allows you to access the internet as if you were in a different location, bypassing geo-restrictions and enhancing online anonymity.

</p>

<h1>Project Overview</h1>

![Screen Shot 2023-10-26 at 10 52 42 AM](https://github.com/Courela23/vpn-config/assets/136120929/e4f54715-d145-47c9-b30c-4b6ba8c3df7c)


<h2>Environments/Technologies Needed</h2>

- Microsoft Azure Account & VM
- ProtonVPN (free free subcription)
-	Remote Desktop for Windows or Mac

<h2>Operating System Used </h2>

- Macbook Pro m1

<h2>Objective</h2>

- Create a resource group on Azure.
-	Establish a Windows 10 virtual machine in Azure
-	Initiate a remote desktop connection to access the virtual machine.
-	Retrieve the IP address and location of the VM using whatismyipaddress.com.
-	Download the free edition of ProtonVPN, and create an account if necessary.
-	Connect to a ProtonVPN server
-	Use whatismyipaddress.com to find the new IP address and location for the VM
-	Visit a Netflix to detect any modifications in URL or language.
-	Conclude by removing Resource Groups from Azure.

<h2>Summary</h2>

<p>
</p>
<p>
<h2>Creating a Resource Group on Azure</h2>
In this Azure project tutorial, we'll walk you through the process of setting up your Azure free subscription and creating a resource group. To get started, head to the Azure portal and either sign in with your existing Microsoft account or create one if you don't have it. Once you're in, go to the "Subscriptions" tab and click on "Add" to create your free Azure subscription. Follow the on-screen instructions to complete the subscription setup.

After that, under the "Resource groups" section, click on "Create" to establish a new resource group. Give it a meaningful name and choose your preferred region. This resource group will serve as an organized container for managing your Azure resources effectively. With these initial steps, you'll be ready to start building and managing your Azure project. 
 
![Screen Shot 2023-10-26 at 9 52 37 AM](https://github.com/Courela23/vpn-config/assets/136120929/3303eff0-46e7-4467-a2a5-d896abb27056)

<p>


<h2>Creating a Virtual Machine on Azure</h2>

- Navigate to Virtual Machines: In the Azure portal, click on "Virtual machines" in the left-hand menu.
-	Add a New Virtual Machine: Click on the "+ Add" button to create a new virtual machine.
-	Configure Basics: Provide details like the name, region, operating system, and resource group for your virtual machine. You can also choose the authentication method (password or SSH key).
-	Choose Size: Select the virtual machine size based on your needs, considering factors like CPU, memory, and disk space.
-	Configure Settings: Set options for networking, monitoring, and management. You can create or use an existing virtual network, configure monitoring settings, and enable features like Boot Diagnostics if needed.
-	Review + Create: Review your settings to ensure they are correct, and then click "Create" to start the virtual machine deployment.
-	Deployment: Azure will deploy your virtual machine based on your chosen configuration. You can monitor the deployment progress in the Azure portal.
![Screen Shot 2023-10-26 at 10 15 24 AM](https://github.com/Courela23/vpn-config/assets/136120929/bfd44264-cf0c-4452-ae94-e9b40b2b0532)

![Screen Shot 2023-10-26 at 9 47 36 AM](https://github.com/Courela23/vpn-config/assets/136120929/da173a28-0d2a-43ca-a81b-e5b1333b2c17)

<h2></h2>
<p>
 
</p>

<p>

<br />

<p>
<h2>Connecting to VM using Remote Desktop</h2>
 
-	Access Your Virtual Machine: Once the deployment is complete, you can access your virtual machine via Remote Desktop (for Windows) or SSH (for Linux) using the credentials you provided during setup.
-	Get the Public IP Address: In the virtual machine overview, you'll find the public IP address. This is the address you'll use to connect.
-	Connect to the VM: In the Remote Desktop application, enter the public IP address of your virtual machine in the "Computer" field. Click "Connect."
-	Enter Credentials: You will be prompted to enter the username and password or credentials you provided during the virtual machine setup.
-	Connect: After entering the credentials, click "OK" or "Connect." The Remote Desktop session will establish, and you will have access to your virtual machine.
![Screen Shot 2023-10-26 at 11 13 19 AM](https://github.com/Courela23/vpn-config/assets/136120929/9ef433ab-ca15-4b63-85f5-045179f5228d)

 ![Screen Shot 2023-10-26 at 9 48 27 AM](https://github.com/Courela23/vpn-config/assets/136120929/77493193-b86e-449d-a2dc-586f1677c192)

</p>
<p> 

<p>
<h2>Confirming the IP Address of the VM</h2>
On the Virtual Machine, launch a web browser, then enter "whatismyipaddress.com" into the search bar. Make a record of the IP address shown. Please be cautious not to share or reveal your public IP address to unauthorized individuals, as it could potentially expose your private location and make you vulnerable to malicious actions aimed at your network.

 ![Screen Shot 2023-10-26 at 12 11 14 PM](https://github.com/Courela23/vpn-config/assets/136120929/fc180e09-d07e-4795-8434-d6da3f9d0a95)
</p>
<p>  

</p>
<p>
 
</p>
<p>
</p>
<p>
<h2>Installing & Deploying Proton VPN</h2>
 
- Start by opening a new tab in your web browser.
-	In the address bar, enter "protonvpn.com" and hit Enter.
-	On the ProtonVPN website, locate the "Create Free Account" button and click on it.
-	Fill in the required information to create your ProtonVPN account. This typically includes your email address and a secure password.
-	Once you have successfully registered for a ProtonVPN account, proceed to download the ProtonVPN client that is compatible with your operating system.
-	Wait for the download to finish, and then locate the installer for the ProtonVPN client.
-	Run the VPN client installer and choose all the default settings as suggested by the ProtonVPN setup wizard.
-	After the installation is complete, launch the ProtonVPN application on your device.
-	Log in to the ProtonVPN application using the same login credentials you used to create your account.
-	Upon logging in, you may notice that the free account offers a limited selection of VPN servers. This is because free accounts typically come with fewer server options.
![Screen Shot 2023-10-26 at 10 12 21 AM](https://github.com/Courela23/vpn-config/assets/136120929/6213e6e5-b5fa-43fd-98b5-252e2f0e0c56)
</p>
<br /> 
</p>
<p>  

<h2>Establishing a VPN Connection</h2>
Pick one of the available VPN servers for connection and allow the connection to establish. For this example, Japan has been chosen.
</p>  

![Screen Shot 2023-10-26 at 10 12 53 AM](https://github.com/Courela23/vpn-config/assets/136120929/1eb84e7f-8d99-425f-8651-fab1263b4f8c)
<p>

<h2>Confirming & Observing the VPN Connection</h2>
After establishing the connection, you can confirm it by refreshing the dashboard interface. Next, open a web browser and visit "whatismyipaddress.com." Here, you will observe that the public IP address of the virtual machine (VM) now reflects the geographical region where the VPN server is situated. 

![Screen Shot 2023-10-26 at 10 14 04 AM](https://github.com/Courela23/vpn-config/assets/136120929/d07447f7-f5a9-48df-a905-b4c3f7348e36)
 
![Screen Shot 2023-10-26 at 10 14 30 AM](https://github.com/Courela23/vpn-config/assets/136120929/56330199-751e-4320-8ade-43a93420cd2e)

</p>
<p>
<h2>Conclusion</h2> 
</p>
  
In summary, creating a virtual machine emulates certain aspects of a VPN by showing an IP address corresponding to the VM's server location when selecting the region. However, a VPN offers additional benefits, such as serving content in the region's language and providing region-specific information. To validate this, simply visit a popular website in your browser and compare the language and content displayed on the webpage with what you see when accessing the same webpage on your physical PC.
</p>
<br />
