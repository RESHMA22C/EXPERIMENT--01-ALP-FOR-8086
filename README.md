# EXPERIMENT--01-ALP-FOR-8086
# Name : Reshma C
# Roll no : 21222304168
# Date of experiment : 19-08-2025





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
~~~
Mov AL,74H
MOV BL,69H
ADD AL,BL
HLT
~~~

## Output  

<img width="1015" height="536" alt="Screenshot 2025-08-19 142622" src="https://github.com/user-attachments/assets/877f5d81-3cce-44f7-b422-c6826926c001" />

 
## Subtraction   of 8 bit numbers  ALP 
~~~
Mov AL,74H
MOV BL,69H
SUB AL,BL
HLT
~~~
## Output  

<img width="1348" height="684" alt="image" src="https://github.com/user-attachments/assets/71848e42-5429-46e7-8e3e-b405671cb039" />


## Multiplication alp 
~~~

org 100h
Mov AL,74H
MOV BL,69H
MUL BL
HLT
ret
~~~
 ## Output  

<img width="1017" height="525" alt="image" src="https://github.com/user-attachments/assets/f578dbae-7194-4973-b379-6f5b7ce2f6e1" />


## Division alp 
~~~
MOV AL,68H
MOV BL,18H
DIV BL
HLT
~~~
## Output  

<img width="1012" height="520" alt="image" src="https://github.com/user-attachments/assets/db3e1863-f3fc-4cc7-b7c8-e7ed3a3f723a" />

# And of 8 bit numbers ALP

~~~
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
~~~

# Output


<img width="1010" height="550" alt="image" src="https://github.com/user-attachments/assets/45a74cbd-7f16-4046-a700-b3dc2cdc8c98" />


# OR of 8 bit numbers ALP
~~~
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
~~~

# Output


<img width="1035" height="556" alt="image" src="https://github.com/user-attachments/assets/43225625-c58f-4223-8880-9b0ce4f35819" />

# NOT of 8 bit number ALP
~~~
MOV AL,65H
NOT AL
HLT
~~~
# Output


<img width="1028" height="525" alt="image" src="https://github.com/user-attachments/assets/13e8d66c-112c-4151-ab54-5ded2ef2bb32" />

# XOR of 8 bit number ALP
~~~
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
~~~
# Output:

<img width="1034" height="547" alt="image" src="https://github.com/user-attachments/assets/67a7bd4b-cba4-4de9-975d-ed104793471b" />

## Result :

 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.






