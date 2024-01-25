# ModuleSim

ModuleSim is a Java GUI application for building a processor out of components (adders, registers, memory, multiplexers etc.) as taught in the computer architecture units in Computer Science at the University of Bristol.

The modules and the Hex8 processor that you can build with them were designed by [Prof. David May FREng FRS](http://people.cs.bris.ac.uk/~dave/) ([wiki page](https://en.wikipedia.org/wiki/David_May_(computer_scientist))). For a brief while, we even had a 16-bit physical version of the machine running in our building:

  - [youtube video](https://www.youtube.com/watch?v=sQM2s8UJJQw)
  - [press release](https://www.bristol.ac.uk/news/2016/november/big-hex.html)
  - [project website](https://bighexmachine.github.io/)

ModuleSim, in this repository, allows you to build a virtual Hex8/16 processor.

## Building and Using

If you are taking the relevant courses at the University of Bristol, binary (JAR) versions of ModuleSim should be distributed along with the course materials, and are preinstalled on the lab machines.

You should be able to double-click a JAR file if you have Java installed correctly. The terminal command is `java -jar JARFILENAME` where you replace JARFILENAME with the name of the file, such as `ModuleSim.jar`.

To build the application from source, run `build.sh` from any POSIX-compatible shell with the `find` binary and a JDK available (git bash on windows works just fine too).

## Module Documentation

Clone this repository and open the HTML files in `doc/workbook`. You will find:

  - components: an explanation of most components.
  - hex8: overview of the instruction set of the hex8 processor.
  - exercises: a guide to building the hex8 processor step by step, best used together with the lectures and labs for our computer architecture units (not public).
  - program: an example hex8 program that does something vaguely useful.
  - stacks: implementing a stack on hex8. The fact there is no stack pointer does not matter.