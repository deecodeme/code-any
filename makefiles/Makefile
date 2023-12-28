all : say_hello greet welcome generate

say_hello: welcome greet
	@echo "Hello World!"

greet:
	@echo "Greetings from the makefile"

welcome:
	@echo "Welcome to the world of makefiles"

generate:
	@echo "Generating the file"
	touch file_generated.txt

clean:
	@echo "Cleaning the file"
	rm file_generated.txt

CC = gcc

CFLAGS = -Wall -g

hello: hello.c
	mkdir -p target/hello
	${CC} ${CFLAGS}  hello.c -o target/hello/hello

hello_clean:
	rm -rf target/hello
