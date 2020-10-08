# Cora Z7 Hardware Repository

This repository contains Vivado projects for all demos for the Cora Z7.

For more information about the Cora Z7, visit its [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/cora-z7/start) on the Digilent Wiki.

Each demo contained in this repository is documented on the Digilent Wiki, links in the table below.

| Wiki Link | Description |
|-----------|-------------|
| [Cora Z7 Basic-IO](https://reference.digilentinc.com/reference/programmable-logic/cora-z7/demos/basic-io) | Simple hardware-only project that uses Cora Z7's RGB LED's and pushbuttons |
| [Cora Z7 Pmod-VGA Demo](https://reference.digilentinc.com/reference/programmable-logic/cora-z7/demos/pmod-vga) | Using a Pmod-VGA, a bouncing box and many test pattern bars are displayed on a connected VGA monitor. |
| [Cora Z7 XADC Analog to Digital Converter Demo](https://reference.digilentinc.com/reference/programmable-logic/cora-z7/demos/xadc) | A project that demonstrates how to use the Cora Z7's ZYNQ FPGA's analog-to-digital core (referred to as the XADC) with a ZYNQ processor |
| [Cora Z7 Petalinux Demo](https://reference.digilentinc.com/reference/programmable-logic/cora-z7/demos/petalinux) | A Petalinux project that includes different BSP features by default |

## Repository Description

This repository contains the Vivado projects and hardware designs for all of the demos that we provide for the Cora Z7. As some demos also require software sources contained in Vitis workspaces, this repository should not be used directly. The [Cora Z7](https://github.com/Digilent/Cora-Z7) repository contains all sources for these demos across all tools, and pulls in all of this repository's sources by using it as a submodule.

For instructions on how to use this repository with git, and for additional documentation on the submodule and branch structures used, please visit [Digilent FPGA Demo Git Repositories](https://reference.digilentinc.com/reference/programmable-logic/documents/git) on the Digilent Wiki. Note that use of git is not required to use this demo. Digilent recommends the use of project releases, for which instructions can be found in each demo wiki page, linked in the table of demos, above.

Demos were moved into this repository during 2020.1 updates. History of these demos prior to these updates can be found in their old repositories, linked below:
* https://github.com/Digilent/Cora-Z7-07S-Basic-IO
* https://github.com/Digilent/Cora-Z7-10-Basic-IO
* https://github.com/Digilent/Cora-Z7-07S-Pmod-VGA
* https://github.com/Digilent/Cora-Z7-10-Pmod-VGA
* https://github.com/Digilent/Cora-Z7-07S-XADC
* https://github.com/Digilent/Cora-Z7-10-XADC
* https://github.com/Digilent/Cora-Z7-07S-base-linux and https://github.com/Digilent/Petalinux-Cora-Z7-07S
* https://github.com/Digilent/Cora-Z7-10-base-linux and https://github.com/Digilent/Petalinux-Cora-Z7-10
