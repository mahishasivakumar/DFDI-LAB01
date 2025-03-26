# Analysing the Disk Files

```
Register Number : 212222040095
Name : Mahisha S
```
## AIM:

The primary aim of this report is to demonstrate the process of creating a disk partition, adding files, and analyzing them using Autopsy, a digital forensic tool.

## Step1: Creating a Disk Partition
## 1.Open File Manager

- Right-click This PC → Click Show More Options.
  ![Screenshot 2025-03-19 220523](https://github.com/user-attachments/assets/8a7b99d9-bd5d-4b41-ad35-6d1301b5ff82)

- Select Manage.
  ![Screenshot 2025-03-19 220537](https://github.com/user-attachments/assets/df827a18-3894-4dbd-bbd3-a1b6eb8ae0b8)


## 2.Access Disk Management

- In the new window, select Disk Management.
  ![Screenshot 2025-03-19 220639](https://github.com/user-attachments/assets/9652e198-abd8-4f45-a689-a20f248bac2d)


## 3.Shrink the C Drive to Allocate Space

- Locate C: drive → Right-click → Select Shrink Volume.

- Enter the amount of memory to allocate for the new disk.

- Click Shrink.
  ![Screenshot 2025-03-20 094902](https://github.com/user-attachments/assets/f9ea27b3-79e2-4531-bf34-3e680e869330)



## 4.Create a New Volume

- Right-click on the newly unallocated space → Select New Simple Volume.
  ![Screenshot 2025-03-20 095001](https://github.com/user-attachments/assets/27b2fd03-4ca4-41f7-be83-294f5b0222ca)



- Follow the wizard and assign a disk name.
  ![Screenshot 2025-03-20 095037](https://github.com/user-attachments/assets/40a27a4b-1abc-4fbc-b630-ca1c537757e1)



- Click Finish to complete the process.
  ![Screenshot 2025-03-20 095054](https://github.com/user-attachments/assets/bf8de9fb-713c-42b5-88fb-7c3f3282450e)

  
- The new Disk Partition is created as **MAHISHA S**.
  ![Screenshot 2025-03-20 095119](https://github.com/user-attachments/assets/fa6779d1-c6e5-4a7b-a8b5-a6dab3b6b290)


  
## Step2: Adding and Deleting Files for Recovery

## 1. Copy Files to the Partition:

- Open File Explorer → Navigate to the newly created drive (C: or D:).

- Transfer images or files into it.
![Screenshot 2025-03-20 100942](https://github.com/user-attachments/assets/1fde9b34-b001-4db1-8bb6-599498ec6791)




## 2. Delete Files:

- Select one or more files → Press Delete.

- Empty the Recycle Bin to permanently remove them.

## Step3: Recover
- Use the Autopsy or sleuthkit tool to recover these files.

## Result:
The process successfully demonstrated disk partitioning, file storage, and forensic analysis using Autopsy. The analysis provided valuable insights into file metadata and system account details.
