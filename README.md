# Programming-Principles-and-Practice-Using-Cpp
This is the support code for Stroustrup book: "Programming: Principles and Practice using C++ (Second Edition)". 

I modified the code on his website so that it compiles on modern operating systems and compilers.

Compilation and code has been tested on Ubuntu Linux 16.04.1 and Mac OS X El Capitan (10.11.6).

## Installation
Move to your working directory and run the followin command (you need to install `git` if you did not yet):
```
git clone https://github.com/whitehatty/Programming-Principles-and-Practice-Using-Cpp.git
```

On Ubuntu Linux LTS 16.04.1 you need to install some dependencies first
```
sudo apt-get install xorg-dev libjpeg-dev
```

On Mac OS X you need to install Xcode. You also want the command line tools
```
xcode-select --install
```

Then, you need to compile FLTK, which is in the fltk-1.3.x-r11880 directory
```
cd fltk-1.3.x-r11880
make
```
If the compilation process succeded you can test FLTK
```
cd test
./demo
```

We now need to compile the exercises of the book. It should be as simple as
```
make
```

Enjoy! :-)

Give Bjarne Stroustrup an heads up so that he updates his code on the website, thanks. 
