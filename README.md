# Conduit

A simple multithreaded TCP chat server written in C using POSIX sockets and pthreads.

## Features

- IPv4 TCP server
- One thread per client
- Multiple clients can connect simultaneously
- Messages from one client are broadcast to others
- Clean separation of Server / Client / Utils


## Build Instructions

```bash
cmake -B build/
cmake --build build
```

## Run Instructions

### server

```bash
cd build/Server
make
./Server
```

### Client

```bash
cd build/Client
make
./Client
```
