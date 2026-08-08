## Initial SSH Connection

#SSH Command

Commands: ssh

Important Flags: -p; allows you to specify the port number you want to connect through.
Why -p is important: If you have a service listening on a specific port, you can connect directly to that port. Changing the port from the default can be used to hide a service from basic automated scripts that search for common open ports(443, 80, 22, etc.)

Command Syntax: ssh -<Flag> <username>@<host-address>

*NOTE: for more help, do man ssh or ssh --help
