.EXPORT_ALL_VARIABLES:
new_contents = "hello: \n\techo \$$(cooly)"
cooly = "The subdirectory can see me!"
export cooly
test:
	echo $(cooly)
	printf $(new_contents) | sed -e 's/^ //'

one = this will work locallyexport 
export two = we can run this globally

all:
	@echo $(one)
	@echo $$one
	@echo $(two)
	@echo $$two
makefile:
	mkdir -p subdir
	@printf $(new_contents) | sed -e 's/^ //' >subdir/makefile
	@cd subdir && cat makefile
	cd subdir && $(MAKE)
clean:
	rm -rf subdir