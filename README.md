# Installation of ROS Noetic & ROS Foxy On Ubuntu Mate 20.04
#### 
## Task Description:-
Install Both ROS Noetic & ROS Foxy on Ubuntu Mate 20.04 and explain all the steps taken to achieve that.
#### 
## Before Installing ROS Noetic & ROS Foxy, You Must:
#### 
1. Download VirtualBox from this [link](https://www.virtualbox.org/wiki/Downloads)
2. Download Ubuntu Mate 20.04 desktop image from this [link](https://cdimage.ubuntu.com/ubuntu-mate/releases/20.04/release/)
3. Create a Virtual Machine For Ubuntu Mate 20.04 inside VirtualBox
4. Install Ubuntu Mate 20.04 inside the Virtual Machine
#### 
## 1. Download VirtualBox:-
#### 
![‏‏لقطة الشاشة (1994)](https://github.com/user-attachments/assets/d40b250a-5279-4a67-8a58-a1bef304439d)
#### 
## 2. Download Ubuntu Mate 20.04:-
#### 
![‏‏لقطة الشاشة (2012)](https://github.com/user-attachments/assets/cebbed7c-207d-4f3d-bbbd-4688fde56c1f)
#### 
## 3. Create a Virtual Machine For Ubuntu Mate inside VirtualBox:-
#### 
1- Click on New and create a new virtual machine
#### 
![‏‏لقطة الشاشة (2017)](https://github.com/user-attachments/assets/7ceb123d-46d2-4524-bfac-c4edaf738253)
#### 
2- Choose the amount of RAM (Base memory) and the number of virtual CPU(s) (Processor(s)) you want in this virtual machine
#### 
![‏‏لقطة الشاشة (2018)](https://github.com/user-attachments/assets/178284ea-5b78-4203-8ff5-6fded09e5f3e)
#### 
3- Select the size of the virtual hard disk - (no less than 20GB)
#### 
![‏‏لقطة الشاشة (2019)](https://github.com/user-attachments/assets/fe4cfa99-8d80-4888-babc-71ad6c02552a)
#### 
4- After creating the virtual machine: 
- Go to settings and click on storage, then click on the blue CD icon that's named (Empty).
- After that, to the very far right there is another blue CD icon, click on it and then go to "choose a disk file" and choose the just downloaded Ubuntu Mate 20.04 file.
#### 
![‏‏لقطة الشاشة (2026)](https://github.com/user-attachments/assets/6a580a94-f16e-4d53-a71c-e6a40f990a20)
#### 
- After doing all the previous steps, click on start at the top to begin installing and launching Ubuntu Mate 20.04 into the newly created virtual machine.
#### 
![‏‏لقطة الشاشة (2031)](https://github.com/user-attachments/assets/672d4687-169b-4806-931d-ab8c0a91956d)
####
## Installing ROS Noetic:-
After installing and launching Ubuntu MATE 20.04 on the virtual machine, click on the menu at the top left and go to "System Tools" and click on "MATE terminal" which should look like this.
####
![TERMINAL](https://github.com/user-attachments/assets/bf4598ea-e61a-450f-aa2d-ef7f834a3280)
#### 
```bash
sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
```
