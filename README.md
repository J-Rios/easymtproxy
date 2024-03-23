# Easy-MTProxy

Easy tool to simplify installation and setup of MTProxy for Telegram.

Install and use MTProxy in a single step by running a single command.

This is a BASH script that automatically gets, compile and setup MTProxy on a Debian based Linux system. It creates a systemd Service for MTProxy so you don't need to bother to make MTProxy run or recover from errors or systems restarts.

You can use it in a personal computer, a server or a Single Board Computar like a Raspberry Pi.

## Usage

1 - Simply get the script, run it:

```bash
wget https://raw.githubusercontent.com/J-Rios/easymtproxy/main/src/easymtproxy
chmod +x easymtproxy
sudo ./easymtproxy 443
```

Note: The "443" is the port that will be used by users to connect to the Proxy (this Port need to be accessible in the system, so check to allow connections on firewalls).
