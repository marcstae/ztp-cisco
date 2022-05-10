# ZTP Server

This is a learning project I undertook in my time at the Linux and Networking team as a part of my apprenticeship @Aveniq.

## Key Features

ZTP Server on a Raspberry Pi.

* Automatically configures Cisco switches
  * Catalyst 9300

## How To Use

Connect switch with an ethernet cable to the Pi and wait until it finished the configuration.

```bash
# Edit tftp server
$ sudo vim /etc/default/tftpd-hpa
```

```bash
# Edit DHCP server
$ sudo vim /etc/dhcpd.conf
```