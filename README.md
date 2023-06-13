# Kali Linux VM on macOS M1 (ARM64) with UTM

### Step 1 install UTM

To install UTM on your macOS M1 device, visit https://mac.getutm.app and download the UTM app, then drag it to the "Applications" folder.\
After opening UTM, click on the "Create a new virtual machine" button to proceed with setting up a new virtual machine.

![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.24.53.png "UTM")


### Step 2 Start

Select the "Virtualize" option to proceed with creating a new virtual machine in UTM.

![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.27.12.png "Virtualize")


### Step 3 Operating system

Select "Linux" as the operating system option in UTM.

![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.28.14.png "Linux")


## Step 4 Linux 

In the "Boot ISO image" section, choose the ISO file provided at https://old.kali.org/kali-images/kali-2022.2/kali-linux-2022.2-installer-arm64.iso to use as the bootable image for the Kali Linux installation.

    https://old.kali.org/kali-images/kali-2022.2/kali-linux-2022.2-installer-arm64.iso

![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.29.18.png "Boot ISO Image")


## Step 5
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.31.59.png "")

## Step 6 Hardware

In the "Hardware" section, allocate an appropriate amount of memory based on the available resources on your computer, ensuring you have enough space. Additionally, it is recommended to choose 4 cores for optimal performance.

![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.33.02.png "Hardware")

## Step 7 Storage

In the "Storage" section, allocate a storage size based on the available space on your computer. For example, if you have 32GB available, you can specify that as the size for the drive where data will be stored. Adjust the size according to your specific requirements and available resources.

![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.35.36.png "Storage")

## Step 8 Shared directory

In the "Shared directory" section, you have the option to select a directory on your macOS host system to make accessible inside the virtual machine (VM). Keep in mind that the support for shared directories can vary depending on the guest operating system you are using in UTM. It may require installing additional guest drivers within the VM. For more details and specific instructions, refer to the UTM support pages.

![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.37.02.png "Shared Directory")

## Step 9 Summary

![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.39.39.png "Summary")

## Step 10

After naming the virtual machine, you will find a button located in the top left corner resembling a gear or settings icon. Click on this button to access the settings for the virtual machine.

![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.40.35.png "settings")

## Step 11

In the "Display" settings, enable the "Retina mode" option. UTM supports retina display, which allows the virtual machine to take advantage of the high-resolution capabilities of your Mac's display, resulting in a sharper and more detailed visual experience within the virtual machine environment.

![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.42.43.png "Retina Mode")

## Step 12
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.44.25.png "Install")

## Step 13
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.45.23.png "")

## Step 14
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.45.55.png "")

## Step 15
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.46.22.png "")

## Step 16
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.48.52.png "")

## Step 17
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.49.37.png "")

## Step 18
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.50.36.png "")

## Step 19
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.52.01.png "")

### Step 20
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.53.00.png "")

### Step 21
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2020.55.12.png "")

### Step 22
Virtual Machine-ий navigation bar choose **Drive image options**
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2021.19.47.png "")

### Step 23
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2021.22.12.png "")
```bash
sudo apt update
sudo apt install spice-vdagent spice-webdavd
sudo reboot
```

### Step 24
90 болгоно
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2021.30.23.png "")

### Step 25
90 болгоно
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2021.32.36.png "")

### Step 26
90 болгоно
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2021.33.34.png "")

### Step 27
90 болгоно
![alt text](https://github.com/Munkhbadral1/Kali_Linux_arm64/blob/main/img/Screenshot%202023-06-08%20at%2021.34.20.png "")

---
