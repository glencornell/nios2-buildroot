# Linux for Altera's Max10 Develpoment Board Using Buildroot

This project provides a template to build and install an embedded
real-time (PREEMPT_RT) Linux kernel and file system image on Altera's
(now Intel's) [Max10 development
board](https://www.altera.com/products/boards_and_kits/dev-kits/altera/max-10-fpga-development-kit.html).

![MAX 10 FPGA Development Board](max_10_dev_kit_top_photo.jpg)

This project is based upon
[buildroot-sumbodule](https://github.com/Openwide-Ingenierie/buildroot-submodule),
[Altera NIOS II Linux
project](https://github.com/altera-opensource/linux-socfpga), and [a
RocketBoards
instruction](https://rocketboards.org/foswiki/Documentation/AlteraMAX1010M50RevCDevelopmentKitLinuxSetup).
I chose to extend the project by actually pulling together the three
projects together as a github project.

* [Buildroot-Submodule Instructions](doc/buildroot-submodule.md)
* [Image Creation Process](doc/max10-image-conversion.md)
