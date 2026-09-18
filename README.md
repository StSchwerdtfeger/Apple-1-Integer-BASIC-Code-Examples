# Apple-1-Integer-Basic-Code-Examples

A small collection of code examples. The code should also be compatible with most other forms of BASIC like C64 BASIC etc.,
but I did not check... The first code example in the collection is HEX code to display possible symbols in a loop. 

I used pom1 version 1.0 to emulate the Apple 1. The emulator can be downloaded here: https://pom1.sourceforge.net/?page=downloads 

## How to run the code:

Open pom1.exe or any other emulator to open the so-called WozMon.

To open Apple 1 integer-BASIC type E000R and hit ENTER. 
The line "E000:    4c" and the ">" sign will indicate you are running integer-BASIC now. 
Now just type in the code by hand. Note that the Apple 1 does not have a BACKSPACE function! Either create a syntax error in BASIC and rewrite a line or use Ctrl + H to hard reset and Ctrl + R to reset. Some of the endless loops in the code examples can be stopped via pressing ESC. It then says STOPPED AT and names the line of the code it stopped at (see image below).

<div align="center">
<img width="350" alt="image" src="https://github.com/user-attachments/assets/ccca80f8-ea1b-469b-b5fb-455940a86446"/>
</div>


There are other ways, such as loading .txt files with the code into basic. To do so, create a .txt file with the code you want to run and place it into the pom1 folder with the pom1.exe file. 
Then press Ctrl + L, type in the file name (e.g. code.txt), press 1 for ASCII and then 1 again to simulate the code being typed... Then type RUN and hit enter... 

The official Apple 1 integer-BASIC manual can be found here: https://archive.org/details/apple1_basic_manual/page/n5/mode/2up 

Have fun running ancient code :D
