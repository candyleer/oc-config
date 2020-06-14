# Dell OptiPlex 3050

## Config

* CPU: i5-7500
* GPU: IGPU HD630 (DP+HDMI output)
* MEM: 8G x 2
* BOOT: OpenCore 0.5.9
* BIOS: 1.10.3
* OS Version: 10.15.5


## Advanced

### BIOS Setting
```
# Set DVMT to 64M
setup_var 0x795 0x2

# Set CFG Unlock
setup_var 0x4ED 0x0
```

### Dual Monitor
Add `igfxonln=1` to Boot Args.

## Tool

Use [modGRUBShell.efi](https://github.com/datasone/grub-mod-setup_var/releases) to modify BIOS DVMT and CFG LOCK



# Gigabyte Z390 Aorus Elite 

## Config
* CPU: i7-9700K
* GPU: Dataland RX 590 Plus
* MEM: CORSAIR 16G*2
* BOOT: OpenCore 0.5.9
* BIOS: Version F7(actually F7-F10c all ok now)
* OS Version: 10.15.5

## Advanced

### BIOS Setting
```
# Set CFG Unlock
setup_var_3 0x5C1 0x0
```
