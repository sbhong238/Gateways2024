# Curriculum Enhancement of Parallel Computing Course at Jackson State University 

Target Course(s): CSC425.01 Parallel Computing 

The course (CSC 425) is for junior- to senior-level Computer Science (CS) and Computer Engineering (CE) students. Based on the curriculum, all students would have already finished programming languages, operating systems, computer architectures, and data structure courses to develop sequential programs.  The course will then focus on implementing parallel algorithms.  

## Objectives:
* Refine curriculum to enable students to understand and be skilled at parallel computing.
* Implementing/understanding effective HPC architecture.
* Get access to HPC resources.
* Obtaining large datasets for data analytical problems.
* Design sample projects for parallel programming using OpenMP, MPI, and OpenACC, using C/C++.
* Apply the knowledge on sorting, graph, search, dynamic programming, and Fast Fourier Transform problems.

The programming models would consist of several subareas: 
* Data parallelism
* Task parallelism
* Multithreaded programming
* Shared memory model
* Message-passing model

# Projects for the class
Projects would be designed to take advantage of large data sets and computing power. As part of this effort, some of the NSF/IEEE-TCPP curriculum initiatives on Parallel and Distributed Computing (PDC) modules would be integrated into department-wide core and elective courses offered in both fall and spring semesters. From CSC 325 Operating Systems (core), the students would learn how to write simple parallel programs with the POSIX threads library.

# Example projects
1. Genomics Big Data Problem:  
The simple DNA problem: 
DNA sequences are represented as character strings, with each character representing a nucleotide type. The DNA sequence alignment problem, or pattern searching problem, identifies coincidences of nucleotide strings in a long DNA sequence. Multiple pattern matching is a complex problem in a DNA sequence. Our assignment addresses this by finding matches in a random main DNA sequence with multiple nucleotide patterns, which can also be random sequences or exact copies of parts of the main sequence. The students are going to use a brute-force algorithm that checks each pattern at every possible position in the DNA sequence, offering parallelization opportunities. The program identifies patterns found in the sequence and their starting positions. The project requires the implementation of direct parallelization opportunities at two levels: patterns and starting positions. An example algorithm for genome similarity identification from Machbah Uddin et al [2] would be parallelized for the student projects. 

2. Principal Component Analysis (PCA):                                                                                                                                                  
The students would apply PCA for the reduction of problem spaces. Their project codes would be parallelized using OpenMP, MPI, and OpenACC. These would be applied on image datasets obtained from different resources.

# Datasets
* Github repositories
* https://data.world/datasets/
* Designsafe-CI - https://www.designsafe-ci.org 
* https://Kaggle.com
* pip install genomic-benchmarks (dataset would be installed directly on the machine)


# Resources
* Pathways For Supercomputing - Oak Ridge National Laboratory (ORNL)
* ACCESS - National Science Foundation (NSF)
* Globus for data transfers
* Symmetric multiprocessing (SMP) type HPC for OpenMP
<img width="1143" alt="image" src="https://github.com/user-attachments/assets/cb027a0b-7a36-4201-b310-13017cb90d71">


## Reference : 
1]. Victor Eijkhout, The Art of High Performance Computing, 3rd edition 2022.

2]. Machbah Uddin et al. A fast and efficient algorithm for DNA sequence similarity identification. Complex & Intelligent Systems (2023) 9:1265–1280 


## 
