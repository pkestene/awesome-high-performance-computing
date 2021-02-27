# Awesome High Performance Computing Resources <img align="right" width="20%" src="parallel-computing.jpg">

A curated list of awesome high performance computing resources. 
Please feel free to update this page through [submitting pull requests][GitHub pull requests] or 
[emailing me][email me].

## Table of Contents

 - [Software](#software)
 - [Clusters](#software)
 - [Presentations](#presentations)
 - [Learning Resources](#learning-resources)
 - [Datasets](#datasets)
 - [Links](#links)
 - [Acknowledgements](#acknowledgements )

All the lists in this page are either in alphabetical order or chronological order.

## Software

#### Programming Library

- [CAF: An Open Source Implementation of the Actor Model in C++](https://github.com/actor-framework/actor-framework)
- [Chapel: A Programming Language for Productive Parallel Computing on Large-scale Systems](https://chapel-lang.org/)
- [Charm++: Parallel Programming with Migratable Objects](http://charm.cs.illinois.edu/research/charm) 
- [Cilk Plus: C/C++ Extension for Data and Task Parallelism](https://www.cilkplus.org/)
- [Taskflow: A Modern C++ Parallel Task Programming Library](https://github.com/taskflow/taskflow)
- [FastFlow: High-performance Parallel Patterns in C++](https://github.com/fastflow/fastflow)
- [Galois: A C++ Library to Ease Parallel Programming with Irregular Parallelism](https://github.com/IntelligentSoftwareSystems/Galois)
- [Heteroflow: Concurrent CPU-GPU Task Programming using Modern C++](https://github.com/Heteroflow/Heteroflow)
- [HPX: A C++ Standard Library for Concurrency and Parallelism](https://github.com/STEllAR-GROUP/hpx)
- [Intel TBB: Threading Building Blocks](https://www.threadingbuildingblocks.org/)
- [Kokkos: A C++ Programming Model for Writing Performance Portable Applications on HPC platforms](https://github.com/kokkos/kokkos)
- [OpenMP: Multi-platform Shared-memory Parallel Programming in C/C++ and Fortran](https://www.openmp.org/)
- [RaftLib: A C++ Library for Enabling Stream and Dataflow Parallel Computation](https://github.com/RaftLib/RaftLib) 
- [STAPL: Standard Template Adaptive Parallel Programming Library in C++](https://parasol.tamu.edu/stapl/)
- [STLab: High-level Constructs for Implementing Multicore Algorithms with Minimized Contention](http://stlab.cc/libraries/concurrency/)
- [Transwarp: A Header-only C++ Library for Task Concurrency](https://github.com/bloomen/transwarp)
- [MPI: Message passing interface; OpenMPI implementation](https://www.open-mpi.org/)
- [MPI: Message passing interface: MPICH implementation](https://www.mpich.org/)

## Clusters

### Future
 - [Frontier](https://www.amd.com/en/products/exascale-era) - 2021, AMD-based, ~1.5 exaflops
 - [El Capitan](https://www.amd.com/en/products/exascale-era) - 2023, AMD-based, ~1.5 exaflops
 - [Aurora](https://en.wikipedia.org/wiki/Aurora_(supercomputer)) - 2021, Intel-based, ~1 exaflops

### Current
 - https://www.top500.org/lists/top500/2020/11/

## Presentations

#### Generic Parallel Computing Topics

- [Task based Parallelism and why it's awesome](https://www.fz-juelich.de/ias/jsc/EN/Expertise/Workshops/Conferences/CSAM-2015/Programme/lecture7a_gonnet-pdf.pdf?__blob=publicationFile) - Pedro Gonnet
- [Concurrency in C++20 and Beyond](https://www.youtube.com/watch?v=jozHW_B3D4U) - A. Williams
- [Is Parallel Programming still Hard?](https://www.youtube.com/watch?v=YM8Xy6oKVQg) - P. McKenney, M. Michael, and M. Wong at CppCon 2017
- [The Speed of Concurrency: Is Lock-free Faster?](https://www.youtube.com/watch?v=9hJkWwHDDxs) - Fedor G Pikus in CppCon 2016

#### Scheduling in Parallel Processing

- [Expressing Parallelism in C++ with Threading Building Blocks](https://www.youtube.com/watch?v=9Otq_fcUnPE) - Mike Voss at Intel Webinar 2018
- [A Work-stealing Runtime for Rust](https://www.youtube.com/watch?v=4DQakkJ8XLI) - Aaron Todd in Air Mozilla 2017

#### Memory Model

- [C++11/14/17 atomics and memory model: Before the story consumes you](https://www.youtube.com/watch?v=DS2m7T6NKZQ) - Michael Wong in CppCon 2015
- [The C++ Memory Model](https://www.youtube.com/watch?v=gpsz8sc6mNU) - Valentin Ziegler at C++ Meeting 2014

## Learning Resources

#### Books

- [C++ Concurrency in Action: Practical Multithreading](https://www.manning.com/books/c-plus-plus-concurrency-in-action) - Anthony Williams 2012
- [The Art of Multiprocessor Programming](https://www.amazon.com/Art-Multiprocessor-Programming-Revised-Reprint/dp/0123973376/ref=sr_1_1?ie=UTF8&qid=1438003865&sr=8-1&keywords=maurice+herlihy) - Maurice Herlihy 2012
- [Parallel Computing: Theory and Practice](http://www.cs.cmu.edu/afs/cs/academic/class/15210-f15/www/tapp.html#ch:work-stealing) - Umut A. Acar 2016

#### Tutorials

- [Parallel Computing Training Tutorials](https://hpc.llnl.gov/training/tutorials) - Lawrence Livermore National Laboratory

#### Position Papers

- [The Landscape of Parallel Computing Research: A View from Berkeley](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2006/EECS-2006-183.pdf)
- [Extreme Heterogeneity 2018: Productive Computational Science in the Era of Extreme Heterogeneity](references/2018-Extreme-Heterogeneity-DoE.pdf)

#### Experimental Papers

- [Evaluation and Analysis of Dynamic Loop Scheduling in OpenMP](references/EvaluationAndAnalysisofDynamicLoopSchedulingofOpenMP.pdf)

#### Courses

- [CS6290 High-performance Computer Architecture](https://www.udacity.com/course/high-performance-computer-architecture--ud007) - Milos Prvulovic and Catherine Gamboa at George Tech


## Datasets

- [HPEC Graph Challenge](https://graphchallenge.mit.edu/)
- [PARRSEC Benchmark Suite for the Analysis of Multithreaded Programs](https://parsec.cs.princeton.edu/)


## Links

#### Forums
 - [r/hpc](https://www.reddit.com/r/HPC/)
 - [r/homelab](https://www.reddit.com/r/homelab/)

#### Blogs
 - [1024 Cores](http://www.1024cores.net/) - Dmitry Vyukov 
 - [Michael Wong's Standard on Parallelism and Programming Languages](https://wongmichael.com/about/) - Michael Wong
 - [Preshing on Programming](https://preshing.com/) - Jeff Preshing
 - [Sutter's Mill](https://herbsutter.com/) - Herb Sutter
 - [The Black Art of Concurrency](https://www.internalpointers.com/post-group/black-art-concurrency) - Internal Pointers
 
#### Journals
 - [IEEE Transactions on Parallel and Distributed Systems (TPDS)](https://www.computer.org/csdl/journal/td) 
 - [Journal of Parallel and Distributed Computing](https://www.journals.elsevier.com/journal-of-parallel-and-distributed-computing)
  
#### Conferences

 - [ACM SIGPLAN Annual Symposium on Principles and Practice of Parallel Programming (PPoPP)](https://ppopp19.sigplan.org/home)
 - [ACM Symposium on Parallel Algorithms and Architectures (SPAA)](https://spaa.acm.org/)
 - [ACM/IEEE International Conference for High-performance Computing, Networking, Storage, and Analysis (SC)](https://sc19.supercomputing.org/)
 - [IEEE International Parallel and Distributed Processing Symposium (IPDPS)](http://www.ipdps.org/)
 - [International Conference on Parallel Processing (ICPP)](https://www.hpcs.cs.tsukuba.ac.jp/icpp2019/)

#### Other
  - [Nice notes](https://caiorss.github.io/C-Cpp-Notes/Libraries.html)


## Acknowledgements

This repo started from the great curated list https://github.com/taskflow/awesome-parallel-computing


