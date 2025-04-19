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
Register Number:212222040121
Name: Praveen V
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
  ![image](https://github.com/user-attachments/assets/19b59ff8-d8f8-4d0f-8d4a-5e1394c8c037)

### Step2: Adding and Deleting Files for Recovery
  •	Open File Explorer → Navigate to the newly created drive (C: or D:).
  
  •	Transfer images or files into it.
  ![image](https://github.com/user-attachments/assets/29edf11c-b7fb-49ea-9ce9-aba1215bc421)
  
  •	Select one or more files → Press Delete.
  
  •	Empty the Recycle Bin to permanently remove them.
  
### Step3: Recovering Deleted Files Using Autopsy
1. Launch Autopsy and Set Up a New Case:
 
  •	Run Autopsy as Administrator.

  •	Click Create New Case.
  ![image](https://github.com/user-attachments/assets/2a61d108-a014-4d70-a1f4-a58f715649f4)

  •	Enter a case name (e.g., Autopsy1).
  
  •	Select a location for the case folder → Click Next → Finish.

  ![image](https://github.com/user-attachments/assets/78ea718c-53a4-4512-8f3f-75538efd7d02)
  

  •	Add optional information
  
  ![image](https://github.com/user-attachments/assets/94e6ef9e-656b-4e66-b8cf-072045ba66e0)

2. Add the Partition as Evidence:
  •	Click Add Data Source → Choose Host.
  ![image](https://github.com/user-attachments/assets/aefff756-879c-4b26-93ca-866ed25736d4)

  •	Select Local Disk → Click Next.Create a Disk Partition.
  ![image](https://github.com/user-attachments/assets/f39ac8c9-89cd-42b9-b77a-ad6e69b4a54b)

  •	Choose Disk → Select the VHD drive (Drive1).
  ![image](https://github.com/user-attachments/assets/6114610a-5118-41fc-9f6c-07697c873d78)

  •	Click Next → Keep the default settings → Click Finish.
  ![image](https://github.com/user-attachments/assets/36c06665-32e1-4b85-9aca-24312320425b)

  •	Allow Autopsy to process the disk.

## OUTPUT: Extract Deleted Files:
  •	In the left panel, navigate to File Views → Deleted Files.
  
  •	Locate your deleted images.
  ![image](https://github.com/user-attachments/assets/769879a0-0209-4541-9107-eee21a1330df)

  •	Right-click an image → Click Extract File.
  
  •	Choose a folder for saving the recovered files (e.g., C:\image_recovery).
  
  •	The deleted images are now restored!
  ![image](https://github.com/user-attachments/assets/c50ac6b2-bb5e-489b-a93e-6dad4af1de2e)

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
