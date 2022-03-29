## 常见词

Recursion递归, iteration迭代



# 计算机网络



## *WAN

WAN is short for  Wide Area Network .It has a large physical range .It can connect many cities or countries and provide long distance communication.

## *LAN

LAN is short for **Local Area Network**. It has a **small physical range**. It is a network of computers, devices and databases connected to each other.

## *MAN

MAN is short for A **Metropolitan Area Network**.it is a computer communication **Network established within a city.**

## *PAN

PAN is short for A **Personal Area Network**..It has a very small physical range .It  is a Network of computing devices within a few meters

## ?Bandwidth带宽

Bandwidth in computer networks refers to the highest data transfer rate, which is measured in bits per second.



## *RTT

RTT is short for Round-trip Time. It is the time between the sender sending data and  receiving the confirmation datagram.



##  *OSI model

OSI model is short for **Open System Interconnection** model.It consists of seven layers, which are physical layer, data link layer, network layer, transport layer, session layer, presentation layer and application layer.



## *TCP/IP model

The TCP/IP model consists of four layers, which are network access layer, Internet layer, transport layer and application layer.

## RZ&NRZ

RZ is a return to zero code, low level represents 0, high level represents 1. It jumps to low in the middle of every clock cycle.

NRZ is a non-return  to zero code, low level represents 0, high level represents 1. It don't need to jumps to low in the middle of every clock cycle.

NRZI is a reverse non-return to zero code.It use jump to represents 0,keep to represents 1;

## ?Manchester encoding 

Manchester encoding divides the code into two equal intervals, with high level jumping to low level representing 1 and the opposite representing 0.

## ?repeater

The main function of the repeater is to shape and amplify the signal and then forward it

## *Hub

A hub is a **multi-port successor**.It can expand the spread of the network.But it does not have the ability of directional transmission. It does not isolate **conflict domains**.

## ARQ

ARQ is the Automatic Repeat Request. It uses Cyclic Redundancy Check encoding. The receiver drop the error data frame, and the sender retransmits it when it is out of time.



## GBN

GBN protocol is the back N frame protocol, which supports cumulative confirmation. If a frame is wrong, it discards that frame and subsequent frames.

## SR

Sr is a selective retransmission protocol and does not support cumulative confirmation. It retransmits the error frame.



## ?CSMA/CD

CSMA/CD is a carrier sense multiple access protocol with collision detection. Detect the channel before sending data, and send data when the channel is idle. During the sending, it is always checked for sending conflicts. If no conflicts occur during the contention period, it is sure that the sending is not conflicting



## FDM

FDM is **frequency - division multiplexing**. It divides the bandwidth into several sub-channels, each transmitting a signal.

## TDM

TDM is **Time Division Multiplexing**. In terms of time, it transmits one signal at a time. In terms of time periods, it transmits multiple signals per time period.

## WDM

WDM is **wavelength Division multiplexing**. It is frequency division multiplexing of light. It can transmit many different wavelengths of light in a single fiber.

## CDM

CDM is **code Division Multiplexing**. It uses different codes to distinguish the original signals.

## MAC address

A MAC address is a physical address. It is six bytes long, or 48 bits. It is usually expressed in hexadecimal notation.

## *PPP

PPP is a point-to-point protocol, which is a byte-oriented protocol. It establishes point-to-point connections.

## Bridges work

Bridges work at the **data link layer**. It can isolate conflict domains, but not broadcast domains. It is used to extend lans.

## *switch

A switch is a multi-port bridge that can isolate conflicting domains, but not broadcast domains. It has automatic addressing and switching capabilities.

## *router

Routers are network layer devices. It can isolate both conflict domains and broadcast domains. It can also connect to heterogeneous networks.

## *NAT

NAT is **network Address translation**. It converts the local IP address into a valid external IP address.



## CIDR

CIDR is Classless Inter-domain Routing. It uses a slash notation, with the number after the slash representing the network prefix.



## *ARP

ARP is the **Address Resolution Protocol.** It is a **network layer** protocol. It is responsible for converting IP addresses into physical addresses

## *DHCP

DHCP is the **Dynamic Host Configuration Protocol.** It is an **application-layer** protocol and uses UDP. It enables hosts to dynamically obtain IP addresses in the network

## *ICMP

Icmp is The **Internet Control Messages Protocol.** It is a **network layer** protocol. There are two types of messages: error report message and inquiry message.

## IPdatagram

IP datagrams are data units that are transported at the network layer. It has a fixed 20B section at the front. Its tip can be up to 60B in size.

The ipv4 address bit is **32 bits**

ipv6**128bit**

## *IGP

Igp is **Interior Gateway Protocol**. It includes RIP and OSPF.

## *EGP

Egp is **Exterior Gateway Protocol**. It is responsible for transmitting routing information between different internal gateway protocol networks. For example, BGP is a type of EGP.

## *RIP

RIP is the **Routing Information Protocol**. It uses the number of jumps to represent the cost of the path. Its maximum jump number is 16 which means unreachable. It exchanges adjacent routing information every 30 seconds. It **uses udp** to transport its datagram.



## *OSPF

Ospf is the **Open Short Path First protocol.** It uses the **Dijkstra algorithm** to calculate the shortest path. It transmits in **IP datagrams** and sends packets at multicast addresses.

## *BGP

BGP is the **Border Gateway Protocol**. It belongs to the Exterior Gateway Protocol. It uses TCP to transmit packets and needs to establish a TCP connection.

## IGMP

IGMP is The **Internet Group Management Protocol**. It is a multicast protocol.

## the port number

The port number identifies the application and is 16 bits long.

## *socket

The socket is a **combination of the host IP address and the application process port number.** It is used in the network to identify the corresponding process of the corresponding host

## *UDP

UDP is **user datagram protocol**.It is a unreliable transport layer protocol.Its header size is 8 byte.It don't need to create a connection. 

## *TCP

TCP is **transmition cotrol protocol**.It is a reliable transport layer protocol. It needs to create a connection to transport datagram with three handshakes and to close connection with flour handshakes.

## *c/smodel

In the **client/server model**, a host that is always open is called a server. The server serves requests from other hosts called clients.

## *P2P

**Peer-to-peer model** is a model without fixed client and server division. Each of its nodes can either be accessed as a customer or provide a service.

## *dns

DNS is a **Domain Name System**. It is responsible for the specific meaning of the domain name into the IP address of the corresponding host. It uses a UDP and client/server model, and its **port number is 53.**



## *ftp

FTP is the **File Transfer Protocol**. It uses the TCP reliable transport service. Its **data** connection uses **port 20** and its **control** connection uses **port 21**

## *smtp

SMTP is the **Simple Mail Transfer Protocol**. It uses TCP connections and a client/server model. It is mainly used by users to send mail.

## *pop3

Pop3 is **Post Office Protocol 3**. Pop3 uses TCP connections. It is primarily used by the user to receive data from the server.

## *www

WWW is the **World Wide Web**. It is **a large repository of information**. It makes it very easy to access other sites through links.

## *http

HTTP is **hypertext Transport Protocol**. It is the protocol used to interact between browsers and WWW server programs. It uses TCP for reliable transport and listens on **port 80**





# 操作系统



## *Concurrence并发和Parallism

Concurrency is when **multiple events occur at the same time interval**. Parallelism is when **multiple events occur at the same time.**



## *sharing

Sharing refers to resource sharing, that is, resources in the system can be used by **multiple concurrently** executing processes in memory.

## *mutually exclusive

Mutually exclusive access means that **only one process can access a resource at a time.**

## *Asynchronism 

Asynchrony means that the **execution of a process may not be all at once.** When a program segment needs to wait, you **can execute other program segments first and then call back to execute the program segment** when the program segment is ready to run.

## Synchronization  

**Synchronization** means that the program **completes in order**, while the previous one does not complete, the next one has to wait。

## Interruption

**Interrupts** are also called **external interrupts.** It is caused by events **other than the CPU executing instructions**. Such as **human intervention**, **external equipment requests.**

## *Exception

Exceptions are also called **internal interrupts**. It contains voluntary interrupts such as instruction interrupts. It also includes failure interrupts such as **hardware and software failures.**

## *process

A process is a **process executed by a program**, which is dynamic, concurrent and independent. It has **running, ready, blocking, create, and end states.** It has a unique process control block.It is the **smallest unit of resource allocation**

## *PCB

A PCB is a **process control block**. It contains process control and management information, resource allocation lists, process description information, and processor-related information.

## *Threads 

Threads are **smaller process** that **do not own system resources** and **share process resources** with other threads. It is the **smallest unit of dispatch**

## *FCFS

The **First Come, First Served scheduling algorithm selects the process in the time order.**

## *SJF

The **Shortest Job First scheduling algorithm** **selects the Shortest process** in the queue each time.It may cause long processes not to be scheduled for a long time.

## The priority scheduling

The priority scheduling algorithm **selects the process with the highest priority** in the queue for scheduling

## Time slice rotation scheduling algorithm

The time slice rotation scheduling algorithm is **used in the time-sharing system**. It adds the **concept of time slice** to the **first-come-first-served algorithm.**

## the logical address

The logical address is the **offset address** relative to unit 0.

The physicial address is the **real address in the memory.**

## *The First Fit algorithm

The First Fit algorithm is an algorithm that **finds free partitions**. Its free partitions are stored **in address order.** When allocating memory, the first fit free partition will **be allocated**

## *The Best Fit algorithm

The Best Fit algorithm is an algorithm that finds **free partitions**. Its free partitions are **stored in increments of capacity.** When allocating memory, the first fit partition  in its sequence **will be allocated**

## *The Worst Fit algorithm

The Worst Fit algorithm is an algorithm that finds free partitions. Its free partitions are stored in **decreasing order of capacity.**  When allocating memory, the first fit partition  in its sequence **will be allocated**

## *The Next Fit algorithm

The Next Fit algorithm is an algorithm that finds free partitions. Based on the first Fit algorithm, it **changes the starting position**  each search **to the last end position.**

## *TLB

TLB is **Translation look-aside Buffers.** It uses the **cache** to hold the number of page entries currently accessed.It stores the **block number** corresponding to the **physical address.**

## *opt

Opt algorithm is the **optimal permutation algorithm.** It **swaps out pages** that **will not be visited for the longest time.**

## *FIFO

FIFO algorithm is the **first in first out replacement algorithm.** The pages it swaps out are the **first to enter memory.**

## *LRU

LRU algorithm is the **most recent and longest not used substitution algorithm**. It swaps out pages that **have not been visited for the longest time** in the page table

## *clock

The **Clock algorithm** is a **recently unused substitution algorithm**. It swaps out r**ecently unused** pages each time **in a circular linked list.**

## *FCB

FCB is a **file control block.** It mainly contains **basic file information**, **access control information**, and **usage information.**

## hard link

Hard link is to store file information **in the index node**, and **set only the directory name** and **corresponding pointer** in the **file directory**. The disadvantage is that when the file is shared by others, **the user who created the file cannot delete the file.**

## soft link

Soft links **use path names to share files**. If the user who created the file deletes the file, other shared users cannot access the file using the path.

## *FCFS

The **First Come, First Served scheduling algorithm** selects tracks in the time order.

## *SSTF

SSTF algorithm is the **shortest search time first algorithm.** It selects the track closest to the current track at a time.

## *SCAN

The Scan algorithm **selects the closest  track  in the moving direction of the magnetic head** and **changes the direction on the innermost or outermost end of the disk.**

## *CSCAN

CScan algorithm is a **cyclic scanning algorithm**. **selects the closest  track  in the moving direction of the magnetic head**, and **start from the innermost track again when  reach the outermost end.**



## *dma

DMA is **direct memory access**. It **establishes a one-day data exchange path** **between the I/O device and memory**. Its **basic unit of transmission is the data block.** Its data block **transfer is done under the DMA controller.**



## Diskcache

Disk caching refers to the **allocation of a space in memory** to **temporarily hold information in a block read from a disk.**

## *Buffer

The cache is mainly **used to alleviate the speed mismatch between high-speed devices and low-speed devices.** It **reduces the waiting time** of high-speed equipment and improves work efficiency.



# 计算机组成

## *cpu

The CPU is the **Central Processing Unit.** As the operation and control core of the computer system, it is the **final execution unit** of information processing and program operation.



## *MAR

Mar is a **memory address register**. It's responsible for s**toring the address that accesses memory**, and **it's in the CPU**. It has the **same number of bits as the program counter.**



## *MDR

MDR is a **memory data register**. It is responsible for **holding data that is read or written from memory**, and **it is in the CPU**. It has the **same number of bits as the stored word length.**



## *CPI

CPI is **clock cycle per instruction**. It is the **number of clock cycles** **required to execute an instruction.**

## *MIPS

MIPS is **Million Instructions Per Second**. It represents the **number of millions of instructions  that can be executed per second.**

## *Flops

FLOPS is **floating-point operations per second.** It represents **the number of floating-point operations that can be performed per second.**

## *MFLOPS

MFLOPS is **Million  floating-point operationsPer Second.** It represents **the number of millions of  floating-point operations that can be executed  per second.**

## Decimalism

The decimal system is **a system of** **counting** in everyday life.  It means that a number can **be represented as** **many different powers of ten.** Their **preceding coefficients** **are Decimalismrepresentations of numbers.**

## *binary

Binary is the most widely used counting system in computers. It means that a number can be represented as multiple different powers of two. Their preceding coefficients are binary representations of numbers.

## *Hexadecimal 

Hexadecimal is the widely used counting system in computer physic adress. It means that a number can be represented as multiple different powers of 16. Their preceding coefficients are binary representations of numbers.

## BCD

BCD is **binary-coded Decimal.** It **represents a decimal number with four bits in binary.**

## ASCII 

ASCII is The **American Standard Code for Information Interchange**. It is a common character encoding.

## CRC

CRC is **Cyclic Redundancy Check**. It uses **modular two division** to **compute redundancy codes**.

## A parity check code

A **parity check code** **adds a bit of a check code** so that **the number of 1** in the information code **is odd or even.**

## Two's Complement

Two's Complement is an encoding **used to simplify binary subtraction**. Its negative number is  **reversed by all the bits of the truth value,**  **plus one to the end,** and the **negative symbol represented by one at the highest level**.

## *ALU

The ALU is the **Arithmetic Logical Unit**. It can **compelete all kinds of arithmetic and logical operations**. It has **two inputs and one output.**

## *RAM

Ram is a **random access register**. Its advantage is that **it is easy to read and write.** The disadvantage is that **information is lost when the electricity is turned off.**

## *SRAM

Sram is **static random access memory**. It is a type of **random access register**, which will lose information **when the electricity is turned off.** It is commonly used **as cache memory.**

## *DRAM

DRAM is a **dynamic random access register**. It is a type of random access register, which will lose information **when the electricity is turned off.**  It is often used **as main memory.**

## *ROM

ROM is **read only memory.** The disadvantage is that It can **only be read randomly, not written.** The advantage is that information will not be lost **when the electricity is turned off.** 

## *cache

A cache is a **cache register**. It **consists of static random access registers**. It acts as a cache that **allows the CPU to read copies directly** **instead of reading data directly from slow main memory**

## *ACC

ACC is the **accumulator.** It is a register used to **store intermediate operation results.**

## *RISC

RISC is a **Reduced Instruction-Set Computer**. Its **instruction length is fixed** and there are **few classes in the instruction format.** It uses **pipeline technology**. Its controller is **combinatorial logic control.**

## *cisc

CISC is c**omplex Instruction Set Computer**. Its **instruction length is not fixed** and there are **many classes in the instruction format.** The **execution time of its various instructions is very different**. Its controller is **microprogrammed.**

## *psw

PSW is the **Program Status Word register.** It is used to save the contents of **various operation result condition codes,** such as **operation result carry mark**, **result overflow mark**, **result zero mark** and so on

## *IR

IR is the **instruction register**. It is used to save the **instruction currently** being executed.

## *pc

The PC is the **program counter**. It is used to **store the address of the next instruction**. Normally, the address it stores **is automatically incremented by one before each non-jump instruction begins.**

## 流水线

FI is **fetch instruction**. ID is **instruction decoding**. Co is the **compute operand address**. FO is **fetch operation tree**. EI is **executing instructions**. WO is the **write operand**. They constitute a **six-level** assembly line.

## Bus

A bus usually **consists of a control line, a set of data lines, and a set of address lines.**



## I/O

The **I/O mode** is the **program query mode.** It requires the **CPU to constantly query the status of the device**. It dramatically **reduces CPU efficiency.**

## program interrupt mode

In **program interrupt mode**，the **CPU is no longer own by a single device .** **Whenever the device is ready, a request is sent to the CPU.**And cpu will immediately **interrupt the current execution, saves the breakpoint, and goes to execute the interrupt service routine.**

## 模板

... is short for .....

Its characteristics is that ...

It consists of several parts.....

It is mainly used for...

The different between it and ... is that

Its advantages is that...

Its disadvantages is that...

It has high efficiency.

It (dont) need to ... when...

It cant implement ..

In short,