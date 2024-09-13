# EXPERIMENT--01-ALP-FOR-8086
Name : Abdur Rahman Basil A H
<br>
Roll no : 212223040002
<br>
Date of experiment :





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







# Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
mov AL,53H;
mov BL,24H;
Add AL,BL;
HLT;
```
## Output  
![Adding](https://github.com/user-attachments/assets/58d68f9a-fe55-497b-bb02-303744021ace)
## Subtraction   of 8 bit numbers  ALP 
 ```
mov AL,53H;
mov BL,24H;
sub AL,BL;
HLT;
```
## Output  
![Subtraction](https://github.com/user-attachments/assets/b09f6980-61d3-4205-97ec-07840d5c7754)
## Multiplication alp 
```
mov AL,53H;
mov BL,24H;
mul AL,BL;
HLT;
```
 ## Output  
![Multiplication](https://github.com/user-attachments/assets/be4a28e0-92cd-4a0f-b48b-35a9b4c627cf)
## Division alp 
```
mov AL,53H;
mov BL,24H;
Div AL,BL;
HLT;
```
## Output  
![Division](https://github.com/user-attachments/assets/ad9662b8-b834-4812-84d7-b99fede3a2ff)
# Programs for Logical  operations
## Logical AND:
```
mov AL,53H;
mov BL,24H;
AND AL,BL;
HLT;
```
## OUTPUT:
![AND operation](https://github.com/user-attachments/assets/52ec0ce3-61d5-4b63-ac8a-df1539d5e10a)
## Logical OR:
```
mov AL,53H;
mov BL,24H;
OR AL,BL;
HLT;
```
## OUTPUT:
![OR operation](https://github.com/user-attachments/assets/92e9f05d-6f80-4874-babf-be2d26b5462b)
## Logical NOT:
```
mov AL,53H;
not AL;
HLT;
```
## OUTPUT:
![NOT operation](https://github.com/user-attachments/assets/e4361323-edd2-4d57-9428-959010f2c482)
## Logical XOR:
```
mov AL,53H;
mov BL,24H;
XOR AL,BL;
HLT;
```
## OUTPUT:
![XOR operation](https://github.com/user-attachments/assets/3150fb06-3795-4af8-9b76-739278e36b26)
# Programs for Logical  operations
## Logical AND:
```
mov AL,53H;
mov BL,24H;
AND AL,BL;
HLT;
```
## OUTPUT:
![and](https://github.com/user-attachments/assets/b5448f83-deda-48c8-9425-4b5d4174c3d3)
## Logical OR:
```
mov AL,53H;
mov BL,24H;
OR AL,BL;
HLT;
```
## OUTPUT:
![or](https://github.com/user-attachments/assets/65e8d509-b3a0-423a-8882-9867344257f1)
## Logical NOT:
```
mov AL,53H;
not AL;
HLT;
```
## OUTPUT:
![not](https://github.com/user-attachments/assets/ff8d7f43-27e7-44a9-bb58-206b96071641)
## Logical XOR:
```
mov AL,53H;
mov BL,24H;
XOR AL,BL;
HLT;
```
## OUTPUT:
![xor](https://github.com/user-attachments/assets/bf2a2a58-c343-4211-a184-0430dfa41354)
## Result :
Thus the program for arithmetic operations and logical operations are complete
