Files are a very important thing to the Linux kernel. Everything the kernel uses is a file of some type in the filesystem. Many of these files are only kept in [[RAM]] and describe the location, status, configuration or specifications of the physical hardware.

Some important filetypes to distiguish are:

* Binary Files

* Readable Files

* Media Files

* Project Files


## Binary Files

Binary files are not meant to be read through by hand, but rather executed to perform a function. These files are usually what people think of when they think of a computer application.

Binary files can be executed by changing the [[permission|Unix Permissions]] on the file to be executable e.g. `chmod +x /path/to/file`.

System binaries and many installed programs are kept in `/usr/bin`.


## Readable Files

Many files in the Linux filesystem are simply text files. If the file can be read, then any [[text editor]] can open it. If there is write permissions then said text editor may also update the file.


## Media Files

* Audio

* Video

* PDF


## Project Files

These files are a packaged collection of files for specific programs. They contain all the information in a collection of the above formats to keep the entire project together.
