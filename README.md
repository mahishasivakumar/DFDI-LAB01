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


## Step3: Analysing Files using Autopsy
## 1. Install and Open Autopsy
- Download and install Autopsy from its official website.

- Open Autopsy and create a new case.

## 2. Create a Case
- Enter a case name and select a location to store the case data.
  ![Screenshot 2025-03-26 134017](https://github.com/user-attachments/assets/ba2c4341-d4be-489b-8023-27517a2359ca)


- Provide a case number and investigator details if required.

## 3. Add a Data Source
- Click "Add Data Source" and choose the type:
  ![Screenshot 2025-03-26 134115](https://github.com/user-attachments/assets/8b869c1e-ed42-45a0-962b-b6bcb9e85915)


- Select the data source and let Autopsy process it.

## 4. File Analysis
- Application 
![Screenshot 2025-03-26 134244](https://github.com/user-attachments/assets/c096e821-f9b1-4138-93ee-0b736bcab3cd)


- File Metadata
![Screenshot 2025-03-26 134320](https://github.com/user-attachments/assets/8c751f21-9b99-481a-9797-55367bd40cce)

![Screenshot 2025-03-26 134334](https://github.com/user-attachments/assets/39d51a29-a334-4d22-8e3c-a3a7fc765887)

![Screenshot 2025-03-26 134345](https://github.com/user-attachments/assets/33e2f0e6-f1ac-4234-9a72-0567024dd3b9)


- OS Account
![Screenshot 2025-03-26 134434](https://github.com/user-attachments/assets/333485a7-538a-42c2-9f05-910010b0911d)


- Generate Report
![Screenshot 2025-03-26 134509](https://github.com/user-attachments/assets/940c6f1a-634d-4d40-b656-790efcb2e39c)



## Result:
The process successfully demonstrated disk partitioning, file storage, and forensic analysis using Autopsy. The analysis provided valuable insights into file metadata and system account details.
