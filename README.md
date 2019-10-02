# TC-100
A High-Tech Conky Theme in four colors: white, blue, green and red.
![Screen01](https://user-images.githubusercontent.com/9018264/66082903-89db5b00-e541-11e9-8ec8-a2d677674427.png)

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
## Execute
Find out the name of the network device you want to monitor (use the commands "ip a" or "ifconfig") and copy the device name as in the image below:
![Terminal](https://user-images.githubusercontent.com/9018264/66083822-8517a680-e543-11e9-8d7a-50e2c4b52fb4.png)
Open the **tc100*** file (or file according to the color you choose) and on lines 65, 66, 68, 69, and 72 replace the local network interface lo with the previously copied network device:
![Editor](https://user-images.githubusercontent.com/9018264/66083907-bb552600-e543-11e9-910c-897600c06f10.png)
## Screens
![Screen02](https://user-images.githubusercontent.com/9018264/66082906-8c3db500-e541-11e9-8f7c-459bcf581e26.png)
![Screen03](https://user-images.githubusercontent.com/9018264/66082911-8e077880-e541-11e9-89db-4e57d65efe94.png)
![Screen04](https://user-images.githubusercontent.com/9018264/66082912-8fd13c00-e541-11e9-8e16-152b06344b62.png)
![Screen05](https://user-images.githubusercontent.com/9018264/66082918-92339600-e541-11e9-93c1-0106e4f0a84d.png)
![Screen06](https://user-images.githubusercontent.com/9018264/66082921-9495f000-e541-11e9-837a-55988ed8dbb5.png)
