# ms2013

[Watch the installation guide video](https://youtu.be/oUulif3RQJA)
install link
(https://1024terabox.com/s/1xYQoO8G8xEbVPYkoij8rGw)

# Install Microsoft Office Suite in Linux

##### For arch distro
```
yay -Syu playonlinux winbind python-pyasyncore
```

##### Update package list
```
sudo apt-get update
```
##### Install playonlinux - a graphical tool that simplifies the installation of Windows applications using Wine.
```
sudo apt-get install playonlinux
```
##### Install winbind - a compatibility component that helps PlayOnLinux and Wine run Microsoft Office properly—especially for licensing and activation.
```
sudo apt-get install winbind
```
##### Install python dependencies
```
sudo apt-get install python3-pyasyncore  
```
##### Create a folder in root
```
mkdir ~/word2013iso
```
##### Mount the iso file to the folder
```
sudo mount -o loop ~/Downloads/file_name.iso ~/word2013iso
```
##### Open playonlinux
```
playonlinux
```
##### Install and browse for the `setup.exe` file mounted in the root folder.

> After Installation

![image](https://gist.github.com/user-attachments/assets/d7c063cd-1784-43cc-ac7b-ed5e18d3fdea)
![image](https://gist.github.com/user-attachments/assets/ca653d39-bd87-4955-ba8d-7f1329ce1416)
