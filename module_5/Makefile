files := file1 file2

some_file: $(files)
	@echo "see this variable" $(files)

# here some file have dependency on files file1 and file2

a := one two
b := 'one two'

print_a_b:
	echo $(a)
	printf $(a)
	echo ${b}
	printf $(b)

# output
# pl13@pl13:~/Documents/git/makefile_tutorial/module_5$ make print_a_b 
# echo one two
# one two
# echo 'one two'
# one two

# dont use "" and '' in assignment of variables in make files as its a bad prasctice. i am not sure if the data is stored as 'one two' or one two