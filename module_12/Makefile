SHELL=/bin/sh

make_var = this is make variable

all:
	echo $(make_var):
	shell_var="this is shell variablke" ;echo $$shell_var

new_contents =  "hello:\n\ttouch inside_file"

all_2:
	mkdir -p subdir
	printf $(new_contents) | sed -e 's/^ //'> subdir/makefile
	cd subdir && $(MAKE)

clean:
	rm -rf subdir


# output for for all_2
# pl13@pl13:~/Documents/git/makefile_tutorial/module_12$ make all_2
# mkdir -p subdir
# printf "hello:\n\ttouch inside_file" | sed -e 's/^ //'> subdir/makefile
# cd subdir && make
# make[1]: Entering directory '/home/pl13/Documents/git/makefile_tutorial/module_12/subdir'
# touch inside_file
# make[1]: Leaving directory '/home/pl13/Documents/git/makefile_tutorial/module_12/subdir'
