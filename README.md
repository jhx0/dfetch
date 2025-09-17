# dfetch
A tiny bash script that shows some information about a running Debian/Ubuntu system.

## Why?
Well, why not?! 😆

## Running the script
```shell
$ curl -s https://raw.githubusercontent.com/jhx0/dfetch/refs/heads/main/dfetch | bash
```
**NOTE**: You can certainly also clone the repository or download the script without running it directly!

## Sample output
<img width="1161" height="901" alt="dfetch-screenshot" src="https://github.com/user-attachments/assets/ee5ad158-48bc-4ae2-9269-034db53a2fe9" />

## Hacking
The script itself is quite simple - feel free to add whatever you like or desire. 😎   
Basically, every outputed line(s) you see are implemtned as a **bash function** which calls commands like **apt** and **dpkg**.   
There are **no external dependencies** needed for running **dfetch**.
