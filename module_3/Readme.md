now syntax of make file

structure of file:

targets: prerequesties
    command 
    command

targets is the name which we call after the make command
prerequesties: these must be present in the file directory where make file exists if these are present then only the make file will compile.

prerewuesaties are also called dependencies
commands are the stps in a target that are to be performed

if no target is called when a make file is called then the first target is executed. first target is default target.

if make file is directly executed it executs 1st one ie. hello

if make build_logger is called then there is dependency on the logger.c file and in it the logger file is compiled and the object file is created

if you dont update the logger.c file and run make agsain then it will not compile. it tells that the logger is upto date and doesnt regenerate.


