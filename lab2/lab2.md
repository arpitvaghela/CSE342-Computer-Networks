# Lab 2 Part-1

## Follow the following instructions to run part1 of Lab2

### Step 1

Copy over the files [`client.c`](./client.c) and [`server.c`](./server.c)

### Step 2

**Compile the files**

Compiling client

```sh
gcc client.c -o client
```

Compiling server

```sh
gcc server.c -o server
```

### Step 3

Start the server in a terminal

```sh
./server
```

_Keep it running 🏃‍♂️🏃‍♂️🏃‍♂️_

> if the port is in use. Change the port in `client.c` and `server.c` and recompile.

### Step 4

Start the client in a seperate terminal

```sh
./client localhost
```

> Any into the client will be displayed at `STDOUT` of the server.
