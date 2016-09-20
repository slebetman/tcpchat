# tcpchat

Generic TCP client and server.

## Synopsis

	tcpchat [host] [port]
	tcpchat -server [port]

## Description

`Tcpchat` opens a TCP connection and allows the user to send and receive messages from
the console. When given a host (either domain name or IP address) and port number as
argument `tcpchat` will act as a TCP client and open a connection to the specified
host and port. When given the `-server` argument and a port number `tcpchat` will act
as a TCP server waiting for connections on the specified port.

