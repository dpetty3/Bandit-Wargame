# Bandit-Wargame
This repo shares all of my command resolutions to solve the wargame in Bash using SSH on macOS BigSur

Level 0 -> Level 1  
The password for the next level is stored in a file called readme located in the home directory.
Use this password to log into bandit1 using SSH. 
Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

Level 1 -> Level 2
The password for the next level is stored in a file called - located in the home directory

Level 3 -> Level 4
The password for the next level is stored in a hidden file in the inhere directory.

Level 4 -> Level 5
The password for the next level is stored in the only human-readable file in the inhere directory.
Tip: if your terminal is messed up, try the “reset” command.

Level 5 -> Level 6
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

human-readable
1033 bytes in size
not executable

Level 6 -> Level 7
The password for the next level is stored somewhere on the server and has all of the following properties:

owned by user bandit7
owned by group bandit6
33 bytes in size

Level 7 -> Level 8
The password for the next level is stored in the file data.txt next to the word millionth

Level 8 -> Level 9
The password for the next level is stored in the file data.txt and is the only line of text that occurs only once

Level 9 -> Level 10
The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.

Level 10 -> Level 11
The password for the next level is stored in the file data.txt, which contains base64 encoded data

Level 11 -> Level 12
The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions

Level 12 -> Level 13
 The password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed.
 For this level it may be useful to create a directory under /tmp in which you can work using mkdir.
 For example: mkdir /tmp/myname123. Then copy the datafile using cp, and rename it using mv (read the manpages!)
 
Level 13 -> Level 14
 The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. 
 For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. 
 Note: localhost is a hostname that refers to the machine you are working on

 Level 14 -> Level 15
 
 
 Level 15 -> Level 16
 
 
 Level 16 -> Level 17
 
 Level 18 -> Level 19
 
 
 Level 20 -> Level 21
 
 
 Level 21 -> Level 22
 
 
