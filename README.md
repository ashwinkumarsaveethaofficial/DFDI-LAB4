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
Register Number:212222040020
Name: Ashwinkumar S
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
 ![image](https://github.com/user-attachments/assets/ac36144c-c753-4cec-82d6-adac03ae0a7e)


### Step2: Adding and Deleting Files for Recovery
  •	Open File Explorer → Navigate to the newly created drive (C: or D:).
  
  •	Transfer images or files into it.
 ![Screenshot (151)](https://github.com/user-attachments/assets/af27a7ca-1d03-4a5b-b281-524bf9d1e5fc)

  
  •	Select one or more files → Press Delete.
  
  •	Empty the Recycle Bin to permanently remove them.
  
### Step3: Recovering Deleted Files Using Autopsy
1. Launch Autopsy and Set Up a New Case:
 
  •	Run Autopsy as Administrator.

  •	Click Create New Case.
  ![image](https://github.com/user-attachments/assets/2a61d108-a014-4d70-a1f4-a58f715649f4)

  •	Enter a case name (e.g., Autopsy1).
  
  •	Select a location for the case folder → Click Next → Finish.

 ![Screenshot (154)](https://github.com/user-attachments/assets/4dfa4267-d17b-4bad-a6c6-c132d6107498)


  •	Add optional information
  
  ![Screenshot (152)](https://github.com/user-attachments/assets/b4a7285c-3995-4683-a887-637c7d05df41)

2. Add the Partition as Evidence:
  •	Click Add Data Source → Choose Host.
  ![image](https://github.com/user-attachments/assets/5f4c6ea3-e5b6-49d6-aa65-c29deae83f88)

  •	Select Local Disk → Click Next.Create a Disk Partition.
 ![image](https://github.com/user-attachments/assets/cb97d232-fecf-4818-89ab-3abbdbf356c9)

  •	Choose Disk → Select the VHD drive (Drive1).
![Screenshot (157)](https://github.com/user-attachments/assets/76043548-2691-4b74-a39c-b764ca5a46c9)
  •	Click Next → Keep the default settings → Click Finish.
  ![Screenshot 2025-03-19 224106](https://github.com/user-attachments/assets/3feb68c2-3a3a-4e21-b3b8-11f4dfac0990)

  •	Allow Autopsy to process the disk.

## OUTPUT: Extract Deleted Files:
  •	In the left panel, navigate to File Views → Deleted Files.
  
  •	Locate your deleted images.
  ![Screenshot (160)](https://github.com/user-attachments/assets/ab94431a-e6b4-4676-a28c-c574e187e949)

  •	Right-click an image → Click Extract File.
  
  •	Choose a folder for saving the recovered files (e.g., C:\image_recovery).
  
  •	The deleted images are now restored!
 ![Screenshot (161)](https://github.com/user-attachments/assets/b650dfde-d313-4438-9bb6-e3e5c2c5eae3)

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
