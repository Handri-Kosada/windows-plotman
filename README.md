# `windows plotman`: an attempt to get plotman to work on windows

This is a tool for managing Chia based on Plotman (https://github.com/ericaltendorf/plotman)

This is a work in progress.  Please see the original version for linux for additional info:

https://github.com/ericaltendorf/plotman

Please contact me at: chia@ifhya.com


##  Known issues:

- Archiving hasn't been touched
- IO stats does nto work on windows
- Resizing terminal messes up the curses display
- Common dir prefix does not work so while dir path is shown
- Various other issues

## Installation

This program requires `psutil`, `pyfakefs`,`texttable`, `windows-curses`, `pyreadline`, `pyyaml`, and `pypsutil`.

Run commend in Windows Powershell: `python plotman.py interactive`