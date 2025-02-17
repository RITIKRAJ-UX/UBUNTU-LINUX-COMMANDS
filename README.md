# UBUNTU-LINUX-COMMANDS
Ubuntu Linux, like other Linux distributions, has a wide range of commands that you can use in the terminal. Here are some of the main commands that are commonly used:

### File and Directory Management
- **`ls`**: List files and directories in the current directory.
- **`cd [directory]`**: Change the current directory to the specified directory.
- **`pwd`**: Print the current working directory.
- **`mkdir [directory]`**: Create a new directory.
- **`rmdir [directory]`**: Remove an empty directory.
- **`rm [file]`**: Remove a file.
- **`rm -r [directory]`**: Remove a directory and its contents recursively.
- **`cp [source] [destination]`**: Copy files or directories.
- **`mv [source] [destination]`**: Move or rename files or directories.
- **`touch [file]`**: Create an empty file or update the timestamp of an existing file.

### File Viewing and Editing
- **`cat [file]`**: Display the contents of a file.
- **`less [file]`**: View the contents of a file one screen at a time.
- **`nano [file]`**: Open a file in the Nano text editor.
- **`vim [file]`**: Open a file in the Vim text editor.

### System Information
- **`uname -a`**: Display system information.
- **`top`**: Display running processes and system resource usage.
- **`htop`**: An improved version of `top` (may need to be installed).
- **`df -h`**: Show disk space usage.
- **`free -h`**: Show memory usage.
- **`uptime`**: Show how long the system has been running.

### Package Management (APT)
- **`sudo apt update`**: Update the package list.
- **`sudo apt upgrade`**: Upgrade installed packages to their latest versions.
- **`sudo apt install [package]`**: Install a new package.
- **`sudo apt remove [package]`**: Remove an installed package.
- **`sudo apt search [package]`**: Search for a package.

### User Management
- **`adduser [username]`**: Add a new user.
- **`deluser [username]`**: Delete a user.
- **`passwd [username]`**: Change a user's password.
- **`whoami`**: Display the current logged-in user.

### Networking
- **`ping [hostname]`**: Check connectivity to a host.
- **`ifconfig`**: Display network interface configuration (may require `net-tools`).
- **`ip a`**: Display network interface configuration (modern alternative to `ifconfig`).
- **`curl [url]`**: Transfer data from or to a server using various protocols.

### System Control
- **`shutdown now`**: Shut down the system immediately.
- **`reboot`**: Restart the system.
- **`logout`**: Log out of the current session.

### Miscellaneous
- **`man [command]`**: Display the manual page for a command.
- **`history`**: Show the command history.
- **`clear`**: Clear the terminal screen.

### File Permissions
- **`chmod [permissions] [file]`**: Change the permissions of a file or directory.
- **`chown [user]:[group] [file]`**: Change the owner and group of a file or directory.
