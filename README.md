# parity_checker
### TITLE

PARITY GENERATOR

### AIM

Design and simulate 4 bit parity generator using Verilog.

### INTRODUCTION
```
A Parity Generator is a combinational logic circuit that generates the parity bit in the transmitter. On the other hand, a circuit that checks the parity in the receiver is called Parity Checker. A combined circuit or device of parity generators and parity checkers are commonly used in digital systems to detect the single bit errors in the transmitted data.
```

Even Parity and Odd Parity: 
```
The sum of the data bits and parity bits can be even or odd. In even parity, the added parity bit will make the total number of 1s an even number, whereas in odd parity, the added parity bit will make the total number of 1s an odd number.

The basic principle involved in the implementation of parity circuits is that sum of odd number of 1s is always 1 and sum of even number of 1s is always 0. Such error detecting and correction can be implemented by using Ex-OR gates (since Ex-OR gate produce zero output when there are even number of inputs).
```

### Logic diagram

![output](/Screenshot%20(1).png)

### Block diagram

![output](/1.png)

### Truth table/ Excitation table

EVEN PARITY CHECKER:

![output](/Even-Parity-Checker-Truth-Table.jpg)

ODD PARITY CHECKER:

![output](/Odd-Parity-Checker-Truth-Table.jpg)

### RTL diagram

![output](/Screenshot%20(1).png)

### Timing diagram

![output](/4.png)

### Result

The parity checker is obtained using verilog.