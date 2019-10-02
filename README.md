# TC-100
A High-Tech Conky Theme in four colors: white, blue, green and red.

## Requirements
- Conky installed
## Install
Download and extract the project in your system.
Copy the content of the folder **fonts/** to the directory **~/.fonts/**
```shell
cp fonts/* ~/.fonts/
```
Copy the folder **TC-100** for the directory **~/.conky/**
```shell
cp TC-100/ ~/.conky
```
## Execute
To run the conky theme, choose a color and run the commands:
For the default color (white):
```shell
conky -q -c ~/.conky/TC-100/tc100
```
For the blue color:
```shell
conky -q -c ~/.conky/TC-100/tc100-blue
```
For the green color:
```shell
conky -q -c ~/.conky/TC-100/tc100-green
```
For the red color:
```shell
conky -q -c ~/.conky/TC-100/tc100-red
```
**Note:** just run one of the commands to not overwrite the previous theme.
