# TinyShell

- TinyShell is a Unix shell program that supports job control.
- The 5th lab of <a href="https://www.cs.cmu.edu/afs/cs/academic/class/15213-f15/www/schedule.html">2015 Fall: 15-213 Introduction to Computer Systems.</a>

## Files

- `Makefile`: Makefile for compiling the TinyShell program.
- `job.c`, `job.h`: Implementation and header files for job control functionality.
- `sig-handlers.c`, `sig-handlers.h`: Implementation and header files for signal handlers.
- `tiny-shell.c`, `tiny-shell.h`: Implementation and header files for the TinyShell program.
- `tsh`: Compiled executable for TinyShell.
- `tsh.c`: Main source file for the TinyShell program.
- `wrappers.c`, `wrappers.h`: Implementation and header files for utility wrappers.

## Usage

1. Compile the TinyShell program using the provided Makefile: `make`
2. Run the TinyShell program: `./tsh`
3. Use the shell by entering commands and exploring the supported features.

## Features

- Command execution: Run commands and executables.
- Job control: Manage and control multiple processes.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.
