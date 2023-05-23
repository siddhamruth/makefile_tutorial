hello:
	echo "this is the fist commsnd in hello"
	echo "this is the second command and this target has no dependencies"

# output:
# pl13@pl13:~/Documents/git/makefile_tutorial/module_2$ make
# echo "this is the fist commsnd in hello"
# this is the fist commsnd in hello
# echo "this is the second command and this target has no dependencies"
# this is the second command and this target has no dependencies

build_logger: logger.c
	cc logger.c -o logger

# output
# pl13@pl13:~/Documents/git/makefile_tutorial/module_2$ make build_logger 
# cc logger.c -o logger

build_2files: logger.c database.c
	cc logger.c -o logger
	cc database.c -o database