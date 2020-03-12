# Professional Programming Tools for C and C++: Example Code

Code samples from the book *Professional Programming Tools for C and C++* by Anton Gerdelan and Katja Žibrek.

## Repository Structure

* This repository is split into folders, one for each code example.
* Folders are numbered after the corresponding book chapter, and then by order of appearance within the chapter.
* Code snippets from each chapter are put into a stand-alone program with a `main()` function.
* Most examples comprise just a single file called `main.c` and should be straight-forward to compile with any compiler.
Some examples have a `main.cpp` and should be compiled with a C++ compiler.
* Some examples require command line arguments to run, such as the file name of an image to open.
* See comments at the top of source code for further compilation and running instructions.

For example, to build the first assertions example with GCC and run it from a terminal:

```
cd ch1_00_assertions
gcc -o my_program main.c
./my_program
```

In Visual Studio create a new project and drag the appropriate `.c` files into your source code tree before building.

## License

Please refer to LICENSE.txt.

## Contributions and Pull Requests

Please feel encouraged to make a pull request to correct or clarify code.

Some rough guidelines for making a PR:

* Bug fixes and operating-system specific fixes are very welcome.
* When making a PR please make sure both the PR and the code is commented clearly for other book readers.
* Do not introduce code copy-pasted from elsewhere as there are licencing and copyright issues with this.
* Please do not submit CMakeLists or build scripts for the entire book or for individual chapters. There is a specific chapter dedicated to introducing build systems.
* Please do not submit project or solution files for a particular IDE.
* Code in examples is copy-pasted from the book. If the PR needs to modify these please add a comment to those lines indicating why the change was important.
* Code style and language version changes are discouraged unless they fix a bug.
