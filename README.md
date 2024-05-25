# Using the shell
Today, most computer users use a GUI or a Graphical User Interface to interact with their
computers. Before GUIs existed, users would use a terminal to interact with computers. In
contrast to a GUI, a terminal is text-based. A shell runs on the terminal, which will 
accept user commands.

## Navigating around
One of the most common commands is ls. It lists files and directories.

```sh
ls # Lists the current files and directories in current directory
```

Of course, it is not very useful to list files and directories without knowing
what the current directory is. The command pwd can tell you where you currently are.

```sh
pwd
```

To change the current directory, one uses the cd command:

```sh
cd ~ # ~ expands to the home directory of the current user
```

