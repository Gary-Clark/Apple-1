# Apple-1

This is a project to provide a couple of EPROM's for the Apple-1 computer.

Gerbers for a simple PCB to mount two 2732 EPROMs selected via T & S select lines on the Apple-1 bus. If S is mapped to E000, BASIC can be burnt into the
EPROM meaning that BASIC is available without having to load from external storage.
The RAM normally located at E000 can then be mapped to the second bank of 4k giving more RAM for programs.

The .rar file contains the plot & drill files that can be uploaded to sites such as JCLPBC for production. The remaining files are Kicad files of the board.

Also included is a PCB for a three slot riser card so that the EPROM card and the Cassette interface can be fitted inside the case (given sufficient headroom). This card does not include any buffering and has not been tested with three cards installed.
