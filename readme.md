## Intro

A UART includes a transmitter and a reciever. The transmitter is a shift register that loads data in parallel and then shifts it out bit by bit.
The reciever shifts data bit by bit and then reassembles the recieved data stream.

The transmission starts with a start bit, 0, followed by the data bits and an optional parity bit, and ends with a stop bit, 1.

Before the transmission starts, the transmiter and the reciever must agree on a set of parameters in advance, such as number of data bits and stop bits, and use of the parity bit. 
