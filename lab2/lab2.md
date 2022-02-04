# Lab 2

[Instructions](https://shashi-prabh.github.io/teaching/computer_networks_2022/lab1.pdf)

## Follow the following instructions to finish part 1 of Lab2

### Step 1

Copy over the files [`client.c`](./part1/client.c) and [`server.c`](./part1/server.c)

### Step 2

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

> Any input to the client will be displayed at `STDOUT` of the server.
