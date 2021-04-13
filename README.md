# gtk-calc

##Requirements
* install gtk+3 using `sudo pacman -S gtk3`
* install development packages using `sudo pacman -S base-devel`

##Compile and Run
* compile using `gcc -Wall -Wextra -o main main.c $(pkg-config gtk+-3.0 --cflags --libs) -export-dynamic -w `
* run using `./main`
