<h1>CISCO CONFIGURATION - WIRELESS NETWORK</h1>

<h2>Description</h2>
<b>Configured a number of devices to a wireless network using Cisco Packet Tracer.
</b>
<br />
<br />
The project will include steps on how to configure devices (laptops, desktops, and a server) to a wireless network.
<br />
<br />


<h2>Inital Setup</h2>

- <b>Cisco Packet Tracer</b> Download this to use for configuration and display of project

<h2>Basic Setup</h2>

<h3>Configure the Internet Setup:</h3>
<br />
- <b>Go to the GUI of the Wireless Router.</b>
<br />
- <b>Navigate to Internet Setup > Wireless Tri-Band Home Router.</b>
<br />
- <b>Set the Internet Connection type to Automatic Configuration - DHCP.</b>
<br />
- <b>Change the IP Address to 192.168.1.1.</b>
<br />
<br />

<p align="center">
<img src="https://github.com/user-attachments/assets/f955d9c8-f640-438b-b84c-4f3b58a5d363" height="55%" width="55%" alt="Screenshot_1_Initial_Wifi_Network_Config"/>
</p>

<h3>Configure Basic Wireless Settings:</h3>
<br />
- <b>Go to GUI of Wireless > Basic Wireless Setup..</b>
<br />
- <b>You will see three SSIDs listed:.</b>
<br />
  - <b>2.4 GHz</b>
  <br />
  - <b>5 GHz - 2</b>
  <br />
  - <b>5 GHz - 1</b>
<br />
- <b>Change the SSID names to a preferred name (e.g., CSTestNetwork) for all three.</b>
<br />
- <b>Enable only the 2.4 GHz network and disable the other two (5 GHz - 2 and 5 GHz - 1).</b>
<br />
<br />

<p align="center">
<img height="55%" width="55%" alt="Screenshot_1_Basic_Wireless_Setting_Setup" src="https://github.com/user-attachments/assets/63ac8f7a-bbee-4f81-86b9-7ffc2fed63c7">
</p>


<h3>Configure Wireless Security:</h3>
<br />
- <b>Go to Wireless > Basic Wireless Setup > Wireless Security.</b>
<br />
- <b>Change the security setting from Disabled to WPA2 Personal.</b>
<br />
- <b>Set a secure passphrase (e.g., Securenetworkpw123!).</b>
<br />


<p align="center">
<img height="55%" width="55%" alt="Screenshot_1_Basic_Wireless_Security_Setup" src="https://github.com/user-attachments/assets/e8a8b86d-81e6-403c-a359-97c9084bda7b">
</p>


<h3>Connecting Devices to WiFi</h3>
<br />
- <b>Connect Devices to the Wireless Network:</b>
<br />
- <b>Click on the device you want to connect.</b>
<br />
- <b>Go to the Physical Tab.</b>
<br />
- <b>Power off the device, remove the current LAN card, and replace it with a WiFi LAN antenna card.</b>
<br />
<br />
<h4>(Screenshot of Laptop configuration)</h4>
<br />
<br />


<p align="center">
<img height="55%" width="55%" alt="Screenshot_5_LT0_pt1" src="https://github.com/user-attachments/assets/cadc2feb-ddea-4caf-a650-748a32f5bf9f">
</p>

<p align="center">
<img height="55%" width="55%" alt="Screenshot_5_LT0_pt2" src="https://github.com/user-attachments/assets/140feeab-4b0b-4927-b36f-ffd8aa65d27b">
</p>

<br />
- <b>Go to the Desktop Tab and open the PC Wireless section.</b>
<br />
- <b>Go to the Connect Tab and hit the Refresh button to display available networks.</b>
<br />
- <b>Select the wireless network and click Connect.</b>
<br />
- <b>Enter the passphrase in the Pre-shared Key section and click Connect.</b>
<br />
<br />


<p align="center">
<img height="55%" width="55%" alt="Screenshot_3_PC0" src="https://github.com/user-attachments/assets/969abe84-ed45-44e8-b0b0-a1abb6b48a39">
</p>

<p align="center">
<img height="55%" width="55%" alt="Screenshot_4_PC0" src="https://github.com/user-attachments/assets/0ec905cd-645a-4211-9acc-72e0d4e5c8a4">
</p>


<h3>Check RF Communication</h3>
<br />
- <b>Verify RF Communication:</b>
<br />
- <b>Open the Command Prompt on the connected device.</b>
<br />
<br />

<p align="center">
<img height="55%" width="55%" alt="Screenshot_5_LT0_pt3" src="https://github.com/user-attachments/assets/51809bc0-c8ba-4eaa-83b8-34477a4f0bde">
</p>

<br />
- <b>Run the command ping 192.168.1.1 to check the communication.</b>
<br />
<br />


<p align="center">
<img height="55%" width="55%" alt="Screenshot_1_Command_Prompt_Ping" src="https://github.com/user-attachments/assets/f1f56fd5-b1e3-4ce1-89f8-40a6c6bd4c0a">
</p>

<h3>Server Configuration</h3>
<br />
- <b>Setup Server for Wireless Network:</b>
<br />
- <b>Repeat the WiFi connection steps for the server device.</b>
<br />
<br />
- <b>To check the connection via Web Browser:</b>
<br />
<br />
- <b>Go to the Services Tab.</b>
<br />
- <b>Open index.html.</b>
<br />
- <b>Edit the content to :This is CSTESTNetwork Server.</b>
<br />
<br />

<p align="center">
<img height="55%" width="55%" alt="Screenshot_Server_Message" src="https://github.com/user-attachments/assets/ba323e33-251e-473f-a9a4-6b02178e778b">
</p>

<br />
<br />
- <b>Change the server’s IP configuration to Static:</b>
<br />
<br />
- <b>IPv4 Address: 192.168.1.105</b>
<br />
- <b>Subnet Mask: 255.255.255.0</b>
<br />
- <b>Default Gateway: 192.168.1.1.</b>
<br />
<br />


<p align="center">
<img height="55%" width="55%" alt="Screenshot_1_Server_IP_Config" src="https://github.com/user-attachments/assets/5591a3e0-d084-44d3-a9cc-57650c5e03c5">
</p>


<h3>Add the server’s IP to the DNS record.</h3>
<br />
- <b>Redirect to the server’s IP when a domain (e.g., www.google.com) is typed in the browser.</b>
<br />
<br />


<p align="center">
<img height="55%" width="55%" alt="Screenshot_1_Server_DNS" src="https://github.com/user-attachments/assets/83cf053c-3b9c-4d90-9a30-569529262c43">
</p>


<h3>Final Setup:</h3>
<br />
- <b>Ensure all settings are correctly applied and devices are connected.</b>
<br />
- <b>Test the network setup by browsing to www.google.com or the server IP (192.168.1.105) to see the header message: This is CSTESTNetwork Server displayed.</b>
<br />
<br />


<p align="center">
<img height="55%" width="55%" alt="Screenshot_1_Server_DNS" src="https://github.com/user-attachments/assets/83cf053c-3b9c-4d90-9a30-569529262c43">
</p>



<p align="center">
<img height="55%" width="55%" alt="Screenshot_1_Final_Wifi_Network_Config" src="https://github.com/user-attachments/assets/4f149867-911a-4a3c-8222-80384e47d72b">
</p>

<h5>Project Reference</h5>
<p>Youtube: Configuring Wireless Network in Cisco Packet Tracer | CCNA | Networkforyou</p>
<br />
<br />
