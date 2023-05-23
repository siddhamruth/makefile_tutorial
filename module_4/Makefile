#clean is not recommended to be the first command in make file as it will be a default command then.
# clean must not be a default command as it can be easily misused

logger: 
	touch logger.c

clean:
	rm -f logger.c

# output
# pl13@pl13:~/Documents/git/makefile_tutorial/module_4$ make clean 
# rm -f logger.c
# pl13@pl13:~/Documents/git/makefile_tutorial/module_4$ make
# touch logger.c
# pl13@pl13:~/Documents/git/makefile_tutorial/module_4$ ls
# logger.c  Makefile  Readme.md
# pl13@pl13:~/Documents/git/makefile_tutorial/module_4$ make clean
# rm -f logger.c