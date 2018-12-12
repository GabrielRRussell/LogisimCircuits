# Project Savannah
__________________

Project Savannah is a custom CPU that I built in Logisim. It's designed to run simple code, and is planned to have a whole reach of features.

Completed Features:

> Code Execution

> 32 Registers and RAM Modules

> Sample / Demo Program

> Multi-Program Loading 

> A power cord, if you're into that.

> A Pretty Looking Box

To Be Completed:

> A program that is actually useful

> Interfacing with devices 

> Compiler/Assembler

> More Demos

> 64 bit???

> More Operations (ADD/SUB/LS, etc)

> Probably something else I'm missing.

_____________________________
# How to Use

How do you use this thing? It's pretty easy: Just download the .circ file included, and open it in Logisim. It should do all of the work for you. Click on Project, and reset the simulation. Use the "Poke" tool, and Turn on the PC. The JMP register should be set to Zero, so you should also enable, then disable that. You can also clear the screen if you wish.

The screen is currently set to display the instruction recieved on screen. Since instructions are 32 Bits, and I was too lazy to actually put it into a buffer, it only displays the first 7 bits. You can clear the screen if you choose. 

Manual Jump is designed to be a debugging type of thing. In case you are creating a program, and don't want to have to wait to jump, it's there for ya.

Program Select is basically an easy way of loading multiple programs. I recommend keeping at least ONE of the programs set to being empty, so that you don't have to deal with swapping instructions inbetween programs. 

The On/Off cord/button is pretty useful, actually. If I wired it up correctly (which honestly I have no clue, I kind of rushed uploading this), then it should clear all the registers, and RAM values. It won't erase your programs stored in ROM, so no worries there. 

As for programming for Project Savannah, the instructions are in the file labelled "codemanual.txt". That document will give you some insight on how everything is done. It's not really meant to be a public release though, so it might look a bit strange.

The expansion manual is kind of a document on how I'm planning on implementing Expansion / Networking into the CPU. The end goal is networking, plugging in other cards / programs, etc. That's a far way away, but I've already dedicated some registers to it. Since they aren't currently in use, feel free to use them as you wish, at least until it's implemented.

I've also included a program called "JumpTilTen." It's not working at the moment. I think I broke something. But it's just some example code that's documented in the Code Manual. Its job is to count a register to ten, and then place it into RAM. I wrote it as a way to do some basic math and test if registers were being counted properly.