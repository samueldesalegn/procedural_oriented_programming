// procedural_oriented_programming
/*  Chapter one
=

Introduction to Computers and Programming Languages
Objectiver
- State briefly a history of computers
- Name and describe five major components of the computer
- convert binary numbers to decimal numbers and vice versa
- State the difference between the low-level and high-level programming languages.

History of computers
1. Charles Babbage - credited with inventing a precursor to the modern computer (difference Engine and Analytical Engine)
2. Ada Lovelace - wrote the demonstration program of analytical engine - Ada (programming language) was named in honor of her. (daughter of the poet Lord Byron)
a. Network => Computers of all kind are connected to a network.
b. LAN  => A network that connects computers in a single building or in several near buildings is called LAN or Local Area Network
c. WAN => A network that connects geographically dispersed computers is called a wide-area network or WAN. 
d. Internet => The individual networks can be connected further to form interconnected networks called internets.
e. web browser => The hottest tool for viewing information on the internet


2 Computer Architecture
= 

A typical computer today has five basic components: RAM, CPU, I/O, storage devices, and communication devices. 

Binary Numbers:
=> In a decimal number system, we have 10 symbols (0, 1, 2, 3, 4, 5, 6, 7, 8, 9), and the position values are integral powers of 10. 

=> The binary number system works the same as the decimal number system but uses 2 as its base. 
=> The binary number system has two digits (0 and 1) called bits, and position values are integral powers of 2.
=> How to convert a decimal number to binary number
1. Divide the number by 2
2. The remainder is the bit value of the 2 to power of 0 position
3. Divide the quotient by 2
4. The remainder is the bit value of the 2 to power of 1 position
5. Divide the quotient by 2
6. The remainder is the bit value of the 2 to power of 2 position
7. Repeat the procedure until you cannot divide any further, that is until the quotient becomes 0.

Example: Convert 25
25/2 = 12 + 1 
12/2 = 6 + 0
6/2 = 3 + 0
3/2 = 1 +1
1/2 = 0 +  1 
11001 = 1 + 0 + 0 + 8 + 16 = 25

The Binary system is more suitable for computers than the decimal system because it is far easier to design an electrical device that can distinguish two states
(bits 0 and 1) than 10 states (0 through 9)

A. RAM =>  Random Access Memory
= 

=> a repository for both program instructions and data manipulated by the program during execution. RAM is divided into cells. Each cell consists of 4 bytes(B)
1B = 8 bits
RAM is measured by the number of bytes it contains.

B. CPU => Central Processing Unit 
=
=> The brain of a computer. The CPU is the component that executes program instructions by fetching an instruction(stored in RAM), executing it, 
fetching the next instruction and so one
The CPU contains a small number of registers, which are high speed devices for storing data or instructions temporarily. CPUs are characterised by their clock speeds.

C. I/O Devices
=
=> Input/Output (I/O) devices allow communication between the user and the CPU. Input devices => keyboard, mice, etc. Output devices => monitors and printers etc.
=> Other I/O devices include scanners, bar code readers, magnetic strip readers, digital video cameras, and musical instrument digital interface (MIDI) devices.

D. Storage Devices
=

=> Storage devices such as disk and tape drives are used to store data and programs. Secondary storage devices are called non-volatile memory, 
while RAM is called volatile memory. Volatile = lost when the power is turned off.

E. Communication Devices
=
A communication device connects the personal computer to an internet. The traditional communication device for computerrs at home and in small offices was the modem.
A modem, which stands for modulator-demodulator, is a device the converts analog signals to digital and digital signals to analog. 
=> A communication device for connecting a computer to a LAN is a network interface card (NIC). A NIC can transfer data at a much faster rate than the fastest modem. 

03 PROGRAMMING LANGUAGES
=

Programming languages are broadly classified into three levels: Machine languages, assembly languages, and high-level languages. 

Machine Language is the only programming language the CPU understands. Each type of CPU has its own machine language. 
=
Machine - language instructions are binary-coded and very low level - one machine instruction may transfer the contents of one memory location into a CPU register
or add numbers in two registers. 

Assembly Language
=
One level above machine language is assembly language, which allows higher-level symbolic programming. 
Instead of writing programs as a sequence of bits, assembly language allows programmers to write programs by using symbolic operation codes. 

High-level Language
=
=> High-level languages were developed to enable programmers to write programs faster than when using assembly languages.

Compiler
=

=> Since programs written in a high-level language are not recognized by the CPU, we must use a compiler to translate them to assembly language equivalents. 


04 JAVA
=

Java is a new Object-oriented language that is receiving wide attention from both industry and academia. 
Java was developed by James Gosling and his team at Sun Microsystems in California. 

applet
=
=> Java is often described as a web programming language because of its use in writing programs called applets that run within a WEb browser. 
That is, you need a web broswer to execute Java applets. Applets allow more dynamic and flexible dissemination of information on the Internet, and this feature alone
makes Java an attractive language to learn. 

Application
=
=> A ja55va application is a complete stand-alone program that does not require a web browser. 
A Java application is analogous a program we write in other programming languages

Java is an ideal vehicle for teaching the fundamentals of object-oriented programming. 

Summary:
=
1. Charles Babbage invented the Difference Engine and Analytical Engine, precursors to the modern computer
2. Ada Lovelace is considered the first computer programmer
3. The first two modern computers were MARK I and  ENIAC I
4. John von Neumann invented the stored-program approach of executing programs
5. Computers are connected into a network. Interconnected networks are called internets
6. Binary numbers are used in computers
7. A typical computer consists of five components: RAM, CPU, I/O devices, Storage devices, and communication devices
8. There are three levels of programming languages: machine, assembly, and high-level
9. Java is one of the newest high-level programming languages in use today

Exercise of the chapter 
=
conversion to decimal numbers

1010 = 2*2*2 + 0 + 2 + 0 = 10
110011 = 32 + 16 + 0 + 0 + 2 + 1 = 51
110.01 = 4 + 2 + 0 + 1/4 = 6.25

convert to binary

35 
35/2 = 17 + 1
17/2 = 8 + 1
8/2 = 4 + 0
4/2 = 2 + 0
2/2 = 1 + 0
1/2 = 0 + 1
100011 = 32 + 2 + 1 = 35


567
567/2 = 283 + 1
283/2 = 141 + 1
141/2 = 70 + 1
70/2 = 35 + 0
35/2 = 17 + 1
17/2 = 8 + 1
8/2 = 4 + 0
4/2 = 2 + 0
2/2 = 1 + 0
1/2 = 0 + 1
=> 1000110111 

98 
98/2 = 49 + 0
49/2 = 24 + 1
24/2 = 12 + 0
12/2 = 6 + 0
6/2 = 3 + 0
3/2 = 1 + 1
1/2 = 0 + 1
=> 1100010


































