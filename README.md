# Installing-Active-Directory

<h2>Description</h2>
In this lab, I'll demonstrate how to install Active Directory Domain Services on Windows Server. We will then promote the server into a domain controller. A domain controller is just a computer or server that has Active Directory running on it. We will be using a Windows Server 2022 virtual machine (VM) for the demonstration of this lab.
<h2>Environment Used</h2>

- <b>Windows Server 2022</b> (Datacenter)

<h2>Windows Server Manager</h2>
To start off will go to https://portal.azure.com and click on the VM tab.
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/6c81228b-239e-412a-9a1e-40115bace25c" alt=/>
Then we will proceed to create our VM according to the specifications highlighted below.
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/7e23da19-0bbe-4355-b063-64cc57cd0729" alt=/>
For the resource group we won't put anything and will let Azure create one for us.
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/f0acc944-8ba6-42a2-9a5f-61a13073471c" alt=/>
Make note of the username and passowrd you create. Then click review + create to finish the VM process.
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/e05974ff-1e46-42e8-9206-0343e61a10c6" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/d31ce911-9955-47f2-b251-4fc735346ad5" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/3ae59950-a21c-4b0a-ad05-cd3f3b4f16d1" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/7f7b871a-6dfd-4e2a-a2ce-f395a7044b26" alt=/>
To start of we will open the Server manager application in our Windows server VM.
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/89069ca5-5b6f-4dc6-bbab-568e135f8c55" alt=/>
Click on add roles and features.
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/3de1e86d-b1b4-4b1f-816f-8350a1516c0d" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/2beea535-283e-4a8e-b0eb-9d3db5e7cee3" alt=/>
Select Role-based or feature-based installation.
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/334151b5-eb3e-4cdd-8f61-982702bcccef" alt=/>
Click select a server from the server pool and select our DC-1 machine.
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/d3291a34-ed28-4a03-8d91-5f41696ce270" alt=/>
Click the option Active Directory Domain Services.
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/13517796-d544-4601-8ddb-46d9b31697d7" alt=/>
Add features.
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/1f5288e6-fcd3-4b67-bd78-64201302c309" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/695c1860-793b-4551-b970-2bc4b466ede3" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/f473d6da-7897-43f1-9d78-89f3c69c639d" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/8be627b5-a357-4fdc-8019-55916abf97ea" alt=/>
Hit install.
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/de547999-d383-4859-b07f-f7d175d6ae92" alt=/>
Click close once the Installation bar is completed.
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/b2211be4-d975-4137-beaf-bfe0b146edf8" alt=/>
Click on the yellow flag in the upper right hand corner and select promote this server to a domain controller.
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/dc66b3fc-afeb-4c80-9729-0263ae940a5f" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/d362f625-947c-4c9e-b921-65b382e78749" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/a6148894-1412-45bc-a99f-8557191b3adb" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/d3c106cb-e4a7-4a3b-97f8-14a09496f9e1" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/69e19a9a-ef36-4981-b322-9874b114e964" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/9c3703da-9215-4f72-aac2-b69f97a70afd" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/426b90a6-5b9e-44b7-b38e-ad5b18b420f0" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/80622144-fd88-4c3e-a276-bc05d20b983e" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/71a18563-08ef-478a-925b-ac510d26819e" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/5da4d269-240b-445f-8a71-e9df253f1073" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/86c7a8a6-b903-4d25-9a83-959c35b9388b" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/57aac7d3-20e3-44cc-b828-66d3131e31b0" alt=/>
<img src="https://github.com/alibashir7/Installing-Active-Directory/assets/165006117/e8eb82a2-09db-431a-b0ab-5e61f3216dd0" alt=/>
