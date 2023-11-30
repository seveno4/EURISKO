# EURISKO

NOTE: Due to a bug in Medley's PROP command I had to split out Units into a new file. I'll add them back together when the bug is fixed.

With the release of Doug Lenat's [archive](https://www.saildart.org/DBL) on Saildart, [White_Flame](https://white-flame.com/am-eurisko.html) and [aindilis](https://frdcsa.org/~andrewdo/WebWiki/Landing.html) discovered the source code of both AM and EURISKO. After some work I got EURISKO up and running on Medley Interlisp.

# How to run
* Install [Medley Interlisp](https://github.com/Interlisp/medley)  

* Open an Interlisp Exec by hold right-clicking on the background and releasing on "Interlisp" in the EXEC sub-menu.  

* Change to the directory where you downloaded EURISKO  
```
cd /home/foo/EURISKO/
```
* Compile (type 'n' to any questions it asks)
```
(TCOMPL 'EUR)
```
* Load and run
```
(LOAD 'EUR.LCOM)
(Eurisko)
```

Surprisingly, it includes bitmap graphics support (made for the Xerox Alto!) that shows information about the current state of the system. I was able to port the code over to Medley which you can enable by running `(Snazzy)` after loading.  

Eurisko accepts an argument that sets how verbose the output should be. `(Eurisko 0)` for no output and `(Eurisko 100)` everything. The default value is 67.  

You can interrupt a Medley process at anytime with `CTRL-D`  

Another useful tip is that you can disable the Medley page hold, that asks for confirmation to continue on a full window of text output, by running `(PAGEHEIGHT 0)`.  Note that this value is reset when you reshape the window.  

# How to use
I'll get back to you on that one...
