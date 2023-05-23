there are 2 tyoes of variables in a shell:

make variable
shell variable

make variable is declared on the top and it will not be in any target
shell variables are defined in the target and can be accessed using the $$sign

the same is shown in the example

if you wanna run another make file from a make file the run $(MAKE) in any target after selecting corrosponding directory.