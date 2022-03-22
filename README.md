# CLI-atlibby

(program and README edited after submission)

This is a small CLI program written in the D language.

This program takes CL arguments passed in by the user and calculates the average length of each argument.

## Installation (Mac OSX)

The simplest way (at least in my experience) to install and set up D on a Mac OS would be to
open the terminal and type in this command:

*curl -fsS https://dlang.org/install.sh | bash -s dmd*

This installs the DMD compiler for D onto your device. Once installed, open up a new file in a text editor of your choice
(I used Geany) and begin coding!

Important note: Files writted in D end in the file extension .d

## Program Compilation and Running (Mac OSX)

To compile using DMD, open terminal and navigate to the directory in which your .d project file is located. In this case, we will be
running and using dlang_program.d. Type this command into the terminal:

*dmd dlang_program.d*

After which you will press the RETURN key and type this into the CL to run your program (be sure to include CL arguments next to this command so the 
program can do its magic):

*./dlang_program*

## Example Usage

*./dlang_program CS120 is fun*  
*You wrote 3 arguments.*

*Each argument has an average of 5 characters.*
