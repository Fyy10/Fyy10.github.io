---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- You can find the PDF [here](../files/paper1.pdf). -->

# Education

## University of California, San Diego (UCSD) -- Sep.2022 ~ Mar.2024 (expected)

- Major: Computer Science and Engineering \| **Current GPA: 4.0/4.0**
- Major Coursework: Principles of Computer Operating Systems, Recommender Systems, Probabilistic Reasoning & Learning, Convex Optimization, Search and Optimization, Graduate Networked Systems, Statistical Natural Language Processing, Compiler Construction, Parallel Computing.

## University of Electronic Science and Technology of China (UESTC) -- Sep.2018 ~ Jun.2022

- Major: Computer Science and Technology \| **Cumulative GPA: 3.96/4.0**
- Major Coursework: The C/C++ Programming, Data Structure and Algorithm, Computer Networks, Computer Operating System, Artificial Intelligence, Software Engineering, Principle and Application of Database, Principles of Computer Organization, Fundamentals of Compiler, Computer Architecture.

# Publications

***Yangye Fu**, Ming Zhang, Xing Xu, Zuo Cao, Chao Ma, Yanli Ji, Kai Zuo, Huimin Lu*; Partial Feature Selection and Alignment for Multi-Source Domain Adaptation; Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2021, pp. 16654-16663

# Research Experiences

## Partial Feature Selection and Alignment for Multi-Source Domain Adaptation -- May.2020 ~ Jun.2021

- Unified issues of "partialness" to a more generalized Multi-Source Domain Adaption (MSDA) task as Multi-Source Partial Domain Adaption (MSPDA) and proposed a novel model termed Partial Feature Selection and Alignment (PFSA) to cope with both MSDA and MSPDA scenarios.
- Employed a feature selection vector based on the correlation among the features of multiple source domains and the target domain and designed three effective feature alignment losses to align the features by preserving the domain information of data sample clusters in the same category and discrimination between different classes.
- Extensive experiments conducted on three prevailing MSDA datasets exhibited that the model outperformed the state-of-the-art MSDA and PDA methods in both MSDA and MSPDA tasks.

# Working Experiences

## Sichuan Hwadee Information Technology Ltd. -- Jun.2020 ~ Jul.2020

*Crawler Engineer*; Company Homepage: [http://www.hwadee.com/](http://www.hwadee.com/); *Chengdu, China*

- Used Scrapy as the crawler engine to crawl movie metadata from IMDb Top 1000 rated movies and combined data into a single file
- Generated pages to be crawled and stored links into a Redis server
- Wrote a script to store the data into a MySQL database

## UESTC Center for Future Media -- Oct.2019 ~ Jun.2022

*Research Assistant*; Laboratory Web: [https://cfm.uestc.edu.cn/](https://cfm.uestc.edu.cn/); Advisor: *Xing Xu*; *Chengdu, China*

- Proposed a method for multi-source domain adaptation by aligning partial features, implemented the model with PyTorch, and conducted experiments to demonstrate the superiority of the model.
- Composed the Statement of Claims of a patent for the proposed method.

# Projects

<!-- ## minihttp

- Project GitHub (Go): [https://github.com/Fyy10/minihttp](https://github.com/Fyy10/minihttp)
- A simple HTTP GET server -->

<!-- ## FireOS

- Project GitHub (C/C++, Assembly): [https://github.com/Fyy10/FireOS](https://github.com/Fyy10/FireOS) -->

<!-- ## FA Language -- Aug.2023 ~ Sept.2023

- Project GitHub (C/C++): [https://github.com/Fyy10/FAL](https://github.com/Fyy10/FAL)
- A C-style compiler built with Flex, Bison, and LLVM
- Lexical analysis with Flex
- Semantic parsing with Bison
- Code generation and optimization with LLVM -->

## Some Utility Tools

- [Math renderer](https://math-render.pages.dev/): write $\LaTeX$ equations in the browser and copy them to MS Word
- [MIPS machine code generator](https://github.com/Fyy10/Python-Playground/tree/master/MIPS_gen_code): generate machine code from MIPS assembly

## Ray Tracer -- Jul.2023 ~ Aug.2023

- Project GitHub (C/C++): [https://github.com/Fyy10/ray-tracer](https://github.com/Fyy10/ray-tracer)
- A toy ray tracer implemented in C/C++ from scratch
- Learned the basic concepts of rendering in computer graphics
- Implemented the base classes of 3D vectors, rays, and colors
- Defined the interface of diffuse materials, metals, and dielectric materials for interaction with rays
- Positionable camera with antialiasing and defocus blur
- Strengthened my object-oriented programming skills and understanding

## Snek Compiler -- Apr.2023 ~ Jun.2023

- Project GitHub (Rust): [https://github.com/Fyy10/snek-compiler](https://github.com/Fyy10/snek-compiler)
- An x86_64 compiler for snek (Lisp-like) language
- Parsed the abstract syntax tree (AST) using Rust pattern matching
- Implemented numerical and logical operators, variable binding, if statements, loop statements, functions, and structured data (tuples)
- Learned and followed the calling convention according to System V ABI
- Created heap-allocated data with Rust library and managed the memory with Assembly
- Garbage collection using LISP 2 mark-and-compact algorithm

## SurfStore: A Distributed and Decentralized File Synchronization System -- Jan.2023 ~ Mar.2023

<!-- - Project GitHub (Go): -->
- Implemented a key-value store for file content blocks
- Utilized SQLite to maintain a local index database for each client
- Defined communications among clients and servers via gRPC and protocol buffers
- Separately store the file metadata and contents into distributed servers
- Constructed a consistent hash ring to find the dedicated storage server (successor) for each file block
- Implemented the [Raft](https://raft.github.io/) consensus algorithm to achieve fault-tolerance

## Nachos 5.0j -- Oct.2022 ~ Dec.2022

- Project Introduction (Java): [https://cseweb.ucsd.edu/classes/fa22/cse120-a/projects/index.html](https://cseweb.ucsd.edu/classes/fa22/cse120-a/projects/index.html)
- Based on a Java implementation of a simulated operating system
- Completed the clock interrupt and thread join functionalities and implemented the rendezvous system call with condition variables and locks
- Developed demand paging and swapping with page fault handler and a swap file for supporting virtual memory and multiprocessing
- More on OS: [A simulated shell and scheduler (C/C++)](https://github.com/Fyy10/FireOS/tree/master/OS%20Course%20Lab/Lab1)

## File Backup System -- Aug.2021 ~ Sept.2021

- Project GitHub (C/C++): [https://github.com/Fyy10/File-Backup-System](https://github.com/Fyy10/File-Backup-System)
- A file backup application with GUI developed in C/C++
- Led a group of 3, wrote the GUI with Qt, and implemented the backup-on-save feature with Linux inotify APIs
- The listening thread was created and managed by pthreads library

## The Sieve of Prime Numbers and N-Body Simulation (Paralleled Computing) -- Mar.2021 ~ May.2021

- Project GitHub (C): [https://github.com/Fyy10/Parallel_Computing](https://github.com/Fyy10/Parallel_Computing)
- Implemented the Sieve of Eratosthenes Algorithm using MPI (Message Passing Interface).
- Computed the number of primes smaller or equal to the given number N using the MPI algorithm with three optimized approaches, which eventually achieved significant improvement in performance.
- Simulated the gravity interactions and the motions of 4096 bodies with CUDA C and reached more than 1500x speedup compared with sequential code on the target machine.

## Applications and challenges of Artificial Intelligence -- Sept.2020 ~ Nov.2020

- Project GitHub (Python): [https://github.com/Fyy10/Python-Playground/tree/master/AI](https://github.com/Fyy10/Python-Playground/tree/master/AI)
- Learned fundamental concepts and acquired skills in artificial intelligence including decision tree (ID3 algorithm), backpropagation in neural networks, fully connected networks for MNIST classification, LeNet for CIFAR10 classification, and VGG16 for flower classification.
- Led a team of 4 to attend the Kaggle Competition (Kannada-MNIST), where I managed to implement the designed models in Python utilizing PyTorch, and delivered the defense presentation.

## Image Retrieval Engine -- May.2020 ~ Jul.2020

- Project GitHub (Python): [https://github.com/Fyy10/Python-Playground/tree/master/PCA](https://github.com/Fyy10/Python-Playground/tree/master/PCA)
- Search for similar images based on principle component analysis (PCA)
- Data distribution analysis and visualization on [CIFAR10](https://www.cs.toronto.edu/~kriz/cifar.html) and [DomainNet](http://ai.bu.edu/M3SDA/) datasets

## Convolutional Neural Networks for Visual Recognition -- Jan.2020 ~ Feb.2020

- Assignment GitHub (Python): [https://github.com/Fyy10/ML-DL_Practice/tree/master/cs231n](https://github.com/Fyy10/ML-DL_Practice/tree/master/cs231n)
- Improved my programming skill and understanding of computer vision through finishing Stanford CS231n assignments that covered topics including K-nearest neighbor algorithm, fully-connected networks and convolutional networks, generative adversarial networks, and style transfer.

## Artificial intelligence poet system -- Dec.2019 ~ Feb.2020

- Project GitHub (Python): [https://github.com/Fyy10/AI-Poet](https://github.com/Fyy10/AI-Poet)
- Constructed a model to automatically write Chinese poems.
- Implemented the model in Python with PyTorch as the deep learning framework.
- Applied NLP techniques including RNN, LSTM, CharRNN model, Seq2Seq model, and Attention Mechanism.
- Trained the model on a GTX 1050 Ti graphic card and released the trained model on GitHub.

# Skills

- Python
  - PyTorch
  - NumPy
- LaTeX
- C/C++
- Java
- Go
- Rust
- Intel Assembly

# Language

- Chinese
- English
- Japanese (a little)

<!-- Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
