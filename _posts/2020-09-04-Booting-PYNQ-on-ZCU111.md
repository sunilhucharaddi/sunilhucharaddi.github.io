# **Booting PYNQ on ZCU111**
- download  ZCU111 pynq image from [here](http://www.pynq.io/board.html)
- extract the Zip file to get a .img image file
## For windows:
- plug in sd card
- download balenaEtcher for writing the image to sd card from [here](https://www.balena.io/etcher/)
- select the image file in the balenaetcher and select the target sd card and select flash
## For ubuntu
- plug in sd card
- Run "Disks" from your dash(search disks in ubuntu). Then from "Disks" menu select "Attach disk image...":
## boot
- after burning the imagage eject the sd card and and insert in the sd card slot(make sure the sw configuration and the power is off)
- connect the LAN of board to the port of the host computer and connect the host to the local LAN
- after this turn on the board and your device will boot
- check the ip using **ifconfig** command in the terminal
- to get into the board follow [this](https://www.youtube.com/watch?v=PaQBQkDZaks)
## reference
- [PYNQ RFsoc workshop](https://github.com/Xilinx/PYNQ_RFSOC_Workshop)
## debug problems
- if write fails while writing the image. Format the sd card and clear the partitions to make sure the entire disk space is avilabe and try writing again.
