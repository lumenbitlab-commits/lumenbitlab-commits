# LumenBit Lab

This is my firmware portfolio. I use it to document what I build and test while learning embedded C, Embedded Linux, and STM32.

## Current progress

| Milestone | Status | What I did |
| --- | --- | --- |
| [UART loopback in C](https://github.com/lumenbitlab-commits/uart-loopback-c) | Tested | On macOS, I configured UART at 115200 baud, 8N1 using POSIX `termios`. The test sent and received `HELLO` (5 bytes) and reported `PASS`. |
| Ring buffer in C | Standalone exercise | I practiced implementing a ring buffer separately from the UART program. |
| UART and ring buffer integration | Next | Buffer incoming UART bytes and test wraparound and overflow. |

## Longer-term projects

I plan to build a Linux character device driver, explore Device Tree and board support packages, and document my STM32 work as I test it.
