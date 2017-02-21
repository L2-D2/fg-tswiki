**S**ubstitute **U**ser **Do** is a command to let one user execute a command as another user. Without any arguments `sudo` will execute the subsequent command as the `root` user. This is useful for elevating privleges to run administrative commands.

Unix privileges help prevent unauthorized services or users from altering the system configuration in a malicious or catastrophic way. There are a handful of ways to elevate a user's privileges. The standard way is with use of the `sudo` command in the terminal or, if installed, `gksudo` to use a [[GTK]] graphical interface.

For these examples to work, the appropriate user must be in the `sudo` group and the group `sudo` should have access via the `/etc/sudoers` configuration file. This is probably standard in most big Linux distributions.

### Example of sudo

