# ZTP Server

This is a learning project I undertook in my time at the Linux team as a part of my apprenticeship @Aveniq.

## Key Features

ZTP Server on a Raspberry Pi.

* Chooses automatically between RedHat or Ubuntu
  * RedHat: CentOS, Fedora, RHEL, etc.

## How To Use

Clone this project onto your local machine that has Ansible installed.

Edit the inventory file and run the playbook.

```bash
# Edit tftp server
$ sudo vim /etc/default/tftpd-hpa
```

```bash
# Edit DHCP server
$ sudo vim /etc/dhcpd.conf
```