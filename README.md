# Disk_Forensics_ExtractDiskDrive_AutoPSY

# About Autopsy Tool :
The Sleuth Kit is a library and a collection of command-line tools used to investigate disk images. Autopsy is the GUI program for TSK. The results of the forensic search carried over the images are displayed here. These results help the investigator to locate relevant sections of data in their investigation. It is used by law enforcement, military, and corporate examiners to investigate the actions taken place on the evidence computer, however, it can be used to recover deleted data from digital devices too.

Autopsy performs operations onto disk images which can be created using tools like FTK Imager.  Here an already created image is used.
Download link -> https://www.autopsy.com/download/

# Step to Extract Data from Disk Drive ->
________________________________________________________________________________________________________________________________________________________________________
# 1. Getting Started
Open Autopsy and create a new case.

![image](https://user-images.githubusercontent.com/62438853/230049556-03dace22-cd62-4870-8018-faf444e71748.png)

Click on Finish after completing both the steps.

# 2. Add a data source.
Select the appropriate data source type.

![image](https://user-images.githubusercontent.com/62438853/230049626-d66dd884-ca42-4ba6-b4a9-8102ad4e4264.png)

Disk Image or VM file: Includes images that are an exact copy of a hard drive or media card, or a virtual machine image.
Local Disk: Includes Hard disk, Pendrive, memory card, etc.
Logical Files. : Includes local folders or files.
Unallocated Space Image File: Includes files that do not contain a file system but need to run through ingest.
The data source used here is a disk image. Add the data source destination.

![image](https://user-images.githubusercontent.com/62438853/230049721-122fbc04-ba46-40d8-a5de-f8e693bae3cc.png)

Configure ingest modules.

![image](https://user-images.githubusercontent.com/62438853/230049780-b1ccff33-0f71-4ad4-9d0c-0a5df4f3d12b.png)

Select all that will serve the purpose of your investigation and click Next. Once the data source is added, click Finish. It will take some buffer time to extract and analyze the data depending upon the size of the Data Source.

# 3. Exploring the data source:

The Data Source information: Here the basic metadata is shown. A detailed analysis is displayed in the bottom section. These details can be extracted in the form of Hex values, Results, File Metadata, etc.
![image](https://user-images.githubusercontent.com/62438853/230049984-4c309d84-c18c-43b6-ab53-b15df9cab7d2.png)
