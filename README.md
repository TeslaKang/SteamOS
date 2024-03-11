# SteamOS
This explains how to create my own Steam OS<br>
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
Create the downloaded ISO file into a USB disk by DD mode<br>
We recommend the rufus program<br>
<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/d273a6c5-97f6-4cbb-826d-a3d397e5778c"><br>
<br>
Secure space for installation in Windows<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/823182bc-fc7f-4df3-890c-7daa0e65932c"><br>
<br>
After connecting the Linux installation USB to the PC, use the Del key or F2 key (different for each device) to enter BIOS and select the installation USB<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/c9fd89b3-2e51-49a9-91d0-371437daaac3"><br>
<br>
When you boot, you will see the Manjaro Linux installation screen as shown below<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/ccb98b8f-8ae3-49fe-9f65-62664418ee12"><br>
Run <b>Install Manjaro Linux</b> to start the installer<br>
<br>
When installing, be sure to set the language to English<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/a4b7472c-fa48-484e-b202-bb53491e34c8"><br>
<br>
Select region, then select keyboard<br>
<br>
Now comes the most important part: deciding where to install it<br>
If you make a mistake here, the existing Windows may be destroyed, so be careful<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/4d850f43-fe3d-40e6-b448-db16d400837a"><br>
Select the disk to install from number 1<br>
If you want to install by reducing the size of the existing partition without dividing the partition, select “Install alongside” from number 2, select the partition you want to install, and then adjust the size<br>
If you previously secured a partition to install on, just select “Replace a partition” in number 3 and then select the partition you want to install on<br>
You are an expert, I know a lot about partitions, and if you want to control things in more detail..<br>
After selecting number 4, you can manually specify partitions<br>
(For number 4, you must mount the / and /boot/efi partitions. Others are optional.)<br>
Additionally, it is recommended that the file system be EXT4<br>
In the case of BTRFS, the file system is often damaged during use, and even the slightest damage makes it unrecoverable<br>
<br>
Set up a user account<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/f19e7b88-f434-4592-9bd1-3c25bbd7c676"><br>
The name must be <b>deck</b><br>
Please enter your password appropriately<br>
And be sure to uncheck “<b>Log in automatically without asking for the passwd</b>”<br>
If you choose that, you will run into some problems because the files that handle that option are different during installation and when configuring KDE<br>
<br>
It briefly shows the information to be installed<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/26412fa5-a207-4e34-a92d-f42a049cc023"><br>
When you're ready, click <b>Install</b> to begin installation<br>
<br>
manjaro asking again<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/9acf4bf2-cf51-47f1-9e43-9f98f1379cbc"><br>
Click <b>Install now</b><br>
<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/e9b3e6f5-e19b-49a6-b750-265fd12ecb22"><br>
Installation takes approximately 5-10 minutes<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/82dc483c-b191-4595-a19b-4d0097b36ba1"><br>
When finished, reboot<br>
<br>
After re-entering BIOS..<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/19a7c4c3-40ce-48e0-b0bd-a05a8a2dfa59"><br>
Select Manjaro Linux and boot<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/a76844da-2ac0-45d2-8ecc-f99486b1b12a"><br>
<br>
When you enter the password you set during installation, Manjaro Linux will welcome you<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/ecd9a0ed-63fb-47eb-a2fa-366c9ef6b307"><br>
<br>
The basic installation is now complete<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/6cbddaf0-9d5d-42f0-8495-668f0ef45f77"><br>
<br>
<br>
# Configure Linux
<br>
Linux is now installed<br>
Before installing Steam OS, you need to set up some basic settings<br>
Run System Settings<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/538bdc03-fe25-43f9-b0d8-b120f70b6d78"><br>
<br>
Select Startup and Shutdown..<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/9ca832bc-e375-4235-baf8-b4d3f0e6856a"><br>
Select Behavior<br>
<br>
Set the deck to automatically log in<br>
Then select Open KDE Wallet Setting<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/b2b6ffed-6386-4956-938f-fbb2191a670c"><br>
<br>
Select Change Password, enter nothing for the password and press Ok<br>
If you set a password here, you will be repeatedly asked for the password later<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/24ba1c92-4c62-4e59-a1e6-249fcf8147c7"><br>
<br>
When you click Apply, you will be asked for a password. Enter the password you entered during installation<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/7afb6795-e766-4b10-8c3e-c9c2fe9838ca"><br>
<br>
Click on the DOS window at the bottom to run konsole<br>
Linux starts and ends with the console, so you should always be familiar with the console<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/e1d39457-4d46-4336-8e7d-6fbc5874379a"><br>
If you are a Korean/Chinese/Japanese user, install the font by sudo <b>pacman -S noto-fonts-cjk</b><br>
When you first run the command, a warning (?) is displayed. Just ignore it and enter the password you entered during installation<br>
Please note that the password input is not visible, so do not assume that it cannot be entered<br>
<br>
An error occurs saying that the package information has not been updated<br>
Type <b>sudo pacman -Sy</b> as described above<br>
When it's all over..<br>
Type <b>sudo pacman -S noto-fonts-cjk</b> again<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/d7d8606c-4cef-42fe-b61b-63ebe314a1e8"><br>
<br>
This time... trying to update the Linux key<br>
Press Y or just Enter<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/f55e565f-313c-4677-b7ef-112bf9207174"><br>
Now install the font<br>
Just press Y or Enter<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/58d66254-6bb0-430d-a6cf-148e7b755fde"><br>
<br>
Now let's install discover<br>
(Manjaro has its own package installer, but Steam OS and KDE mainly use discover.)<br>
In the console, run <b>sudo pacman -S discover</b>.
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/a05fd278-cabf-4403-be75-c143be82d7a3"><br>
<br>
If you go to Start -> System, you will see Discover<br>
To commemorate the installation(?), let's run it<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/de462abb-ef33-4286-9ed6-909159c4d87b"><br>
It runs well<br>
For reference, if you right-click on the taskbar and select Pin to Task Manager, an icon will appear on the taskbar for convenient use later<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/654c36a9-5afa-45ad-8015-d0742458b502"><br>
<br>
Come back to the konsole..<br>
<b>sudo pacman -S cpupower ark bc onboard gcc jq</b> to install<br>
<b>cpupower</b> is a program that can set up the CPU, and <b>ark</b> is a program that processes compressed files<br>
<b>bc</b> is a program that allows calculation(?) on the command line, and <b>onboard</b> is an on-screen (touch) keyboard<br>
<b>gcc</b> is a compiler, and <b>jq</b> is a program needed to install decky-loader, which will be installed later<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/23567940-4f03-40d8-8bed-070e75a48b86"><br>
<br>
Now let's try updating the entire system<br>
Just type <b>sudo pacman -Syu</b><br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/dc97f54f-9947-46b4-ae7c-30756d035636"><br>
They seem to be installing quite a lot..<br>
Just press y or enter to start installation<br>
After installation is complete, reboot and you will have the latest version of Linux<br>
<br>
When the screen lock is enabled on a UMPC without a keyboard, it is difficult to enter the password..<br>
Try unlocking the screen<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/2c621791-1eb2-4066-885c-1a062e1a3e2d"><br>
Launch Settings and select Workspace Behaviors<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/0cb7dd32-84cc-4823-b20b-631f40a49c8c"><br>
Unlock as above<br>
<br>
Now try turning off Search (if it's on, it can find things in the background and use a lot of CPU)<br>
If you disable it, a warning is displayed<br>
Just ignore it and click Apply<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/08085e49-c45a-4923-9a46-7e175273d560"><br>
<br>
Now let's install Chrome<br>
Personally, I think Chrome is better than Firefox, which is installed by default<br>
(People using Firefox can skip this.)<br>
Chrome will be installed through flapak, so install it with <b>sudo pacman -S flatpak</b> in the konsole<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/2f59b69c-3285-484a-a215-c501749a3f58"><br>
<br>
Now run Discover and type chrome to search for Chrome<br>
Just click install<br>​
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/70351618-70ee-45a9-975d-bfc6dea945db"><br>
<br>
If Chrome does not appear, it may be because the flatpak settings are incorrect<br>
Click on Discover's settings, add dl.flathub.org to the flatpak address, and try again.Click on Discover's settings, add dl.flathub.org to the flatpak address, and try again<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/b2963a31-fc6c-4fe0-8e36-fbe0cc78a67d"><br>
Just find Chrome in the Start menu and run it<br>
Please note that if it is not on startup, it will appear after rebooting<br>
<br>
Try deleting “Welcome to Manjaro” that appears when you run Manjaro Linux<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/c45a8a1b-6782-4145-9414-c85cc91b7060"><br>
You can remove it by running <b>sudo pacman -R manjaro-hello</b><br>
<br>
Also, since you installed Chrome, you don't need firefox either<br>
You can delete it with <b>sudo pacman -R firefox</b><br>
<br>
When you enter the sudo command, you will be asked for your password<br>
If this bothers you, you can disable it using the method below<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/d537454b-15c5-46ab-86ce-fb187bb3d94b"><br>
In the konsole, type <b>kate /etc/sudoers.d/deck</b><br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/01047480-3f68-4cba-b608-93ebf1506da1"><br>
deck ALL=(root) NOPASSWD:ALL<br>
Just enter , click Save, and enter your password<br>
Now, when you run sudo commands in the console, you will no longer be asked for an annoying password<br>
<br>
The basic settings are now complete<br>
<br>

# Dual booting made easy
<br>
You installed Linux, but if I want to boot into Linux, I have to go into the BIOS and select Linux every time<br>
GPD Win 4 or Max 2, which have a keyboard, are fine, but for devices without a keyboard, you can only select the OS when the keyboard is connected through a USB hub<br>
So let's try to solve it<br>
Run the konsole<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/6e3b6fee-fbc5-40d8-97c0-6a8b6f6808da"><br>
Go to the folder containing the kernel with <b>cd /boot</b><br>
Check which files exist with <b>ls -l</b><br>
The important files here are the kernel file starting with <b>vmlinux</b> and the initial RAM disk file starting with <b>initramfs</b><br>
In the case of Manjaro Linux, the version number is attached to the kernel<br>
In my case..<br>
linux 6.6 is vmlinuz-6.6-x86_64 / initramfs-6.6-x86_64.img<br>
linux 6.7 is vmlinuz-6.7-x86_64 / initramfs-6.7-x86_64.img<br>
<br>
Run <b>sudo cat grub/grub.cfg</b>.
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/dfc03e3b-671f-4e2f-beb4-62a1f465f654"><br>
A lot of content is printed..<br>
If you move up with the mouse wheel..<br>
You can see the file name in the /boot directory registered there<br>
The important ones there are "/boot/vmlinuz-6.6-x86_64", "root=UUID=3b86ac23-ef58-4c54-b841-02d595eba78b", "/boot/initramfs-6.6-x86_64.img"<br>
Also remember the UUID of the root volume, "a25f8b7d-c15a-4d9f-9d6a-4b6c98a4ecac"<br>
Please note that UUID is a unique value given during installation, so they all have different values<br>
Write down the three contents above in a notepad<br>
​<br>
<br>
The work on Linux is now complete<br>
<br>
Boot into Windows<br>
Download <a href="https://github.com/TeslaKang/SteamOS/raw/main/GameAssist.7z">GameAssist</a><br>
When you run the GameAssist, a rEFind tab that wasn't there before will appear<br>
Modifying the bootloader may make your device unbootable<br>
In other words, you must pay enough attention<br>
However, the boot loader can be restored very easily, so if you have basic knowledge, there will be no major difficulties<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/4ea111a0-f89f-48ae-8132-1f058007eca3"><br>
First select the EFI partition<br>
In most cases, there will be only one partition, so it will be selected automatically<br>
Then click Refind Install to install<br>
Refind will now be registered as a bootable item and you will be able to select it in BIOS<br>
<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/a3279152-9a2a-4e6e-b753-57e877200cda"><br>
A gamepad driver is also installed so that it can be operated with a gamepad instead of keys. If necessary, ext2/3 drivers and ntfs drivers can also be installed<br>
If you are not sure, you can leave it as default<br>
Since most UMPCs have vertical LCDs, select the rotation portion appropriately and set it so that the OS selection screen appears correctly<br>
If the screen is abnormal when booting, you can modify the resolution<br>
The resolutions of 0, 1, 2, and 3 are different for each device, so you can set them after testing<br>​
<br>
The OS item detects the system and automatically creates Windows and Linux related items<br>
For Windows, there is no need to configure anything differently, but for Linux, you need to enter the previous information to operate properly<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/71e54a7f-d47f-4d67-ba53-9153cf60f2cf"><br>
The <b>volume</b> part is the file system delimiter where the kernel file is located<br>
If you have only one Linux installed on your system, you can enter information such as the kernel name, loader<br>
Write a name starting with vmlinuz in /boot<br>
If you have installed more than one Linux, if the kernel name is the same, the correct file system cannot be found, so in that case, just write down the name or uuid of the partition<br>
In my case, since I have 4 Linux installed on my system, I decided to use UUID<br>
<b>loader</b> is where the kernel is located<br>
Just enter the same information as in the volume section<br>
<b>initrd</b> is the location of the initial ramdisk file<br>
Just enter the file name starting with initramfs<br>
<b>options</b> are options given to the kernel. Here, only root is required, others are optional<br>
The GameAssist is created with the following contents<br>
You can just roughly fix it there<br>
options "root=UUID=xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx rw rd.udev.log_priority=3 vt.global_cursor_default=0 fbcon=rotate:0"<br>
In my case..<br>
    options "root=UUID=3b86ac23-ef58-4c54-b841-02d595eba78b rw rd.udev.log_priority=3 vt.global_cursor_default=0 iomem=relaxed fbcon=rotate:0"<br>
    graphics on<br>
fbcon=rotate:0 is the rotation direction of the kernel message when booting<br>
It is not very important, but if it is a vertical screen, it is good to correct it by inserting numbers such as 1, 2, and 3<br>
Additionally, “iomem=relaxed amd_pstate=disable” was added<br>
It's not that important, but I added it because there are some functions that won't work without that option<br>
Also added "initrd=/boot/amd-ucode.img"<br>
It is not required, but is a patch file related to CPU security updates<br>
Now reboot<br>
If you go into the BIOS and look at the boot item settings, you will see rEFInd for GameAssist, which was not visible<br>
Select this<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/9a2814f7-0cbf-441a-8105-189af244fb36"><br>
<br>
Now, when you reboot... you will see an item where you can select Windows and Linux<br>
(Unlike other loaders, you can select with the gamepad. For reference, the A key is selected.)<br>
Try booting into Linux<br>
If it doesn't work, reboot into Windows and correct the Refind item in the GameAssist<br>
If you want to boot into Linux without going through Refind, select Manjaro in the BIOS and it will boot as before<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/e1188427-f319-460e-b5d9-25a453c26053"><br>
<br>
Now, let's set up the refind configuration file in Linux so that you can easily edit it<br>
Run the konsole<br>
<br>
Type <b>kate /etc/fstab</b>.
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/96280cf1-4d48-4f69-9759-90c5fe8e5ef6"><br>
If /boot/efi's permissions are set to 0077, it cannot be opened<br>
So change to defaults<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/3b8823d5-13ec-49a7-bff8-b9ebcba842d3"><br>
Please note that whenever you modify a system-related file, you will be asked for a password<br>
Try rebooting<br>
Run the konsole again<br>
Run <b>kate /boot/efi/EFI/refind/game_assist.conf</b><br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/6d650cb4-c332-4f24-8c3c-8da14e1f09a1"><br>
You can see that the content you saw in the GameAssist is exactly the same<br>
In other words, you can modify refind settings in Linux as well<br>
Multi-booting is now complete!!<br>

# Install gamescope-session
<br>
Basic Linux tasks are now complete<br>
Let’s start by installing Steam OS-related files on Linux<br>​
<br>
First, install steam, gamescope, mangohud, etc. as explained in the overview<br>
Run konson<br>
Type sudo <b>pacman -S steam gamescope-plus mangohud glfw-x11</b><br>
Once installation is complete, Steam will be registered<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/21a83a53-32cc-4ea9-a7c3-4fea29480414"><br>
Launch Steam<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/850c76bf-c239-4cb6-8ca9-6cc1027b6f77"><br>
Working hard on downloading~~<br>
Let sit until done<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/b9e059a7-37c2-4a54-b176-fa3dd31a9001"><br>
If it comes out like this, it is a success<br>
<br>
Press X to exit<br>
<br>
Now you just need to install the actual Steam OS.<br>
After moving to the Documents folder(by cd ~/Documents) in the konsole.<br>
Enter <b>git clone https://github.com/TeslaKang/gamescope-session.git</b>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/7b41b042-17d3-44cd-a0f3-1c76a218c479"><br>
Check the contents with <b>ls -l</b><br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/7f1a5e96-0b0f-4e97-8334-39a00fff40cb"><br>
Install with <b>./install</b><br>
It's easy to install.<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/1cfb2c90-fb6d-48a9-af0a-51624f73d63b"><br>
If you look at your desktop, you'll see a Steam icon and an icon for Game Mode<br>
When you run Return to Gaming mode, you will be taken to Steam OS<br>







