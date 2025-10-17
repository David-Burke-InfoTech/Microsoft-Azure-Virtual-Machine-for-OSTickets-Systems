<p align="center">
<img width="407" height="266" alt="image" src="https://github.com/user-attachments/assets/b277c876-3a17-4b42-9725-87e85c7ac88c" /
>
</p>

<h1>Microsoft Azure Virtual Machine for OSTickets Systems</h1>
This tutorial outlines the installation and setup of a virtual machine in Microsoft Azure for running OS ticketing Systems.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- A Desktop or Laptop with a modern CPU/Ram combo
- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows 10 or newer

<h2>List of Prerequisites</h2>

- Create Microsoft Azure Account
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

The first step we will need to take is creating an account with Microsoft Azure. 

<p>
<img width="2555" height="1387" alt="VM" src="https://github.com/user-attachments/assets/c9614584-eca9-47c4-b6e7-0ecf5ce4fe8e" />
</p>

After logging into Microsoft Azure, you will scroll down and click the Virtual Machine icon

</p>
<br />

<p>
<img width="1913" height="826" alt="VM-1 1" src="https://github.com/user-attachments/assets/201f50b4-0533-4c24-8814-0c028d430581" />
</p>
<p>
Click on the Create tab
</p>
<br />

<p>
<img width="1911" height="757" alt="VM-1" src="https://github.com/user-attachments/assets/9f54a3b2-3fd3-49fa-96ea-921cd5f658c5" />
</p>
<p>
Click Virtual Machine.
</p>
<br />

<p>
<img width="1910" height="766" alt="VM-2" src="https://github.com/user-attachments/assets/43cfe020-8595-45d1-8836-ceb5ac425850" />
</p>
<p>
You will now want to create a Resource group; we named ours "osTicket".
</p>
<br />

<p>
<img width="1911" height="767" alt="VM-3" src="https://github.com/user-attachments/assets/60bc6e85-065f-4e9b-a3da-6fc778c6aab6" />
</p>
<p>
Name your Virtual Machine; we named ours osTicket-vm.
</p>
<br />

<p>
<img width="1907" height="767" alt="VM-4" src="https://github.com/user-attachments/assets/a871b943-04b3-4ac4-b925-1fb13f33276a" />
</p>
<p>
Next, you will want to pick a Region that best fits your geo location.
</p>
<br />

<p>
<img width="1908" height="764" alt="VM-5" src="https://github.com/user-attachments/assets/56665cf9-4f60-452b-8850-92787cc8854c" />
</p>
<p>
Under Zone options, click *Azure-selected zone(Preview). Let Azure assign the best zone for your needs
</p>
<br />

<p>
<img width="1911" height="822" alt="VM-6" src="https://github.com/user-attachments/assets/7b675555-df3c-43d7-ade6-91dac4fc5f94" />
</p>
<p>
For Image, you will want to select Windows 10 Pro, version 22H2 - x64 Gen2 (free services eligible)
</p>
<br />

<p>
<img width="1918" height="761" alt="VM-7" src="https://github.com/user-attachments/assets/a142261a-d50a-4910-8b06-50a27ba33942" />
</p>
<p>
Size you will select Standard_D2s_v3 - 2 vcpus, 8 GiB memory ($70.08/month)
</p>
<br />

<p>
<img width="1904" height="759" alt="VM-8" src="https://github.com/user-attachments/assets/0611fc73-1fed-4e05-89d4-078a366a0ec3" />
</p>
<p>
Under Administrator Account, create a username and password.
</p>
<br />

<p>
<img width="1910" height="765" alt="VM-9" src="https://github.com/user-attachments/assets/dbdf8cd7-90d6-4fbc-bfe8-b86ce9408a53" />
</p>
<p>
Licensing: You will select *I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights.
</p>
<br />

<p>
<img width="1910" height="696" alt="VM-10" src="https://github.com/user-attachments/assets/1886e0c9-166a-4832-92fe-646165e9f9c5" />
</p>
<p>
Then click Next: Disks
</p>
<br />

<p>
<img width="1903" height="729" alt="VM-11" src="https://github.com/user-attachments/assets/2db3eb7b-40bc-47be-9159-7fcdae192e6c" />
</p>
<p>
Click Next: Networking
</p>
<br />

<p>
<img width="1910" height="737" alt="VM-12" src="https://github.com/user-attachments/assets/15f7cb47-7760-4a42-b0eb-0956aa7a7672" />
</p>
<p>
Network Interface: Azure should auto-fill this section for you. Don't change anything and click Review + create.
<p>
<img width="1911" height="736" alt="VM-13" src="https://github.com/user-attachments/assets/39c6902c-607f-4943-a71a-c2f7a9aa1cd2" />
</p>
<p>
