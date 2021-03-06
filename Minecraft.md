Minecraft is a fantastic, extensively moddable, voxel stylized world simulator with monsters. Minecraft is sold through [[Minecraft.net|https://minecraft.net/en-us/]], and the `.jar` [[binary file|filetypes#binary-files]] can be downloaded there once purchaed.

## Running Minecraft from Official Binary

The Java Archive binary is run via the Java Runtime Environment. To obtain the JRE on a Ubuntu based distribution, you can use the following commands:

```
$ sudo apt update
$ sudo apt install default-jre default-jdk
```

To run Minecraft after installing the JRE and JDK: `java -jar /path/to/minecraft.jar`. 

## Installing from Package Manger

The Minecraft launcher is also packaged in some distributions and can be installed using the provided [[package manager|aptitude]]. In Linux Mint, the Minecraft installer can be downloaded from the Software Manager. 

### Obtaining installer from Community hosts
You might still obtain an installer from the [[Linux Mint Community page|https://community.linuxmint.com/software/view/minecraft-installer]]. Once downloaded the package can be installed either through right clicking and opening with the `GDebi Package Installer` or using `$ sudo dpkg -i /path/to/minecraft-installer.deb`.

Both the community installer and the package manager will create a menu launcher.
