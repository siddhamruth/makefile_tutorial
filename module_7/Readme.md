wht is a wildcard?

* is a wildcard used to search for the matching string

it must be uised  in wildcard function only

if used directly it will not work.

$ must be used for wildcard like $(wildcard *.c) prints all the c files in the folder

we can assign values also with wildcard

if we want to store alll names of .c files in a varaible files_c then?
 files_c := $(wildcard *.c)

 % wildcard

 % -- used in matching mode and called stem
 % -- used in replacing mode takes stem that mached and replaced in string

 

 i ddidnt understand reg this properly. will get back and update  this one.