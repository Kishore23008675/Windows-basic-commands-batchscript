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
![Screenshot 2024-05-09 231346](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/996aa656-e654-45d1-afce-81f08eda90d4)

## COMMAND AND OUTPUT
List the contents of the "MyLab" directory. cd %userprofile%\Desktop\MyLab
![Screenshot 2024-05-09 231406](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/4d479cd8-e18b-4692-a07c-a842f2609ba4)
![Screenshot 2024-05-09 231422](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/2c31c29d-3b3d-4ba0-ab99-7c0bc31992a4)


## COMMAND AND OUTPUT
Copy "MyFile.txt" to a new folder named "Backup" on the desktop. dir %userprofile%\Desktop\MyLab
![Screenshot 2024-05-09 231443](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/427501ba-d355-49c2-b06e-e7828d827bba)


## COMMAND AND OUTPUT
Move the "MyLab" directory to the "Documents" folder. mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![Screenshot 2024-05-09 231506](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/d59069e7-2f6d-4310-86dd-83bef0fd8b4a)
![Screenshot 2024-05-09 231522](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/f65c310d-8fd8-4e3b-a259-4879871b3789)



## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![Screenshot 2024-05-09 231539](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/6893bc66-c4d6-471d-ac79-a09105671374)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!


## OUTPUT

![Screenshot 2024-05-09 231554](https://github.com/Kishore23008675/Windows-basic-commands-batchscript/assets/144979375/47faa40d-4bcf-4122-9411-78d77a09a8d7)




# RESULT:
The commands/batch files are executed successfully.

