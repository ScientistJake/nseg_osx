# nseg_osx
nseg doesn't compile on mac OSX making it impossible to run RepeatModeler

Try this version.  

I edited `genwin.c`, `nseg.c`,and `genwin.h` to add either a `void` keyword at the start of the functions throwing the errors or I added that they `return FALSE;`.

## Disclaimer:  
I don't know shit about C. This was hacked together from [Repeat Modeler issue 32](https://github.com/rmhubley/RepeatModeler/issues/32). 

I made an initial commit of the original so someone smarter than me can check the changes.
