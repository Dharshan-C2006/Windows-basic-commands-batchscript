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
```
mkdir my-folder
```

![Screenshot 2025-05-24 125419](https://github.com/user-attachments/assets/f4ad4aca-6745-41e4-a065-ff71d10461f8)


Remove the directory "my-folder"

## COMMAND AND OUTPUT
```
rmdir my-folder
```

![Screenshot 2025-05-24 125428](https://github.com/user-attachments/assets/6cb3852c-940d-4746-bc8e-03c535ce9b3e)

Create the file Rose.txt

## COMMAND AND OUTPUT
```
touch Rose.txt
```

![Screenshot 2025-05-24 125529](https://github.com/user-attachments/assets/410aa9a0-1b6d-4665-9219-104f8d1d6974)


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
```
echo "Hello, world!" > hello.txt

```


![Screenshot 2025-05-26 083310](https://github.com/user-attachments/assets/9c52ef01-60d9-423c-91ff-2653d0c1a5bb)


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
```
cp hello.txt hello1.txt

```


![Screenshot 2025-05-26 083425](https://github.com/user-attachments/assets/41934abe-5dde-4b0d-95dc-2632d9ecdf9f)


Remove the file hello1.txt

## COMMAND AND OUTPUT
```
rm hello1.txt

```
![image](https://github.com/user-attachments/assets/10ca6b1b-93fd-4c13-a0e7-b370317f83c3)



List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
```
ls hello1.txt

```
![image](https://github.com/user-attachments/assets/c8bb2dd5-a93a-4920-a9ea-19eb22602774)



List out all the associated file extensions 

## COMMAND AND OUTPUT
```
ls | awk -F. 'NF>1 {print $NF}' | sort | uniq

```
![image](https://github.com/user-attachments/assets/d64dfbef-81d2-4d65-94f7-0eaf634607aa)



Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
```
diff hello.txt rose.txt

```
![image](https://github.com/user-attachments/assets/577b5b04-e170-4ac1-a79f-a049a73fed4e)


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

