target1: one two
	echo $@
	echo only newer prerequesties $?
	echo $^
	touch target1
one:
	touch one
two:
	touch two

# pl13@pl13:~/Documents/git/makefile_tutorial/module_8$ make
# echo target1
# target1
# echo one
# one
# echo one two
# one two
# touch target1
# pl13@pl13:~/Documents/git/makefile_tutorial/module_8$ make
# make: 'target1' is up to date.
# pl13@pl13:~/Documents/git/makefile_tutorial/module_8$ touch one 
# pl13@pl13:~/Documents/git/makefile_tutorial/module_8$ make
# echo target1
# target1
# echo only newer prerequesties one
# only newer prerequesties one
# echo one two
# one two
# touch target1
# pl13@pl13:~/Documents/git/makefile_tutorial/module_8$ 