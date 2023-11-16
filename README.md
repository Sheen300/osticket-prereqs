<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a resource group within Azure by going to portal.azure.com. Resource Groups. Click +Create at the top left. Name the resource group "RG-osTicket". 
- Choose your region.
- Next go back to portal.azure.com. Go to Virtual Machines. Click +Create. Add it to the resource group that we just made: that was named "RG-osTicket".
- Name the Virtual Machine: "vm-osTicket". No infrastructure redundancy required. Standard security type.
- Windows 10 Pro version for the Images.
- Standard: 4vcpus
- Choose a username and password. You should see the images below.

- ![image](https://github.com/Sheen300/osticket-prereqs/assets/150862861/c540347e-6115-4c23-b12a-3f292693c5f1)
- ![image](https://github.com/Sheen300/osticket-prereqs/assets/150862861/482cf00f-1992-4098-b807-720db1b11224)

- This helps you create the environment. Move forward with clicking Review+Create. Click virtual machines in Azure searchbar. You should see the now created Virtual Machine for os-Ticket that has now been created as depicted in the image below.

- ![image](https://github.com/Sheen300/osticket-prereqs/assets/150862861/a8c49fb7-3af0-456c-b985-ae530a69f3d7)

- Once the Virtual Machine has been created, while in Azure, click on Virtual Machines. Click Network. Copy the Public IP address that was created for the Virtual Machine. Click on Start. Type "cmd" to access the command panel. Paste the IP address that you copied from the Virtual Machine. This gives you access to the new Virtual Machine that was created within Azure from your remote desktop. You should see the following images below.

- ![image](https://github.com/Sheen300/osticket-prereqs/assets/150862861/f144d493-3f4b-448b-a400-2afbe757bfe1)
- ![image](https://github.com/Sheen300/osticket-prereqs/assets/150862861/4540754e-0fa7-4175-a3e6-8e36963a5a29)

- For the login and password of the new remote desktop connection, enter the username and password that you chose within Azure when you originally created the Virtual Machine.

- Once access has been made. Click on Start within the new remote desktop connection. Type "cmd" to pull up the command panel. And type "whoami". This tells you the name of the Virtual Machine that you are logged in as. Next, type "hostname". You should see the same name that appears. You should see the following image below.

- ![image](https://github.com/Sheen300/osticket-prereqs/assets/150862861/5039e5c4-20fd-4182-b0df-da47c292a902)

DONE!!
