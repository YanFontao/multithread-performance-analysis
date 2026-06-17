### Repository Name

`multithread-performance-analysis`

### Description

Performance benchmarking project developed in C++, evaluating execution times across multiple thread configurations and dataset sizes as part of an Advanced Programming Laboratory course.

# Multithread Performance Analysis

A performance benchmarking project developed in C++ for the Advanced Programming Laboratory course, focused on analyzing the impact of thread count and dataset size on execution time.

The project investigates how computational workloads behave under different levels of parallelism, measuring execution times across multiple thread configurations and input sizes. The results were collected, averaged over multiple executions, and analyzed through tables and graphical reports.

## Overview

The objective of this project was to study the practical effects of multithreading on application performance.

Several experiments were executed using varying numbers of threads and different dataset sizes, allowing the observation of scalability behavior, processing overhead, and execution trends under increasing workloads.

Performance measurements were collected and statistically averaged to reduce the influence of isolated execution variations.

## Features

* Multithreaded workload execution
* Performance benchmarking
* Execution time analysis
* Scalability evaluation
* Comparative testing across thread counts
* Dataset size variation experiments
* Statistical averaging of multiple executions
* Graph generation and result visualization

## Experimental Configuration

### Thread Counts Tested

```text
4
16
32
64
128
256
512
1024
2048
4096
```

### Dataset Sizes

```text
32K
64K
128K
256K
512K
1024K
2048K
```

Each configuration was executed multiple times and the final results were calculated using arithmetic averages.

## Technical Concepts Demonstrated

* Parallel Programming
* Multithreading
* Performance Benchmarking
* Scalability Analysis
* Execution Time Measurement
* Statistical Data Analysis
* Experimental Methodology
* Performance Evaluation

## Methodology

The benchmarking process followed these steps:

1. Generate a workload of a specific size.
2. Execute the workload using a predefined number of threads.
3. Measure execution time.
4. Repeat the execution multiple times.
5. Calculate average execution times.
6. Compare results across configurations.
7. Generate visual reports and graphs.

This methodology minimizes isolated system effects and provides more reliable performance measurements.

## Results

The experiments demonstrated a clear relationship between workload size, thread count, and execution time.

The collected data allowed the identification of:

* Performance growth patterns
* Thread management overhead
* Scalability limitations
* Resource constraints
* Computational cost under increasing workloads

The final report includes detailed tables and charts illustrating the behavior of each configuration.

## Development Environment

### Hardware

* Intel Core i3-4130T @ 3.60 GHz
* 4 GB RAM

### Software

* Linux (Kali Rolling x64)
* C++
* POSIX Threads (Pthreads)

## Building

Compile the project using GCC:

```bash
g++ main.cpp -o benchmark -pthread
```

## Running

Execute the benchmark:

```bash
./benchmark
```

The application will run the configured experiments and generate performance measurements for later analysis.

## Educational Purpose

This project was developed as part of the Advanced Programming Laboratory curriculum to explore practical aspects of parallel computing and performance optimization.

The primary goal was to understand how execution time is affected by increasing workload sizes and thread counts, while gaining hands-on experience with concurrent programming and benchmarking methodologies.

## Author

Yan Matheus Gonçalves Fontão

Advanced Programming Laboratory • C++ • Multithreading • Performance Analysis
