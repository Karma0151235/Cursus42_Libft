# Cursus42_libft
This repository contains the libft project from the 42 Cursus.

# Overview
Libft is the first project in the 42 Cursus. The goal is to recreate a set of functions from standard C libraries such as strlen and memchr. Additionally, the project aims to teach important concepts in memory management, pointer arithmetic, and string manipulation in C.

This project creates a library of functions to be used in future 42 projects.


# Divisions

For more information regarding the task, please refer to the Subject PDF (en.subject.pdf) in the repository. Generally, the functions are split into 3 categories, LIBC functions, Additional Functions, and Bonus Functions. Each function is written with modularity in mind. Hence, many functions reuse functions that have been written elsewhere within the same project.


# Running and Testing

In addition to functions, the repository also contains a Makefile and a header file (libft.h) as per the assignment requirement. However, these additional files serve as a quality of life improvement in the library archiving and testing processes.


## Makefile Functions


`make` - Simply makes the library, ensure that the header file (libft.h) and all required C functions are within the same directory as the Makefile.

`make clean` - Removes all object files after `make`.

`make fclean` - Removes all object files and removes libft.a (the library created from calling `make`).

`make re` - A shortcut function that allows fclean and make to be called together (`make fclean && make).


## Validation of Results

The functions have been tested through community-validated testers. To replicate the testing, ensure the tester.sh file from the Tester/ directory is within the same directory as libft. Then, call `bash tester.sh` to start the testing.

This tester encompasses 5 testers, and was found here:

https://github.com/FranFrau/Supreme-Tester-Libft?tab=readme-ov-file

However, during my pre-evaluation testing, only the following testers have been used:

| Author | Link | Active | Result |
| ------ | ---- | ------ | ------ |
| y3ll0w42 | https://github.com/y3ll0w42/libft-war-machine | ✅ | Pass |
| jtoty | https://github.com/jtoty/Libftest.git | ✅ | Pass |
| Tripouille | https://github.com/Tripouille/libftTester.git | ✅ | Pass |
| alelievr | https://github.com/alelievr/libft-unit-test.git | ❌ | N/A |
| adrossig | https://github.com/adrossig/libft_tester.git | ✅ | Pass |


# Learning Outcomes

This project validated many crucial concepts from the Piscine. Although it is quite rudimentary, it was my first time having to be compliant with good software development principles on this scale (i.e. handling edge cases, improving modularity, etc.).


# Author

**Stephen Tee**
42 Kuala Lumpur | Sunway University | Lancaster University | University of Malaya
