# icaur 
Extremely simple AUR PKGBUILD file downloader written in C.
## Dependencies
```
curl
cjson
```
## Usage with gcc
Compile the main.c file
```
gcc -o icaur main.c -lcurl -lcjson
```
Run the compiled file
```
./icaur
```