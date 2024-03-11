# SteamOS
This explains how to create my own Steam OS.<br>
<br>
<br>
# Install Linux
<br>
Install Arch linux + KDE DE.(We recommand using manjaro minimal version)<br>
https://manjaro.org/download/<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/8c5d76ac-5934-4f6c-be45-860dfef43488">  
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/b88a1e41-42bb-4232-b3e8-e8f889bda780"><br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/21005d72-8328-46bd-b417-0da9c8052bb3"><br>
<br>
Create the downloaded ISO file into a USB disk by DD mode.<br>
We recommend the rufus program.<br>
<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/d273a6c5-97f6-4cbb-826d-a3d397e5778c"><br>
<br>
Secure space for installation in Windows.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/823182bc-fc7f-4df3-890c-7daa0e65932c"><br>
<br>
After connecting the Linux installation USB to the PC, use the Del key or F2 key (different for each device) to enter BIOS and select the installation USB.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/c9fd89b3-2e51-49a9-91d0-371437daaac3)<br>
<br>
When you boot, you will see the Manjaro Linux installation screen as shown below.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/ccb98b8f-8ae3-49fe-9f65-62664418ee12)
Run <b>Install Manjaro Linux</b> to start the installer<br>
<br>
When installing, be sure to set the language to English.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/a4b7472c-fa48-484e-b202-bb53491e34c8"><br>
<br>
Select region, then select keyboard.<br>
<br>
Now comes the most important part: deciding where to install it.<br>
If you make a mistake here, the existing Windows may be destroyed, so be careful.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/4d850f43-fe3d-40e6-b448-db16d400837a">
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
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/f19e7b88-f434-4592-9bd1-3c25bbd7c676">
The name must be <b>deck</b>.<br>
Please enter your password appropriately.<br>
And be sure to uncheck “<b>Log in automatically without asking for the passwd</b>”.<br>
If you choose that, you will run into some problems because the files that handle that option are different during installation and when configuring KDE.<br>
<br>
It briefly shows the information to be installed.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/26412fa5-a207-4e34-a92d-f42a049cc023">
When you're ready, click <b>Install</b> to begin installation.<br>
<br>
manjaro asking again.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/9acf4bf2-cf51-47f1-9e43-9f98f1379cbc">
Click <b>Install now</b><br>
<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/e9b3e6f5-e19b-49a6-b750-265fd12ecb22">
Installation takes approximately 5-10 minutes.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/82dc483c-b191-4595-a19b-4d0097b36ba1">
When finished, reboot.<br>
<br>
After re-entering BIOS...<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/19a7c4c3-40ce-48e0-b0bd-a05a8a2dfa59)
Select Manjaro Linux and boot.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/a76844da-2ac0-45d2-8ecc-f99486b1b12a">
<br>
When you enter the password you set during installation, Manjaro Linux will welcome you.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/ecd9a0ed-63fb-47eb-a2fa-366c9ef6b307">
<br>
The basic installation is now complete.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/6cbddaf0-9d5d-42f0-8495-668f0ef45f77">
<br>
<br>
# Configure Linux
<br>
Linux is now installed.<br>
Before installing Steam OS, you need to set up some basic settings.<br>
Run System Settings.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/538bdc03-fe25-43f9-b0d8-b120f70b6d78"><br>
<br>
Select Startup and Shutdown...<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/9ca832bc-e375-4235-baf8-b4d3f0e6856a">
Select Behavior.<br>
<br>
Set the deck to automatically log in.<br>
Then select Open KDE Wallet Setting.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/b2b6ffed-6386-4956-938f-fbb2191a670c">
<br>
Select Change Password, enter nothing for the password and press Ok.<br>
If you set a password here, you will be repeatedly asked for the password later.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/24ba1c92-4c62-4e59-a1e6-249fcf8147c7">
<br>
When you click Apply, you will be asked for a password. Enter the password you entered during installation.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/7afb6795-e766-4b10-8c3e-c9c2fe9838ca">
<br>
Click on the DOS window at the bottom to run konsole.<br>
Linux starts and ends with the console, so you should always be familiar with the console.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/e1d39457-4d46-4336-8e7d-6fbc5874379a">
If you are a Korean/Chinese/Japanese user, install the font by sudo <b>pacman -S noto-fonts-cjk</b>b>.<br>
When you first run the command, a warning (?) is displayed. Just ignore it and enter the password you entered during installation.<br>
Please note that the password input is not visible, so do not assume that it cannot be entered.<br>
<br>
An error occurs saying that the package information has not been updated.<br>
Type <b>sudo pacman -Sy</b> as described above.<br>
When it's all over...<br>
Type <b>sudo pacman -S noto-fonts-cjk</b> again.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/d7d8606c-4cef-42fe-b61b-63ebe314a1e8">
<br>
This time... trying to update the Linux key.<br>
Press Y or just Enter.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/f55e565f-313c-4677-b7ef-112bf9207174">
Now install the font.<br>
Just press Y or Enter.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/58d66254-6bb0-430d-a6cf-148e7b755fde">
<br>
Now let's install discover.<br>
(Manjaro has its own package installer, but Steam OS and KDE mainly use discover.)<br>
In the console, run <b>sudo pacman -S discover</b>.
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/a05fd278-cabf-4403-be75-c143be82d7a3">
<br>
If you go to Start -> System, you will see Discover.<br>
To commemorate the installation(?), let's run it.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/b4ab8d84-2247-4c31-8caa-b6a1f50ac0d8">
It runs well.<br>
For reference, if you right-click on the taskbar and select Pin to Task Manager, an icon will appear on the taskbar for convenient use later.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/47cff60d-7034-4572-ad5c-62750ba04765)">
<br>
Come back to the konsole...<br>
<b>sudo pacman -S cpupower ark bc onboard gcc jq</b> to install.<br>
<b>cpupower</b> is a program that can set up the CPU, and <b>ark</b> is a program that processes compressed files.<br>
<b>bc</b> is a program that allows calculation(?) on the command line, and <b>onboard</b> is an on-screen (touch) keyboard.<br>
<b>gcc</b> is a compiler, and <b>jq</b> is a program needed to install decky-loader, which will be installed later.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/23567940-4f03-40d8-8bed-070e75a48b86">
<br>
Now let's try updating the entire system.<br>
Just type <b>sudo pacman -Syu</b>.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/dc97f54f-9947-46b4-ae7c-30756d035636">
They seem to be installing quite a lot...<br>
Just press y or enter to start installation.<br>
After installation is complete, reboot and you will have the latest version of Linux.<br>
<br>


