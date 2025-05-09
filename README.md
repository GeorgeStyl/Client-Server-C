# Simple Mail Client-Server in C

This is a simple mail system implemented in C using a client-server architecture. The client sends messages to the server, which stores and processes them using plain `.txt` files.

The communication is simulated using two text files:
- `george-sms.txt` (written by the client)
- `kyriakos-sms.txt` (read and stored by the server)

This was developed as part of a **group university project** to understand basic inter-process communication, file I/O, and client-server interaction principles in C.

## Compilation

To compile client and server programs:
```bash
gcc -o client client.c
gcc -o server server.c
```
