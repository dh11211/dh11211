# Hi, I'm Zishan (Shannon) Chen 👋

### CS Student @ The University of Melbourne | Systems & Security Researcher

I am a second-year Computer Science student with a deep interest in low-level systems, memory optimization, and hardware-level security (TEE). 

### Code Availability & Academic Integrity
My most significant engineering projects are not publicly visible for the following professional and academic reasons:

1.  **Research Confidentiality:** My active research on Trusted Execution Environments (TEE), involving Intel SGX and ORAM, is hosted in a private repository on my personal GitHub account to maintain confidentiality prior to potential publication.
2.  **Academic Integrity:** My core C/C++/Java coursework is submitted via a mix of private university GitLab instances and the university's learning platform (Ed). In accordance with the University of Melbourne's academic integrity policy, this work is kept private to prevent plagiarism.

I am fully available to screen-share code, discuss system architecture, and review memory profiling metrics (Valgrind) during technical interviews.

### What I actually build:
* **Secure Vector Databases (Current Research):** Writing C++ to protect LLM agents from memory-poisoning. I'm using Intel SGX, Path ORAM, and branchless CMOV instructions to stop microarchitectural side-channel leaks. (Currently running this on a custom Docker/QEMU x86 emulation stack I built for Apple Silicon).
* **Combinatorial AI Solver (C):** Built a high-performance puzzle solver using Iterated Width (IW) search and Radix Trees. I used custom bit-packing protocols to slash the memory footprint by 87% and maximize CPU cache locality.
* **Low-Latency Dictionary (C):** Built a Patricia Trie from scratch for O(k) lookups. I managed all dynamic memory manually (safe_malloc wrappers) and used Valgrind Massif to profile heap allocations while optimizing Levenshtein distance fuzzy searches.
* **Database Architecture (SQL):** Designed a massive, complex ERD for a SpaceX-style launch system and engineered advanced nested SQL queries for an EV charging network database.

### Hit me up:
* [LinkedIn](https://www.linkedin.com/in/zishan-chen-25477b330/)
* shannon.zishan@outlook.com
