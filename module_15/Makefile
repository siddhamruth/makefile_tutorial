one = one $(later_variable)
two := two $(later_variable)

later_variable = later

all:
	echo $(one)
	echo $(two)

# pl13@pl13:~/Documents/git/makefile_tutorial/module_15$ make -e
# echo one later
# one later
# echo two 
# two

onee = hello
onee = $(one) there
nullstring =
two = will be$(nullstring)set

all2:
	echo $(one)
	echo $(two)