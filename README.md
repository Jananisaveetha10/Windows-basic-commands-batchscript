![Screenshot 2025-05-30 231139](https://github.com/user-attachments/assets/e98367d0-39bd-4a31-b705-010697406c57)# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\MyLab
![Screenshot 2025-05-30 230501](https://github.com/user-attachments/assets/b171f18a-2dfa-4c42-8fe1-70920ddd9edf)


Remove the directory "my-folder"

## COMMAND AND OUTPUT
cd %userprofile%\Desktop\MyLab
![Screenshot 2025-05-30 230607](https://github.com/user-attachments/assets/719f1e93-87b8-4d2f-994b-7e7eabfb6522)




Create the file Rose.txt

## COMMAND AND OUTPUT
type nul > MyFile.txt
![Screenshot 2025-05-30 230706](https://github.com/user-attachments/assets/deb310a5-d834-486c-aa41-42d43ab6a660)




Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\Backup
![Screenshot 2025-05-30 230800](https://github.com/user-attachments/assets/90b7d5ca-022d-47d6-8e68-deaf093371db)



Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
copy MyFile.txt %userprofile%\Desktop\Backup
![Screenshot 2025-05-30 230900](https://github.com/user-attachments/assets/7b6315cb-43e3-4e74-b675-441c1249961e)



Remove the file hello1.txt

## COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\Documents
move MyLab Documents
![Screenshot 2025-05-30 230942](https://github.com/user-attachments/assets/3b2f550f-9a89-49d4-89bb-dfc8be042e8a)






## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
COMMAND:
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!







## OUTPUT
![Screenshot 2025-05-30 231139](https://github.com/user-attachments/assets/590ed871-464a-4a0e-beed-a6c709562966)

COMMAND:
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!






## OUTPUT:
![Uploading Screenshot 2025-05-30 231416.png…]()









# RESULT:
The commands/batch files are executed successfully.

