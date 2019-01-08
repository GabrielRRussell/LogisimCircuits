# Project Savannah
Project Savannah is a custom CPU that I built in Logisim. It's designed to run simple code, and is planned to have a whole reach of features. For those who don't know what Logisim is, it's a program that allows you to design custom circuitry. Many people design their own computers and hardware inside of it. My goal is to build a custom 32 Bit processor. 

Repo Link: https://github.com/GabrielRRussell/LogisimCircuits/tree/master/ProjectSavannah

Completed Features:

> Code Execution

> 32 Registers and RAM Modules

> Sample / Demo Program

> Multi-Program Loading 

> Power Cord for Completeness

> A Pretty Looking Box

To Be Completed:

> More Programs

> Interfacing with devices 

> Compiler/Assembler

> More Demos

> Larger Instructions possibly

> More Operations (ADD/SUB/LS, etc)

> Logisim Evolution version

# How to Use
How do you use this thing? It's pretty easy: Just download the .circ file included, and open it in Logisim. It should do all of the work for you. Click on Project, and reset the simulation. Use the "Poke" tool, and Turn on the PC. The JMP register should be set to Zero, so you should also enable, then disable that. You can also clear the screen if you wish.

The screen is currently set to display the instruction recieved on screen. Since instructions are 32 Bits, and I was too lazy to actually put it into a buffer, it only displays the first 7 bits. You can clear the screen if you choose. 

Manual Jump is designed to be a debugging type of thing. In case you are creating a program, and don't want to have to wait to jump, it's there for ya.

Program Select is basically an easy way of loading multiple programs. I recommend keeping at least ONE of the programs set to being empty, so that you don't have to deal with swapping instructions inbetween programs. 

The On/Off cord/button is very useful. It clears RAM storage, and all available registers on the same tick. It does not clear ROM though, so you can keep your programs safe.

As for programming for Project Savannah, the instructions are in the file labelled "codemanual.txt". That document will give you some insight on how everything is done. It's not really meant to be a public release though, so it might look a bit strange.

The expansion manual is kind of a document on how I'm planning on implementing Expansion / Networking into the CPU. The end goal is networking, plugging in other cards / programs, etc. That's a far way away, but I've already dedicated some registers to it. Since they aren't currently in use, feel free to use them as you wish, at least until it's implemented.

I'm always looking for new improvements to Project Savannah. At the time of writing this, I am currently designing revision two, which will have improved functionality and a larger set of instructions.

# What Next?
I'm currently designing a more robust language to go along with it. More operations, including logic, maths, etc. I wish to have 7 bit addressable memory, and more registers. 

Some features that I'm planning on including are...

1) Code Execution from RAM

2) Protected Memory

3) More extensible inputs and outputs

4) Multiple Outside LED's, including a "Program Swap" LED, a "R/W" LED, and maybe some more fancy stuff.

5) Multiple RAM Components

6) Proper Storage
