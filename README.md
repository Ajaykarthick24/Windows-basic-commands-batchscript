# Windows-basic-commands-batchscript
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

<img width="893" height="166" alt="img 1" src="https://github.com/user-attachments/assets/0fe6115b-f220-4d55-9910-7c04fc9383ae" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="877" height="122" alt="img 2" src="https://github.com/user-attachments/assets/c03560b3-0229-4fd9-98bf-bef4ee51758e" />

Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="887" height="365" alt="img 3" src="https://github.com/user-attachments/assets/54746d4e-d585-4253-b9fc-36ec362ba7a0" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="977" height="170" alt="img 4" src="https://github.com/user-attachments/assets/2d577224-308c-421e-93ac-336b771879ad" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="947" height="132" alt="img 5" src="https://github.com/user-attachments/assets/35f3089d-b706-4f3e-82d0-1e62a5c488dc" />

Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="857" height="50" alt="img 6" src="https://github.com/user-attachments/assets/9cd40069-fbb6-4617-8f97-5166fdc7b66d" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="825" height="182" alt="img 7" src="https://github.com/user-attachments/assets/4e446869-f683-4819-ad01-005e9faa08e3" />

List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="468" height="608" alt="img 8" src="https://github.com/user-attachments/assets/af30242f-2f25-4f8e-bf3c-f446755d6397" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="882" height="197" alt="img 9" src="https://github.com/user-attachments/assets/749f895e-d725-4073-9ee4-01c2e95c14ac" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="673" height="76" alt="img 10" src="https://github.com/user-attachments/assets/d6dc9e95-b167-457f-87c2-3e03ce942a0a" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="767" height="230" alt="img 11" src="https://github.com/user-attachments/assets/414b2eb5-829f-41b8-8e00-3c28545336d4" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="767" height="230" alt="img 11" src="https://github.com/user-attachments/assets/6065c4c5-c671-4ce7-ad9d-cf24f557093a" />

Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="767" height="230" alt="img 11" src="https://github.com/user-attachments/assets/f8941e92-ab7c-4a44-8ab3-fbb6dfd7f3d2" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="791" height="417" alt="img 14" src="https://github.com/user-attachments/assets/678bb930-7b77-45e7-83ff-289dc0dc8a7e" />

# RESULT:
The commands/batch files are executed successfully.

