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
<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/01047480-3f68-4cba-b608-93ebf1506da1"><br>
deck ALL=(root) NOPASSWD:ALL<br>
Just enter , click Save, and enter your password<br>
Now, when you run sudo commands in the console, you will no longer be asked for an annoying password<br>
<br>
The basic settings are now complete<br>
<br>

# Dual booting made easy
<br>
You installed Linux, but if you want to boot into Linux, you have to go into the BIOS and select Linux every time<br>
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
<br>
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
Now, when you reboot...<br>
<br>
you will see an item where you can select Windows and Linux<br>
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
<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/3b8823d5-13ec-49a7-bff8-b9ebcba842d3"><br>
Please note that whenever you modify a system-related file, you will be asked for a password<br>
<br>
Try rebooting<br>
<br>
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
<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/850c76bf-c239-4cb6-8ca9-6cc1027b6f77"><br>
Working hard on downloading~~<br>
Let sit until done<br>
<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/b9e059a7-37c2-4a54-b176-fa3dd31a9001"><br>
If it comes out like this, it is a success<br>
Press X to exit<br>
<br>
Now you just need to install the actual Steam OS.<br>
After moving to the Documents folder(by cd ~/Documents) in the konsole.<br>
Enter <b>git clone https://github.com/TeslaKang/gamescope-session.git</b>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/7b41b042-17d3-44cd-a0f3-1c76a218c479"><br>
<br>
Check the contents with <b>ls -l</b><br>
<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/7f1a5e96-0b0f-4e97-8334-39a00fff40cb"><br>
Install with <b>./install</b><br>
It's easy to install.<br>
<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/1cfb2c90-fb6d-48a9-af0a-51624f73d63b"><br>
If you look at your desktop, you'll see a Steam icon and an icon for Game Mode<br>
When you run Return to Gaming mode, you will be taken to Steam OS<br>
<br>
If you don't go into game mode, it's because auto login is set to Plasma<br>
After executing kate /etc/sddm.conf in konsole<br>
Just delete all contents of [Autologin]<br>
If you select automatic login during installation or set automatic login in the environment settings, the value will be registered and you will not be able to switch to game mode<br>
<br>
Now run Return to Gaming mode and check if it works properly<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/9a65df36-4542-406a-b5e2-2a9bca55b580"><br>
<br>
Enter the language/time zone/account to enter Steam OS<br>
Now it is the same as Steam Deck, so you can use it like Steam Deck<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/cc29061c-721c-4718-8604-899f3684df48"><br>
<br>
Try changing the desktop start icon to Steam Deck<br>
Press Menu, select Power, and then select Desktop to switch to the desktop<br>
Right-click on the Start icon and select "Configure Application Launcher..."<br>
Click the icon and select “Choose”<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/1cb54fef-e0e3-41c0-bfba-19a6aa8285e2"><br>
<br>
There are so many icons that it is difficult to find them, so type "dis" and select the Steam Deck start icon<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/c689a194-9800-40a8-9576-d24042c5fb30"><br>
<br>
Changed to Steam Deck start icon<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/0b9d58a8-5b40-478b-b4e7-7c6d7b5aee96"><br>
Now my device is a Steam Deck.<br>
<br>
Just use it diligently.<br>
<br>

# Make custom key/power key work
<br>
​The Steam OS is now installed<br>
However, the UMPC custom key or power key does not work, making actual use a bit difficult<br>
Let's solve this<br>
Expert have already created a solution, so all you have to do is install it<br>
<br>
The related program is <b>HandyGCCS</b><br>
However, after using HandyGCCS for a few months, it is fine for regular use, but when using it in hibernation mode, there is an issue where the controller stops working after hibernating 10-20 times<br>
Also, it cannot handle cover events from devices with covers like GPD Win Max2 or GPD Win Mini<br>
A thirsty person digs a well, so I created something called HandyGCCS++<br>
The basic HandyGCCS source is in Python, and each function is made into a module, making it difficult to manage, so I made it into just one file in C++<br>
After using it for about a month, there seemed to be no major problems, so we recommend that future users use HandyGCCS++<br>
<br>
First, go to https://github.com/TeslaKang/HandyGCCS and take a look<br>
If the device is not there, it is difficult to actually use it, so you can either wait for it to be added or download HandyGCCS++ and add it yourself<br>
<br>
First, launch the konsole<br>
Type cd Documents to move to the documents folder(It is convenient to use the tab key after entering only one or two characters, so get used to using the tab key~~)<br>
<b>git clone https://github.com/TeslaKang/HandyGCCS.git</b><br>
Type <b>cd HandyGCCS</b><br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/27514a65-f311-49a6-93a0-6fe2960f8a02"><br>
<br>
Launch <b>./stop.sh</b> to stop previously running services<br>
For install <b>sudo ./install.sh</b><br>
For launch <b>sudo ./start.sh</b><br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/56a5d0d4-04c4-41ef-8654-990203fe0e2c"><br>
<br>
To know if it's currently running well<br>
You can find out by running <b>./log.sh</b><br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/1c70b101-5dfa-4dde-9286-fb938dc44c49"><br>
<br>
If you want to change the settings for the key<br>
After stopping the service with <b>./stop.sh</b><br>
<b>kate /etc/handygccs/handygccs.conf</b><br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/5a83db7e-1e22-4503-ad2e-826ae467109d"><br>
Just restart the service with <b>./start.sh</b><br>

# Install GameAssist for Steam OS
<br>
Although Steam itself has a TDP or GPU clock setting function, it is tailored to the Steam deck, so it is lacking in other high-end UMPCs<br>
Let's solve this using the Game Assistant for Steam OS<br>
GameAssist for Steam OS was implemented through decky-loader<br>
So, you need to install decky-loader first<br>
First, go to <b>https://github.com/SteamDeckHomebrew/decky-loader</b> and take a look<br>
Installation is <b>"curl -L https://github.com/SteamDeckHomebrew/decky-installer/releases/latest/download/install_release.sh | sh​"</b><br>
Now run the konsole<br>
In the konsole, type <b>"curl -L https://github.com/SteamDeckHomebrew/decky-installer/releases/latest/download/install_release.sh | sh"</b><br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/ef70c5fa-d5fc-463e-959b-06dd0c52b701"><br>
Ugh... I can't install it because I don't have JQ<br>
Try installing JQ<br>
Enter <b>sudo pacman -S jq to install JQ</b><br>
<br>
If JQ installation is successful, enter the decky loader installation command<br>
For reference, you can use the previous command by pressing the up arrow key<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/9800479e-5bec-48d7-a54b-efe97e16d80d"><br>
It takes a little time, but it installs well<br>
<br>
Now let's install GameAssist<br>
In the konsole, navigate to the Documents folder with <b>cd ~/Documents</b><br>
<b>git clone https://github.com/TeslaKang/GameAssistSteamOS</b><br>
Go to the folder with <b>cd GameAssistSteamOS</b><br>
Check the contents with <b>ls -l</b><br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/ae37c8cb-c740-4693-8e1b-b3b93f6cc418"><br>
It should come out like above<br>
Just enter <b>./depoly.sh</b> to install<br>
​<br>
Now select “Return to Gaming mode” on the desktop to switch to gaming mode<br>
<br>
If you look at the QAM menu (if you don't have the QAM key, press Menu(Guide) + A), there is a plug icon that wasn't there before<br>
If you click on it, you will see GameAssist<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/67988840-8b87-461c-98be-c0c3eb36db31"><br>
<br>
Select Setting/Manager Items<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/67a59736-dc9e-4859-b7b2-934265c794d8"><br>
<br>
Please note that each item in the game assistant can be edited/added/deleted by the user<br>
In other words, you can configure it and use it as you wish<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/e8eb9132-a169-45d0-971c-a91c98be40b4"><br>
<br>
In the case of AyaNeo Air, if you want to make the TDP a little finer<br>
Go to Item Management, select CPU Package Power, and then select Edit<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/4d2f72b5-7256-4611-97db-25cbaf16e4df"><br>
<br>
Set the step value to 0.5 and select OK<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/6bf2c6a5-08f6-4372-bbc0-f2de28f53b1d"><br>
<br>
Package power can be set in 0.5W increments<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/543d2934-f925-4c1b-9150-9fdc9ea4fec4"><br>
<br>
There is also a function to change the settings of HandyGCCS<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/3fec8397-b010-4a09-be06-48b4ae4ff0a4"><br>
<br>
GameAssist has tried to include the basic features found in the SteamDeck whenever possible<br>
However, there may be bugs, and it was my first time using Python or React, the languages ​​used in the decky loader plugin, so there was a lot of trial and error, and there may be many shortcomings<br>
It would be much better if an expert refined this part later<br>
<br>
<b>Please note that GameAssist for Steam OS does not work on Steam Deck.</b>
<br>

# Activating hibernation mode
<br>
This is how to enable hibernation in Linux, which is necessary for the ultimate goal of running games between Windows and Steam OS without interruption<br>
Run the konsole<br>
Type <b>cd /home</b><br>
Enter <b>sudo fallocate -l 16G swapfile</b>(16G is your memory size. For users with 32G or more, 32G is too waste, so enter about 22G.)<br>
<b>sudo chmod 0600 swapfile</b><br>
<b>sudo mkswap swapfile</b><br>
<b>sudo swapon swapfile</b><br>
Type <b>kate /etc/fstab</b><br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/181f00c0-9dd7-4784-91b9-2281b1c86eb6"><br>
<br>
<b>/home/swapfile none swap defaults 0 0</b><br>
Enter the above content at the end of the file and press Save<br>
Then enter the password<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/83943536-7abf-4c76-a550-d4bc4ae1e005"><br>
<br>
Run <b>sudo systemctl edit --full systemd-logind</b><br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/4d892c66-e29a-418d-8b2e-0ab25addb860"><br>
<br>
Change the <b>ProtectHome</b> value to <b>read-only</b> about halfway through and press Ctrl+X to save and exit<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/69fb0ddf-deb6-4ef3-8544-729257c3c4f6"><br>
<br>
Run <b>kate /etc/mkinitcpio.conf</b> in the console again<br>
The original HOOKS had a # in front of them<br>
Remove <b>base</b> and <b>udev</b> and add <b>systemd</b><br>
That is, it goes like this:<br>
<b>HOOKS="systemd autodetect modconf block keyboard keymap consolefont plymouth filesystems"</b><br>
(Previously, it was processed by adding resume, but if you use systemd, resume is no longer needed)<br>
Save<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/b116371b-1ebe-4b56-b00d-4e5e0d0c1c46"><br>
<br>
If you type <b>sudo mkinitcpio -p linux</b> in the konsole and then press the TAB key, the configuration file in the system will be automatically entered<br>
(In the case of Manjaro Linux, it follows the rules of linux61, linux66, linux67, etc.)<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/9cdef70b-1c19-4c2e-bfef-b91b5941f8bd"><br>
<br>
You can see that it is well made as set up.
<br>
<b>
If you use HOOKS="systemd ..." described above and only one Linux is installed on the device<br>
There is no need to input uuid and offset as described below<br>
If you use the old method or more than one of Linux, you must enter uuid and offset in the kernel boot command as follows for it to work properly<br>
</b>
<i>
Now it is time to find the uuid and offset of the swap file<br>
Run <b>sudo findmnt -no UUID -T /home/swapfile</b> in the konsole<br>
In my case "a25f8b7d-c15a-4d9f-9d6a-4b6c98a4ecac"<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/f99c1a74-efe4-4edb-8da5-38457704bc56"><br>
<br>
Run <b>sudo filefrag -v /home/swapfile</b><br>
Since a lot of content is output, move to the beginning with the mouse wheel and remember the red numbers<br>
In my case 3055616<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/19be9a7c-0050-4210-b94d-407d4f585396"><br>
<br>
Now it is time to register in kernel options<br>
Run <b>kate /boot/efi/EFI/refind/game_assist.conf</b>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/292b90e5-3bc2-4ffb-a0b6-76417016254a"><br>
<br>
In the Refind settings file of the previously registered GameAssis<br>
Add <b>resume=UUID=xxxxx resume_offset=yyyy</b><br>
Please note that xxxxx and yyyy vary from person to person</b>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/caaed84a-d22f-4263-a60d-8916f736b888"><br>
Save it<br>​
</i>
<br>
Reboot<br>
When you click the Start menu<br>
Hibernation is now available<br>
Just test to see if it works<br>
<img src="https://github.com/TeslaKang/SteamOS/assets/82138730/6a181aec-026a-4e0b-aff0-0e6e6eb017fe"><br>
<br>
<br>
<b>
There are some things to keep in mind when using hibernation mode<br>
First, hibernation saves the current state of the OS to the SSD<br>
So, after another OS accesses the disk saved in hibernation mode and writes files to it, when it wakes up from hibernation mode, the disk is logically broken because it is not aware of any changes to the disk<br>
In the case of NTFS or EXT4, they are slightly damaged and can be recovered, but BTRFS becomes unrecoverable, so if you use hibernation, you should not use BTRFS<br>
In other words, if possible, write operations should not be performed in areas used by each other<br>
However, because MicroSD can be removed midway, it is safe to use in hibernation mode<br>
In other words, the best way is to share all data through MicroSD if possible<br>
Linux also has a function to determine whether Windows has exited hibernation mode<br>
So, Windows goes into hibernation mode first, and when Linux boots, the Windows partition is mounted as read-only and cannot be written to, so it operates safely(?)<br>
However, if Windows just shuts down and boots into Linux, Linux mounts the Windows partition as writable<br>
In this state, exit Linux into hibernation mode, boot into Windows, and then exit Windows into hibernation mode again<br>
When you wake up from hibernation with Linux, Linux cannot determine whether Windows has exited hibernation mode and is writable, so modifying files on the Windows partition will damage the Windows partition<br>
Therefore, if you use hibernate mode, you should avoid writing to each other between the Windows and Linux partitions if possible<br>
<i>
Please be careful!!</i>
</b>
<br>

