# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it. %userprofile%\Desktop\MyLab
![Screenshot 2024-05-14 114733](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/da0149c0-cb80-4d30-a595-0d1975a20265)

## COMMAND AND OUTPUT
List the contents of the "MyLab" directory. cd %userprofile%\Desktop\MyLab

![Screenshot 2024-05-14 114750](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/6127c56b-49f2-4b6d-b8bc-b8bb305a2bfd)


## COMMAND AND OUTPUT
Copy "MyFile.txt" to a new folder named "Backup" on the desktop. dir %userprofile%\Desktop\MyLab

![Screenshot 2024-05-14 114826](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/97d06b02-268f-449f-bf8d-9e4288d23117)

## COMMAND AND OUTPUT
Move the "MyLab" directory to the "Documents" folder. mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup

![Screenshot 2024-05-14 114849](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/a9b740c7-5247-42e7-955c-1ff2700a12b3)

![Screenshot 2024-05-14 114920](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/14ed42ac-c8ac-465f-b7ae-dddee379b04b)

## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![Screenshot 2024-05-14 115107](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/2c843f40-4326-4217-a45b-fdb35af3c1e7)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!


## OUTPUT
![Screenshot 2024-05-14 115123](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/3d9fd507-8051-4af3-88fc-14b18c73e61e)






# RESULT:
The commands/batch files are executed successfully.

