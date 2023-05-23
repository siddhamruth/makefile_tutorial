what is a make file?
it is used to compile all the .c and .h files in single shot and helps to reduce the effort to include files for compilation all tuime

simple make file is as follows

a make file must be named only as one of the following:
GNUmakefile, makefile and Makefile. 

Recommended is Makefile

a make file prints each command inside the make file and then executes the command.

open terminal and type make to conform make is installed in the system

we need to use only tabs in the makefiles. if u use spaces it will not work as i read

make file prints the command its executing.
to supress this we need to append @fefore the line. see in the make file    
https://www.baeldung.com/linux/makefile-suppress-command-echo