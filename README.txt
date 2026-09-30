# Simple Socket Port Tester

A basic Python networking tool that tests whether a TCP port is open or closed on a specified target.

This project was created as a learning exercise to understand Python sockets, TCP connections, user input, and basic network troubleshooting.

## Features

- Accepts a target IP address from the user
- Accepts a port number from the user
- Creates a TCP socket connection
- Tests whether the port is reachable
- Provides a simple open/closed result

## How It Works

The program uses Python's built-in `socket` module.

The tool:

1. Creates an IPv4 TCP socket
2. Attempts to connect to the specified target and port
3. Checks the connection result
4. Reports whether the port is open or closed

## Requirements

- Python 3.x

No external libraries are required.

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Simple-Socket-Port-Tester.git