# py_virtual_modbus
Virtual MODBUS processor

This is virtual MODBUS device with user defined input, output, holding registers and processors to read and write information in registers.

Definition (yaml file):


Input registers

Output registers

Processors


Processor definition:

Input registers

Output registers

Functions


Function definition

Input

Output

Actions to process information


Listen for configured MODBUS TCP devices ID

When some of input registers is changed save value and perform configured processing to set output registers.
