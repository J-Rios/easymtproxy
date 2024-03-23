# Easy-MTProxy

Easy tool to simplify installation and setup of MTProxy for Telegram.

Install and use MTProxy in a single step by running a single command.

This is a BASH script that automatically gets, compile and setup MTProxy on a Debian based Linux system. It creates a systemd Service for MTProxy so you don't need to bother to make MTProxy run or recover from errors or systems restarts.

You can use it in a personal computer, a server or a Single Board Computer like a Raspberry Pi.

## Usage

1 - Simply get the script and run it:

```bash
wget https://raw.githubusercontent.com/J-Rios/easymtproxy/main/src/easymtproxy
chmod +x easymtproxy
sudo ./easymtproxy 443
```

Note: The "443" is the port that will be used by users to connect to the Proxy, you can use a different one (this Port need to be accessible in the system, so check to allow connections on firewalls).

2 - Wait until process is completed and get the result information for client connections:

```bash
MTProxy installation Completed.

Connection Information:
Host: 111.222.333.444
Port: 443
Secret: ddab2384f64e6cb12c6e52cae916e0a375
```

3 - In your Telegram App, go to the proxy settings and add that Host, Port and Secret information to it to establish the connection.
