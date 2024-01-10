# Simple Shell Project

This is a simple shell project that implements basic shell functionalities, including command execution, process identification, path resolution, error handling as well as a few other system calls. It is a project that highlights the depth and uniqueness of a shell program with respect to command inputs.

## Features

- Command execution using `fork`, `wait` and `execve`.
- Process identification using `pid` and `ppid`.
- Path resolution to find executable commands in the `PATH` environment variable.
- Basic error handling for memory allocation and other system calls.

## Getting Started

### Prerequisites

- Make sure you have a C compiler installed (e.g., GCC).
- This project uses standard library functions and should be compatible with most Unix-like systems.

### Building the Shell

This entails
- writing a program that prints the PID of the parent proces: a shell script that prints the maximum value a process ID can be. In it contains arguments without using a particular term of function (as stated in the project's prerequisites).

Creating prompts that recieves the users command or input and printing on the next line, having a Return value to know when to stop or exit (EOF).- in essence, creating a version of getline.

Creating processes to handle the: 
command syntax in the order of directories and working environments when changing
- a seperator ;,
- Operator (&&) and operator ||,
- implentation of the builtin `alias`,
- variables $? and $$,
- comment #,
- file as an input.

All of these processes come with an environment, accessing the environment comes via MAIN functions and its prototypes(parameters included).
