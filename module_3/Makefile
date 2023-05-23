build_1: logger.c
	cc logger.c -o logger
	echo"this will always run but this runs after the dependency of logger.c s existanse"
# if the logger.c is not there then this will trigger the logger.c target and then it executes the next line
# if the logger.c is there already then it runs directly
logger.c: database.c
	cc database.c -o database

#ouutput is error as 
# cc logger.c -o logger
# echo"this will always run but this runs after the dependency of logger.c s existanse"
# /bin/sh: 1: echothis will always run but this runs after the dependency of logger.c s existanse: not found
# make: *** [Makefile:3: build_1] Error 127


build_2: logger_2.c
	cc database.c -o database
	@echo "build_2 executed"
#this runs second

logger_2.c:
	echo "int main() {return 0;	}" >logger_2.c 
	@echo "logger_2 executed"
#this runs 1st

# output
# build_2 executed
# pl13@pl13:~/Documents/git/makefile_tutorial/module_3$ rm logger_2.c 
# pl13@pl13:~/Documents/git/makefile_tutorial/module_3$ make build_2
# echo "int main() {return 0;     }" >logger_2.c 
# logger_2 executed
# cc database.c -o database
# build_2 executed
