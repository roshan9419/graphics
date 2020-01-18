# graphics
In this repository I have uploaded graphics library files which enables you to use graphics in your system. 

Copy the "libbgi.a" in this location::::::
C:\Program Files (x86)\CodeBlocks\MinGW\lib

Copy the "graphics.h" and "winbgim.h" in this location::::
C:\Program Files (x86)\CodeBlocks\MinGW\include

In CodeBlocks follow these steps:
Settings --> Compiler --> Linker Settings

In Link Libraries: Click on "Add" Button and select the "libbgi.a" file from that location
where you paste this in previous steps...

In Other linker options: Copy the below line and Paste and press OK 
-lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32

That's all, hope your program will run properly :)
