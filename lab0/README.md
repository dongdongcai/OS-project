# About included files
There are five files included in the tarball: **backtrace.png**, **breakpoint.png**, **main.c**, **Makefile** and this **README**. The two png files are required by the lab0 spec. The **main.c** is the source module of this lab0, you can compile it using *make* command in terminal. **Makefile** is used to build to program and the tarball and can do some simple test as well.

# About smoke test
The test script would check the return code required in the lab0 spec, i.e. 0 for default, 1 for invalid input, 2 for invalid output and 3 for catched segment fault. The test script would also check the difference between input file and output file using *diff* command as well, the script would throw out an error and exit with return code of 1 if it fail any one of the tests metioned above.
