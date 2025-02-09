## Description

This directory contains Tcl scripts for various purposes for automizing building designs, cleaning repositories, generating compile orders, controlling Xilinx tools from command line, and more.

# How to Use

Tcl scripts can be called from Tcl console in Vivado or by using make commands in command line.

Make command can be executed from the project root directory:
make src TOP=top_module.vhd

## TODO

There are some redundant and unused scripts. For example, make_new_module was created to save time, however, it is significantly buggy and I don't recommend to use it. But it is a good source for some inspiration.