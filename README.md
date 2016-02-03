# bash-scripts
A collection of random bash scripts that have been of use.

## Contents 
1. handBrakeAuto - A script to batch convert movies within a directory using HandBrake transcoder on Mac

## handBrakeAuto 

### Prerequisities
Install HandBrake open source transcoder and command line interface (CLI)

https://handbrake.fr/

https://handbrake.fr/downloads2.php - (CLI) Command Line Interface

Clone handBrakeAuto script to a desired area on the Mac
Alter code for CLI installation path and point to where the CLI was installed on the machine.

```
/path/location/to/HandBrakeCLI
Ex. /Users/<name>/Desktop/HandBrakeCLI
```
### Example Usage
```
handBrakeAuto
Feed me the folder that you want converted
/some/path/that/contains/MP4
Navigating to /some/path/that/contains/MP4 ......
Found the following files for conversion in
/some/path/that/contains/ls *.MP4
file1
file2
file3 ....
All files you want converted should be the same Height & Width before proceeding
Enter Desired Width:
1920
Enter Desired Height:
1080

Begins to convert each movie
