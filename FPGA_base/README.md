# FPGA_base

## Creating the project

There is a TCL file in the scripts dir that will create the project and create the block diagram for the EBAZ4205.

The project name can be modified in the top of the `scripts/make_proj.tcl` file.

To create the project open vivado and run the following commands in the TCL console:

```
cd <this dir>
source ./scripts/make_proj.tcl
```

This will create a folder containing the project which can be opened in Vivado
