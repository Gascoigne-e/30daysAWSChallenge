# AWS 30-Day Challenge - Day 7

## Overview

Today was a deep dive into the Linux operating system, marking my official switch from Windows to the Ubuntu distribution. This transition is part of my journey to align my development environment with industry standards, especially in cloud computing and DevOps. I explored the core principles, components, architecture, and file system hierarchy of Linux, along with understanding different Linux distributions and the Linux shell.

## Core Principles of Linux

- **Everything is a File:** In Linux, almost everything is treated as a file, including hardware devices and processes, allowing for a unified way of managing system resources.
- **Small, Single-Purpose Programs:** Linux philosophy emphasizes creating small programs that do one thing well, making them easier to manage and chain together for complex tasks.
- **Ability to Chain Programs:** The shell allows users to combine simple programs to perform complex operations through piping and redirection.
- **Avoid Captive User Interfaces:** Linux avoids interfaces that trap the user, promoting flexibility and the ability to work directly with the underlying system.
- **Configuration Data Stored in Text Files:** Configurations are usually stored in plain text files, making them easy to edit, backup, and manage using version control.

## Components of Linux

- **Bootloader:** The program that starts when you boot your computer and loads the operating system kernel.
- **OS Kernel:** The core of the operating system, managing system resources, hardware communication, and system calls.
- **Daemons:** Background services that start at boot or after logging in, handling tasks like networking, printing, and scheduling.
- **OS Shell:** The command-line interface where users interact with the system by typing commands.
- **Graphics Server:** The component responsible for displaying graphical output on the monitor.
- **Utilities:** Basic tools and programs that allow users to perform common tasks, like file manipulation, text editing, and system monitoring.

## Linux Architecture

- **Hardware:** The physical components of the computer.
- **Kernel:** The central part of the operating system that manages hardware, memory, processes, and system calls.
- **Shell:** The interface that allows users to interact with the kernel through commands.
- **System Utility:** The collection of essential tools and applications that facilitate various user tasks.

## Linux File System Hierarchy

- **/**: The root directory, the starting point of the Linux file system hierarchy.
- **/bin**: Essential command binaries that are needed in single-user mode and for all users.
- **/boot**: Files required for the boot process, including the kernel and bootloader configuration files.
- **/dev**: Contains device files representing hardware components.
- **/etc**: Configuration files for the system and applications.
- **/home**: Home directories for individual users.
- **/lib**: Shared libraries and kernel modules needed to boot the system and run binaries in /bin and /sbin.
- **/media**: Mount points for removable media like USB drives and CDs.
- **/mnt**: Temporary mount points for filesystems.
- **/opt**: Optional software packages.
- **/root**: The home directory for the root user.
- **/sbin**: System binaries used for system administration tasks.
- **/tmp**: Temporary files.
- **/usr**: Secondary hierarchy for read-only user data and programs.
- **/var**: Variable data files, like logs, databases, and email.

## Linux Distributions

- **Debian:** Known for its stability and primarily used for servers, Debian is the base for many other distributions, including Ubuntu.

## Linux Shell

- **User Shell Prompt:** The command prompt where a regular user can enter commands.
- **Root Shell Prompt:** The command prompt for the root user, with administrative privileges.
  
  The shell prompt can be customized to display various information, such as the current directory, username, or system status.

## Key Takeaways

- Learning about the core principles of Linux has given me a solid foundation for understanding how the OS functions.
- Exploring Linux components and architecture has helped me grasp the structure and flow of the operating system.
- The file system hierarchy was a crucial topic, as it’s essential for navigating and managing files in Linux.
- Understanding different Linux distributions and their purposes has broadened my knowledge of where and how Linux is used.
- Customizing the Linux shell to fit my workflow will make me more efficient and comfortable using the terminal.
