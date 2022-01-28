# Introduction to C and C++

## Hello C

To install vim editor
```sh
sudo apt-get install vim
```
To open a new file `test1.c` in the vim editor
```sh
vim test1.c
```
Press `i` (to go to insert mode)

Type code
```c
#include<stdio.h>
#include<conio.h>

int main()
{
	int a;
	printf("Hello world! \n");
	printf("Please enter a number: ");
	scanf("%d",&a);
	printf("Your number is %d",a);
	return 0;
}
```

Press Esc to exit writing mode, then press Shift z z to save and exit.

To compile,
```sh
gcc -o test1 test1.c
```

To run, 
```sh
./test1
```

To use user input like `scanf()` function, incase of error you will need to install ncurses library packages
```sh
sudo apt-get install libncurses5-dev libncursesw5-dev
```

Please explore more similar packages and programs.

## Hello C++


To open a new file `test1.c` in the vim editor
```sh
vim test2.cpp
```
Press `i` (to go to insert mode)

Type code
```c
#include <iostream>

//using namespace std;

int main() {
	int a;
	std::cout<<"Hello world! \n";
	std::cout<<"Please enter a number: ";
	std::cin>>a;
	std::cout<<"Your number is "<<a;
	return 0;
}

```

To compile, 
```sh
g++ -o test2 test2.cpp
```
To run, 
```sh
./test2
```

- An exercise for you to explain, why and what: Try using gcc instead of g++ to compile c++ code and explain the output or error

    (Answer: [here](https://stackoverflow.com/questions/28236870/undefined-reference-to-stdcout))


- Find out what is required to get user input in c++ and write a sample code.

     (Answer: cin)


__Exercise:__

Write a C program to create and write into a text file using FILE pointer.


__Few weblinks:__

Step by step guide: https://vitux.com/how-to-write-and-run-a-c-program-in-linux/

For a more detailed flow, please refer,

Execution flow of a C program: https://www.javatpoint.com/flow-of-c-program

__Book to explore:__

Exploring C by Yashavant Kanetkar
