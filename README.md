# EURISKO

The source for Doug Lenat's legendary [EURISKO](https://en.wikipedia.org/wiki/Eurisko) program has at long last been [found](https://white-flame.com/am-eurisko.html) and can now be run using Medley Interlisp.

# How to run
* Install [Medley Interlisp](https://github.com/Interlisp/medley)  

* Open an Interlisp Exec by hold right-clicking on the background and releasing on "Interlisp" in the EXEC sub-menu.  

* Change to the directory where you downloaded EURISKO  
```
cd /home/foo/EURISKO/
```
* It is recommended to disable the Medley feature that asks to continue after a full page of text has been output. (This is reset on window resize)
```
(PAGEHEIGHT 0)
```
* Compile (Answer 'n' to all questions)
```
(TCOMPL 'EUR)
```
* Load
```
(LOAD 'EUR.LCOM)
```
* Enable GUI
```
(Snazzy)
```
* Run (The Eurisko function can take an argument from 0 to 100 for controlling the verbosity of output)
```
(Eurisko)
```

You can stop the EURISKO system with `CTRL-D`
