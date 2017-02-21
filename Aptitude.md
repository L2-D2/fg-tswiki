Aptitude is the default package manager found in many Debian and Ubuntu based Linux distributions.

## Usage

Aptitude will usually require elevated [[privileges]] to install or upgrade software. If you are not the `root` user, be sure to always use [[`sudo`|sudo]] when asking Aptitude to manipulate packages.

Aptitude runs on the command line via the `apt` command. When calling `apt` there are many internal commands and options to use. Check the [[manual page]] for a complete list. Some common internal commands are:

* **Install**
    * `# apt install <package>`
    * Install a package and its dependencies.
* **Reinstall**
	* `# apt reinstall <package>`
	* Reinstall a package (can sometimes fix installation errors).
* **Remove**
	* `# apt remove <package>`
	* Remove a package, but leave configuration files.
* **Purge**
	* `# apt purge <package>`
	* Remove everything from a package.
* **Update**
	* `# apt update`
	* Updates the online package list that Apt uses.
* **Upgrade**
	* `# apt upgrade`
	* Upgrades all (but actually some) of the packages installed.
* **Show**
	* `$ apt show <package>`
	* Shows detailed information about a package.
* **Search**
	* `$ apt search <keyword>`
	* Searches the package list and descriptions for keyword.
* **Help**
	* `$ apt help`
	* Prints the Apt help page to [[stdout|Standard Streams]].
