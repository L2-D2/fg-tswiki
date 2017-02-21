**S**ubstitute **U**ser **Do** is a command to let one user execute a command as another user. Without any arguments `sudo` will execute the subsequent command as the `root` user. This is useful for elevating privleges to run administrative commands.

Unix privileges help prevent unauthorized services or users from altering the system configuration in a malicious or catastrophic way. There are a handful of ways to elevate a user's privileges. The standard way is with use of the `sudo` command in the terminal or, if installed, `gksudo` to use a [[GTK]] graphical interface.

For these examples to work, the appropriate user must be in the `sudo` group and the group `sudo` should have access via the `/etc/sudoers` configuration file. This is probably standard in most big Linux distributions.

### Example of sudo

In a [[terminal]] a user can run `id` to list out the userid and groupid info for the current user using the [[shell]].

For an example user `tux` on an example `freekbox`:

```
tux@freekbox $ id
uid=1000(tux) gid=1000(tux) groups=1000(tux),91(video),92(audio),617(adbusers),1001(sudo),1002(steam)
tux@freekbox $ sudo id
[sudo] password for tux:
uid=0(root) gid=0(root) groups=0(root),1(bin),2(daemon),3(sys),4(adm),6(disk),10(wheel),19(log)
```


