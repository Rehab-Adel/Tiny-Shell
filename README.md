# TinyShell

TinyShell is a Unix shell program that supports job control.

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
- Background processes: Run commands in the background.
- Foreground processes: Run commands in the foreground.
- Job control: Manage and control multiple processes.
- Signal handling: Handle signals like Ctrl+C and Ctrl+Z.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.
