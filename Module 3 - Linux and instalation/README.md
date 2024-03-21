Installing Ubuntu Server

    Download the Installation Media: Head to the official Ubuntu Server download page https://ubuntu.com/download/server and choose the latest Long Term Support (LTS) version. Download the 64-bit server image (.iso file).

    Prepare Your System: You can install Ubuntu Server on a physical machine or a virtual machine. Ensure your system meets the minimum hardware requirements listed on the download page.

    Boot from the Installation Media: Burn the downloaded ISO file to a DVD or create a bootable USB drive using tools like Rufus. Boot your system from the prepared media.

    Follow the Installation Wizard: The installation process is user-friendly. Here's a basic overview:
        Choose your preferred language.
        Select your keyboard layout.
        Configure your network connection (wired or wireless).
        Set a strong password for the root user.
        Optionally, create a non-root user account for everyday tasks.
        Choose the type of installation (minimal or server with graphical desktop).
        Select the software packages you want to install (e.g., OpenSSH server for remote access).
        Review your configuration and start the installation.

    Post-Installation Tasks: After the installation finishes, you'll be prompted to reboot. Once rebooted, log in with your chosen username and password. It's recommended to:
        Update the system packages: sudo apt update && sudo apt upgrade
        Secure the server by setting up a firewall (e.g., UFW).

Basic Linux Commands Documentation

    File Navigation:
        cd <directory>: Change directory.
        ls: List directory contents.
        pwd: Print working directory (your current location).
        mkdir <directory>: Create a new directory.
        rmdir <directory>: Remove an empty directory.
        mv <source> <destination>: Move or rename a file/directory.
        cp <source> <destination>: Copy a file/directory.
        rm <file>: Remove a file (use with caution!).

    Permissions:
        chmod <permissions> <file>: Change file permissions (e.g., chmod 755 myfile makes the file executable for everyone).
        chown <owner>:<group> <file>: Change file ownership.

    Viewing Files:
        cat <file>: Display the contents of a text file.
        less <file>: View a file content page by page (useful for large files).
        more <file>: Similar to less, but navigates forward only.

    Managing Processes:
        ps aux: List all running processes.
        top: Monitor system processes (CPU, memory usage).
        kill <pid>: Terminate a process by its process ID (PID).

    Networking:
        ping <hostname/IP>: Test network connectivity to a host.
        ifconfig: Display network interface details (IP address, etc.).
        netstat -antup: List network connections and listening ports.

    Package Management:
        sudo apt update: Update package lists.
        sudo apt install <package>: Install a software package.
        sudo apt remove <package>: Remove a software package.

    Getting Help:
        man <command>: Display the manual page for a specific command.

This is a basic list to get you started. There are many more commands available in Linux. Consider exploring the man pages for detailed information on each command and its options.
