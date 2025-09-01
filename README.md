# EXPERIMENT--01-ALP-FOR-8086
Name :DHARSHAN R
Roll no:212224230060
Date of experiment :31/8/25





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
MOV AL,0BH
MOV BL,05H
ADD AL,BL
```


## Output  
 <img width="1916" height="1198" alt="image" src="https://github.com/user-attachments/assets/c32e0015-1512-4360-a5ff-c888c14f3c06" />

## Subtraction   of 8 bit numbers  ALP 
 ```
MOV AL,0BH
MOV BL,05H
SUB AL,BL
```
## Output  
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/1ebc96ad-48fa-467b-88fd-9a0d55b8ef43" />

## Multiplication alp 
```
MOV AL,0BH
MOV BL,05H
MUL AL
```
 ## Output  
<img width="1919" height="1192" alt="image" src="https://github.com/user-attachments/assets/a6042b6b-2a2e-4476-b21d-52b3a030891a" />


## Division alp 
```
MOV AL,0AH
MOV BL,05H
DIV BL
```
## Output  
<img width="1919" height="1196" alt="image" src="https://github.com/user-attachments/assets/67ee1060-7b2e-4b10-be84-4116db3fd766" />

## AND alp
```
MOV AL,0BH
MOV BL,05H
AND AL,BL
```
## Output
<img width="1919" height="1196" alt="image" src="https://github.com/user-attachments/assets/1c903019-2333-4560-8c5b-6f85f6fb7eaf" />

## OR alp
```
MOV AL,0BH
MOV BL,05H
OR AL,BL
```
## Output
<img width="1919" height="1198" alt="image" src="https://github.com/user-attachments/assets/ba6205f0-7e48-4722-b4f5-b17c714247eb" />

## NOT alp
```
MOV AL,0BH
MOV BL 05H
NOT AL
```
##  Output
<img width="1919" height="1189" alt="image" src="https://github.com/user-attachments/assets/165edd26-e9cc-4f24-9dc2-08d0281d5901" />

## XOR alp
```
MOV AL,0BH
MOV BL,05H
XOR AL,BL
```
## Output
<img width="1919" height="1195" alt="image" src="https://github.com/user-attachments/assets/47d4be84-1e2a-4f87-96c1-7509cde6d76a" />

## NAND alp
```
MOV AL,0BH
MOV BL,05H
AND AL,BL
NOT AL
```
## Output
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/c8184891-0833-4452-988c-c82519f168e9" />

## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








