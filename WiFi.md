## Reasons WiFi would not work:

* No WiFi card is installed.

* WiFi switch is off.

* Driver is not installed for the WiFi card.

* WiFi is out of range.

* Wireless Router is nonexistent.

* Internet service is interrupted.

## How to check WiFi card status

```
lspci -nn
```

This will list all PCI devices seen by the [[Linux]] kernel. Read the output to find which device, if any, is your wireless card.