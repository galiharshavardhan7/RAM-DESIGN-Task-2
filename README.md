# RAM-DESIGN-Task-2

**Company** :CODETECH IT SOLUTIONS

**Name**    :Gali HarshaVardhan Reddy

**InternId**:  CT06MKS

**Domain**  :VLSI

**BatchDuration**: Jan 15-th to -FEB 15th  4 weeks

**Mentor Name**:Neela Santhosh

**Description**
The Synchronous RAM Module is a digital circuit designed to store and retrieve data synchronously with a clock signal. It provides a basic implementation of a Random Access Memory (RAM) that can be used in a variety of digital systems.
**Features**
Synchronous Operation: The RAM module operates synchronously with a clock signal, ensuring that all data transactions occur at the rising edge of the clock.
Read and Write Operations: The module supports both read and write operations, allowing data to be stored and retrieved from the RAM.
Address Bus: The module has an address bus that selects the specific location in the RAM where data will be read or written.
Data Bus: The module has a data bus that carries the data being written to or read from the RAM.

**Features**
Synchronous Operation: The RAM module operates synchronously with a clock signal, ensuring that all data transactions occur at the rising edge of the clock.
Read and Write Operations: The module supports both read and write operations, allowing data to be stored and retrieved from the RAM.
Address Bus: The module has an address bus that selects the specific location in the RAM where data will be read or written.
Data Bus: The module has a data bus that carries the data being written to or read from the RAM.

**Operation**
Write Operation: When the write enable input is high, the module performs a write operation. The data on the data bus input is written to the location in the RAM array specified by the address bus input. The write operation occurs at the rising edge of the clock signal.
Read Operation: When the write enable input is low, the module performs a read operation. The data stored in the location in the RAM array specified by the address bus input is output on the data bus output. The read operation occurs at the rising edge of the clock signal.

**Timing Diagram**
Here is a timing diagram illustrating the synchronous operation of the RAM module:
Time	Clock	Write Enable	Address Bus	Data Bus
t1	0	0	A	D1
t2	1	0	A	D1
t3	0	1	B	D2
t4	1	1	B	D2

**In this timing diagram:**
At time t1, the clock is low, and the write enable is low, indicating a read operation.
At time t2, the clock rises, and the data on the data bus is output from the RAM.
At time t3, the clock is low, and the write enable is high, indicating a write operation.
At time t4, the clock rises, and the data on the data bus is written to the RAM.
Examples of arithmetic operations are addition, subtraction, multiplication, and division. Examples of logic operations are comparisons of values such as NOT, AND, and OR. All information in a computer is stored and manipulated in the form of binary numbers, i.e. 0 and 1

##Output
![Image](https://github.com/user-attachments/assets/d435ceee-ebe8-4d11-a6e6-ace49290e2c4)
