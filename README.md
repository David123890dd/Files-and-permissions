# Files-and-permissions

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Network Security Group(NSG)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h3>To do this section, you need a domain controller and a client. go to the domain controller. open files and create several new files like this:</h3>

![image](https://github.com/David123890dd/Files-and-permissions/assets/138183500/1e21f40d-7172-4aa9-8c0e-f7578343184f)

<h3>Right click, Properties --> Sharing --> Share...--> select the users/groups you would like to set permissions to and choose "Read" or "Read/Write". if you dont want to give access to a user, remove the user if the user is already in there.</h3>

![image](https://github.com/David123890dd/Files-and-permissions/assets/138183500/f76ff299-e1af-4176-bafc-9c825c6e8065)

<h3>After the file is shared, open the client virtual machine, open files and at the search bar enter two backslashes and the domain rootname.</h3>

![image](https://github.com/David123890dd/Files-and-permissions/assets/138183500/46ed0de5-01a4-41d1-be82-23b32957fe12)

<h3>since the "Resources" file was shared, the client can see the file too.</h3>
