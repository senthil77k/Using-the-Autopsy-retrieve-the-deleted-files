# EXP 4 : USING THE AUTOPSY RETRIEVE THE DELETED FILES

## AIM:
This experiment aims to demonstrate:

  •	Create a Disk Partition.
  
  •	Adding, deleting, and recovering files using Autopsy.
  
  •	Understanding the forensic recovery of deleted data.
  
  •	Removing the disk partition after the process.

## EQUIPMENTS REQUIRED:
  ●	Hardware: PCs

```
Register Number:212223220103
Name: Senthil Kumaran C
```

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.


## PROCEDURE:
### Step1: Create a New Disk
  •	The new Disk Partition is created
![image](https://github.com/user-attachments/assets/f3875414-29a7-41ad-851c-ac034b876a29)

### Step2: Adding and Deleting Files for Recovery
  •	Open File Explorer → Navigate to the newly created drive (C: or D:).
  
  •	Transfer images or files into it.
![image](https://github.com/user-attachments/assets/b548e2d9-260e-48fb-af9d-33eede96a418)
  
  •	Select one or more files → Press Delete.
  
  •	Empty the Recycle Bin to permanently remove them.
  
### Step3: Recovering Deleted Files Using Autopsy
1. Launch Autopsy and Set Up a New Case:
 
  •	Run Autopsy as Administrator.

  •	Click Create New Case.
  ![image](https://github.com/user-attachments/assets/2a61d108-a014-4d70-a1f4-a58f715649f4)

  •	Enter a case name (e.g., Autopsy1).
  
  •	Select a location for the case folder → Click Next → Finish.

![image](https://github.com/user-attachments/assets/478b2cf4-79c7-4399-a0b2-ca3f0b841855)
  

  •	Add optional information
  
![image](https://github.com/user-attachments/assets/b64ca531-a41c-4241-909e-1fbd9d62915a)

2. Add the Partition as Evidence:
  •	Click Add Data Source → Choose Host.
![image](https://github.com/user-attachments/assets/28b9e387-92e2-4cac-8c01-32cdfffb762e)

  •	Select Local Disk → Click Next.Create a Disk Partition.
![image](https://github.com/user-attachments/assets/1d771b96-1b12-4f29-abe1-51b592cbf3c4)

  •	Choose Disk → Select the VHD drive (Drive1).
![image](https://github.com/user-attachments/assets/e1bdaa1f-52cf-4d44-9f47-0c0a19143fd5)

  •	Click Next → Keep the default settings → Click Finish.
![image](https://github.com/user-attachments/assets/88a0c9ba-3875-437c-b0ec-9c516c3d6f66)

  •	Allow Autopsy to process the disk.

## OUTPUT: Extract Deleted Files:
  •	In the left panel, navigate to File Views → Deleted Files.
  
  •	Locate your deleted images.
![image](https://github.com/user-attachments/assets/ab5c810c-66a0-42bb-8b69-9cf26805d026)

  •	Right-click an image → Click Extract File.
  
  •	Choose a folder for saving the recovered files (e.g., C:\image_recovery).
  
  •	The deleted images are now restored!
![image](https://github.com/user-attachments/assets/600c205d-d8c7-4558-8261-2d06acb356eb)

## Removing the Disk Partition (Optional Cleanup)
1.Using Disk Management:

  •	Open Disk Management (Win + X → Disk Management).
  
  •	Identify the created partition.
  
  •	Right-click on the partition → Select Delete Volume.
  
2.Alternative Method via Settings:

  •	Click the Start button → Go to Settings.
  
  •	Select System → Click Storage.
  
  •	Click Advanced Storage Settings → Select Disks & Volumes.
  
  •	View the list of available disks.
  
  •	Select the created partition → Click Properties.
  
  •	Click the Delete option to remove it.


## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
