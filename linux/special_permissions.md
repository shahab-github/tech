### Special Permissions in Linux
**umask**: Umask (user file-creation mode mask) is a command in Linux that sets and displays the default permissions for newly created files and directories.
The default creation permissions for files are **666** and for directories **777**


To make the changes permanent, set the new umask value in a global configuration file like /etc/profile file which will affect all users or in a user’s shell configuration files such as ~/.profile, ~/.bashrc or ~/.zshrc, which will affect only the user. The user files have precedence over the global files.
For more details visit here [umask](https://linuxize.com/post/umask-command-in-linux/)
