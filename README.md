#===========================================================#

                CPU / GPU Chip Data Analysis
                
#===========================================================#

Created on Sun May  7 14:10:05
author@ Ben Settle

Professor Cates
Intro to Data Science - COMSC.225.01

* FINAL PROJECT *

I will be performing an analysis on a CPU/ GPU dataset I found on kaggle.com that contains
information on CPU and GPU chipsets. The goal is to analyze the differences between different
manufacturers chips and potentially determine through the raw data, which manufacturer makes the best
CPUs and which makes the best GPUs.


The Metrics used to determine the hardwares performace are as follows:

FOR CPUs:
---------
    - Process Size (nm)
    - TDP (W)
    - Die Size (mm^2)
    - Transistors (million)
    - Frequency (MHz)

FOR GPUs:
---------
    - Process Size (nm)
    - TDP (W)
    - Die Size (mm^2)
    - Transistors (million)
    - Frequency (MHz)

    ALSO:
    - FP16 GFLOPS
    - FP32 GFLOPS
    - FP64 GFLOPS

Other columns containing non-relevant information for the quantitative analysis will be dropped.
The only qualitative information in the table will be hardware type and manufacturer.

#----------------------------------------------------#

        RESOURCES AND INFORMATION ON CHIP SPECS
        
#----------------------------------------------------#

Defenitions for all aformentioned quantitative analysis attribues are listed below.

* PROCESS SIZE *
----------------
Process size, also known as the fabrication process or node, 
refers to the size of the transistors and other components on a computer chip, 
which are manufactured using a series of photolithographic steps. 
In CPU manufacturing, a smaller process size generally leads to higher performance, 
lower power consumption, and smaller physical size of the chip. For example, 
a CPU with a 7nm process size has smaller transistors than a CPU with a 14nm process size, 
which allows for more transistors to be packed onto the same chip area, 
resulting in higher performance and efficiency.

* TDP *
-------
TDP (Thermal Design Power) is the maximum amount of heat a computer chip can generate under normal operation. 
It's measured in watts and is important for selecting appropriate cooling solutions. 
It's not the same as actual power consumption, which can vary depending on usage.

* DIE SIZE *
------------
Die size refers to the physical dimensions of a computer chip's silicon wafer, 
which contains the transistors, circuits, and other components that make up the chip. 
It is typically measured in millimeters and is an important factor in determining the chip's cost, 
performance, and power consumption. A larger die size can accommodate more transistors, 
allowing for more powerful and complex chips, but it also increases manufacturing costs and power consumption.

* TRANSISTORS *
---------------
Transistors are electronic switches that are the fundamental building blocks of CPUs and other computer chips. 
They can be turned on or off to represent 1 or 0, which are the binary digits used in digital computations. 
A CPU contains billions of transistors, which work together to perform calculations and execute instructions.

* FREQUENCY *
-------------
Frequency, measured in hertz (Hz), refers to the clock rate or the 
number of cycles per second at which a CPU operates. 
It determines how many instructions a CPU can process per second and is an important factor 
in determining the CPU's performance. A higher frequency generally leads to faster processing speeds, 
but it also results in higher power consumption and heat generation.

* GFLOPS *
----------
GFLOPS stands for billions of floating-point operations per second and is a measure of the computing power 
of a GPU (Graphics Processing Unit). It indicates the number of floating-point calculations that a GPU can 
perform in one second and is often used to compare the performance of different GPUs. The higher the GFLOPS, 
the faster the GPU can process complex mathematical calculations, such as those used in 3D graphics 
rendering and scientific simulations.
