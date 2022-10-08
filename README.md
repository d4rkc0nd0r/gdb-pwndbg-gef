# Pwndbg + GEF - One for all, and all for one

This is a script which installs **Pwndbg** and **GEF** GDB plugins in a single command.

Run `install.sh` and then use one of the commands below to launch the corresponding GDB environment:

```sh
gdb-pwndbg
gdb-gef
```

> **NOTE**: This is a modified [fork](https://github.com/apogiatzis/gdb-peda-pwndbg-gef). I didn't include **PEDA** as it is not maintained by its author.

# Installation

```sh
cd ~ && git clone https://github.com/d4rkc0nd0r/gdb-pwndbg-gef.git
cd ~/gdb-pwndbg-gef
./install.sh
```

## Update

```sh
./update.sh
```
