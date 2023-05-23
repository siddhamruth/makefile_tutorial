objects := test1.o test2.o test3.o

all : $(objects)

# noe if we wanna compile all the files we can declare and do like this

test1.o : test1.c
test2.o : test2.c 
teat3.o : test3.c 

test1.c:
	echo "int main() { return 0; }" >test1.c

t%.c:
	touch $@

clean:
	rm -f *.c *.o all