# Audible Ping
Audible Ping tool.

This can be useful when fiddling with network cables to find loose
connections without having to look at the screen.

This is a wrapper around the real "ping" command that will parse the output to
find out whether packets were missing.

## Requirements

- python >= 2.7.3
- pexpect
- pygame (for playing sounds, not the best choice but playing sounds in python is hard)

This was only tested on Linux (openSUSE 12.3).

## Usage

Run "aping" with the usual ping arguments.

    ./aping [ping_arguments]

For example:

    ./aping 192.168.1.1

