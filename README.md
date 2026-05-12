# OpenMP 25-26 May 2026 for VECTA

This repository contains the material to be used in the OpenMP course run for VECTA in May 2026.

## Machines

We will use ARCHER2 as our principal platform, as this gives us easy access to GPU nodes. You should have your own machine from which you will log in to ARCHER2. Please try to ensure that you are able to do so before the course begins. Linux and macOS users will be able to log in directly using a command line terminal. Windows users may need to install MobaXterm, WSL2, or a command line emulator.

If you have a C/C++ or Fortran compiler with OpenMP installed on your own machine, please feel free to use it; likewise if your machine has a GPU and you have installed OpenMP with GPU support (and are confident it works correctly) you may use this for the final exercise using GPUs.

## Schedule

This course will run from Monday morning to Wednesday lunchtime, at which point we will move to the MPI course. Monday and Tuesday will cover an introduction to OpenMP and its use on CPU-based systems. Wednesday morning will act as an introduction to the use of OpenMP directives to run code on GPUs.

### Monday 25th May

10:00 [Lecture 1: Concepts](./slides/L01-concepts.pdf)  
10:45 [Lecture 2: OpenMP Intro](./slides/L02-OpenMPintroduction.pdf)  
11:30 Break  
11:45 Exercise 1: Hello, World  
12:30 Lunch  
13:30 [Lecture 3: Parallel regions](./slides/L03-parallelregions.pdf)  
14:15 Exercise 2: Mandelbrot set  
15:00 Break  
15:30 [Lecture 4: Worksharing](./slides/L04-worksharing.pdf)  
16:15 Exercise 3: Mandelbrot again (exercise 4 extension)  
17:00 Finish  

### Tuesday 26th May

10:00 [Lecture 5: Synchronisation](./slides/L05-synchronisation.pdf)  
10:45 Exercise: 5: Molecular dynamics  
11:30 Break  
11:45 [Lecture 6: Further topics](./slides/L06-furthertopics.pdf)  
12:30 Lunch  
13:30 [Lecture 7: Tips, tricks and gotchas](./slides/L07-TipsTricksGotchas.pdf)  
14:15 [Lecture 8: OpenMP performance](./slides/L09-GPU-architectures.pdf)  
15:00 Break  
15:30 Exercise 6: Molecular dynamics II, optional Exercise 7: ADI, and finishing other exercises  
17:00 Finish  

### Wednesay 27th May

9:30 [Lecture 9: GPU architectures](./slides/L09-GPU-architectures.pdf)  
10:15 [Lecture 10: Introduction to OpenMP offloading](./slides/L10-Introduction-to-OpenMP-GPU-Offload.pdf)  
11:00 Break  
11:15 [Lecture 11: OpenMP data movement](./slides/L11-Introduction-to-OpenMP-data-movement.pdf)  
12:00 Exercise 8: Calculating pi on the GPU  
12:30 Lunch  
