# Computer Architecture and Logic

## What Makes a Computer, a Computer?

A computer is an electronic machine that processes information—in other words, an information processor: it takes in raw information (or data) at one end, stores it until it's ready to work on it, chews and crunches it for a bit, then spits out the results at the other end. All these processes have a name. Taking in information is called input, storing information is better known as memory (or storage), chewing information is also known as processing, and spitting out results is called output.

## Binary & Data

We have all seen computers do seemingly miraculous things with all kinds of sounds, pictures, graphics, numbers, and text. It seems that we can build a replica of parts of our world inside the computer. You might think that this amazing machine is also amazingly complicated - it really is not. In fact, all of the wonderful multi-media that we see on modern computers is all constructed from simple ON/OFF switches - millions of them - but really nothing much more complicated than a switch. The trick is to take all of the real-world sound, picture, number etc data that we want in the computer and convert it into the kind of data that can be represented in switches.

![Binary Data](https://homepage.cs.uri.edu/faculty/wolfe/book/images/R02/binary5.jpg)

All data in a computer is represented as a sequence of ones and zeros. Depending on where the data lives — RAM, SSD, HDD, DVD etc. — ones and zeros are encoded differently physically, but conceptually it’s two distinguishable states — and that’s all there really is.

One such piece of data — a zero or one — is called a bit. Eight bits make a byte. Bytes are relevant as a unit, because — generally speaking — they are the smallest addressable units of memory.


## Circuits and Logic

We send information through computers using wires that represent 1s and 0s. Computers need a way to manipulate those 1s and 0s, so that they can eventually do more complicated operations like calculating the 50th digit of \piπpi.
Computers use logic gates to transform the 1s and 0s from input wires. A logic gate accepts inputs and then outputs a result based on their state.

For Example:

- NOT

The simplest gate is the NOT gate, also known as an inverter. It accepts a single input and outputs the opposite value.

If the input is 0, the output is 1:

![not](https://cdn.kastatic.org/ka-perseus-images/ea2294995e72f4144524ac8425fbcb1fb0df0788.svg)

If the input is 1, the output is 0:

![not](https://cdn.kastatic.org/ka-perseus-images/c7b71f28c14da65a2491522f62a0be0c2210dfcf.svg)

Inverting a value may seem like a trivial operation, but in computers, we can build highly sophisticated logic by combining many small operations.

![gates](https://study.com/cimages/videopreview/videopreview-full/svx7r9dl2s.jpg)

## CPU, Memory, Input & Output

**input** is how bits and bytes get into the computer. **Output** is how they get out.

The CPU is the part that executes instructions. It has a few (1 to dozens) of very fast places to hold information being worked on. These are called registers. Instructions that do calculations leave their results in a register. Depending on the computer architecture, the inputs to a calculation instruction come from a register and/or memory.

Memory holds most information, the program's instructions and data. Its size can vary from a few hundred bytes to terabytes. Each byte of memory has an address that can be used to load information from it or to store information to it.

![computer][https://www.kullabs.com/uploads/cpuu1.png]

## Hardware and Software

Computer hardware is any physical device used in or with your machine, whereas software is a collection of programming code installed on your computer's hard drive. In other words, hardware is something you can hold in your hand, whereas software cannot be held in your hand. You can touch hardware, but you cannot touch software. Hardware is physical, and software is virtual.

All software utilizes at least one hardware device to operate. For example, a video game, which is software, uses the computer processor (CPU), memory (RAM), hard drive, and video card to run. Word processing software uses the computer processor, memory, and hard drive to create and save documents.

Hardware is what makes a computer work. A CPU processes information and that information can be stored in RAM or on a hard drive. A sound card provides sound to speakers, and a video card provides an image to a monitor. Each of these are examples of hardware components.



