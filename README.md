# EURISKO

NOTE: Due to a bug in Medley's PROP command I had to split out Units into a new file. I'll add them back together when the bug is fixed.

With the release of Doug Lenat's [archives](https://www.saildart.org/DBL) on Saildart, [White_Flame](https://white-flame.com/am-eurisko.html) and [aindilis](https://frdcsa.org/~andrewdo/WebWiki/Landing.html) discovered the source code of both AM and EURISKO. After some work I got EURISKO up and running on Medley Interlisp.

# How to run
1. Install [Medley Interlisp](https://github.com/Interlisp/medley)
2. Open an Interlisp Exec by hold right-clicking on the background and releasing on "Interlisp" in the EXEC sub-menu.
3. Change to the directory where you downloaded EURISKO
```
cd /home/foo/EURISKO/
```
4. Load and run
```
(LOAD 'EUR.LCOM)
(Eurisko)
```
`(Eurisko 0)` for much less verbose output.  
`CTRL-D` interrupts execution.  
`(PAGEHEIGHT 0)` turns off Medley's page hold so it stops asking you to continue on a full window of text. This resets if you resize the window.  

# How to use
I'll get back to you on that one...
