# SteamOS
This explains how to create my own Steam OS.<br>
<br>
Install arch linux + KDE DE.(We recommand using manjaro minimal version)<br>
https://manjaro.org/download/<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/8c5d76ac-5934-4f6c-be45-860dfef43488)
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/b88a1e41-42bb-4232-b3e8-e8f889bda780)<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/21005d72-8328-46bd-b417-0da9c8052bb3)<br>
<br>
Create the downloaded ISO file into a USB disk by DD mode.<br>
We recommend the rufus program.<br>
<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/d273a6c5-97f6-4cbb-826d-a3d397e5778c)<br>
<br>
Secure space for installation in Windows.<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/823182bc-fc7f-4df3-890c-7daa0e65932c)<br>
<br>
After connecting the Linux installation USB to the PC, use the Del key or F2 key (different for each device) to enter BIOS and select the installation USB.<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/c9fd89b3-2e51-49a9-91d0-371437daaac3)<br>
<br>
When you boot, you will see the Manjaro Linux installation screen as shown below.<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/ccb98b8f-8ae3-49fe-9f65-62664418ee12)
Run <b>Install Manjaro Linux</b> to start the installer<br>
<br>
When installing, be sure to set the language to English.<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/a4b7472c-fa48-484e-b202-bb53491e34c8)<br>
<br>
Select region, then select keyboard.<br>
<br>
Now comes the most important part: deciding where to install it.<br>
If you make a mistake here, the existing Windows may be destroyed, so be careful.<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/4d850f43-fe3d-40e6-b448-db16d400837a)
Select the disk to install from number 1.<br>
If you want to install by reducing the size of the existing partition without dividing the partition, select “Install alongside” from number 2, select the partition you want to install, and then adjust the size.<br>
If you previously secured a partition to install on, just select “Replace a partition” in number 3 and then select the partition you want to install on.<br>
You are an expert, I know a lot about partitions, and if you want to control things in more detail...<br>
After selecting number 4, you can manually specify partitions.<br>
(For number 4, you must mount the / and /boot/efi partitions. Others are optional.)<br>
Additionally, it is recommended that the file system be EXT4.<br>
In the case of BTRFS, the file system is often damaged during use, and even the slightest damage makes it unrecoverable.<br>
<br>
Set up a user account.<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/f19e7b88-f434-4592-9bd1-3c25bbd7c676)
The name must be <b>deck</b>.<br>
Please enter your password appropriately.<br>
And be sure to uncheck “<b>Log in automatically without asking for the passwd</b>”.<br>
If you choose that, you will run into some problems because the files that handle that option are different during installation and when configuring KDE.<br>
<br>
It briefly shows the information to be installed.<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/26412fa5-a207-4e34-a92d-f42a049cc023)
When you're ready, click <b>Install</b> to begin installation.<br>
<br>
manjaro asking again.<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/9acf4bf2-cf51-47f1-9e43-9f98f1379cbc)
Click <b>Install now</b><br>
<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/e9b3e6f5-e19b-49a6-b750-265fd12ecb22)
Installation takes approximately 5-10 minutes.<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/82dc483c-b191-4595-a19b-4d0097b36ba1)
When finished, reboot.<br>
<br>
After re-entering BIOS...<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/19a7c4c3-40ce-48e0-b0bd-a05a8a2dfa59)
Select Manjaro Linux and boot.<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/a76844da-2ac0-45d2-8ecc-f99486b1b12a)
<br>
When you enter the password you set during installation, Manjaro Linux will welcome you.<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/ecd9a0ed-63fb-47eb-a2fa-366c9ef6b307)
<br>
The basic installation is now complete.<br>
![image](https://github.com/TeslaKang/SteamOS/assets/82138730/6cbddaf0-9d5d-42f0-8495-668f0ef45f77)





