[English](./index.md) | [Русский](./ru.md)

# Nikita Malcev 
C++ Software Engineer

---

## Contacts

Location: Moscow, Russia (GMT+3)

telegram: `@hfhhdp`

mail: `malcevnik99@gmail.com`

github: [repo](https://github.com/mmmhdp)

---

## Summary

Graduated with a Bachelor's degree.
Worked on Python projects with asynchronous processing and real-time backend services.
Currently developing C++ skills to work on high-load systems, build efficient multithreaded architectures, and optimize performance.

---

## Technical Skills

**Languages:** C++, C, Python  

**Tools:** Linux, Git, Docker, Make, CMake

**Languages:** Russian (native), English (C1)

---

## Projects

### Real-Time Video Stream Analysis Service ([Farseer](https://github.com/mmmhdp/farseer))

*Pet / Academic Project*  

- Implemented an asynchronous service for real-time video stream analysis
- Designed request lifecycle management using an explicit finite state machine (FSM)
- Ensured data consistency between Redis and PostgreSQL using background workers
- Integrated RTSP video streams with concurrent frame processing
- Developed an async REST API for request management
- Integrated object detection inference as a processing component
- Used PostgreSQL for persistent state storage and MinIO for media storage

**Tech stack:** Python, FastAPI, PostgreSQL, Redis, MinIO, RTSP, Docker

---

### Voice-Based Conversational AI Platform ([Bishop](https://github.com/mmmhdp/bishop))

*Team Diploma Project*  

- Developed a full-stack conversational application with voice-based interaction
- Implemented backend services for user authentication and chat management
- Built frontend interfaces using FastHTML (user dashboard, chat UI)
- Integrated audio processing pipeline for voice input and output
- Worked with speech and language models as part of the system
- Designed end-to-end workflow across frontend, backend, and ML components
- Focused on application architecture and system integration

**Tech stack:** Python, Fastapi, FastHTML, YOLO, Docker

### EEPROM SPI Memory Driver (25LC040A) ([task1](https://github.com/mmmhdp/infotecs_junior_position_assigment))

*Completed as part of the selection process for a Junior Developer position*

- Designed and implemented a C++ abstraction layer for SPI EEPROM (25LC040A) using a bit-banging driver  
- Developed a memory access API supporting bit-, byte-, and buffer-level read/write operations  
- Designed interface-based architecture (`i_memory_device_api`, `i_chip_spi_api`) to decouple hardware access from memory logic  
- Implemented address management and command framing according to the SPI EEPROM protocol  
- Documented all public interfaces, constants, and enumerations using Doxygen  
- Analyzed architectural changes required for supporting NOR Flash (W25Q128), including page programming, sector erase, 24-bit addressing, and read-modify-write logic  
- Structured the project with clean modular layout and compilation-ready C++ codebase  

**Tech stack:** C++, SPI (bit-banging), Embedded Systems Concepts, Doxygen, Git

### Custom Fixed-Size Memory Allocator ([task2](https://github.com/mmmhdp/infotecs_junior_position_assigment))

*Completed as part of the selection process for a Junior Developer position*

- Implemented a custom memory allocator in pure C supporting two fixed allocation sizes (15 and 180 bytes)  
- Designed separate memory pools with free-list management for efficient block reuse  
- Implemented buffer-based allocation strategy, splitting large buffers into fixed-size blocks  
- Ensured low allocation overhead and fast O(1) allocation/deallocation via linked free lists  
- Added pointer ownership validation with fail-fast behavior on invalid free  
- Designed platform-adaptive bootstrap layer using `malloc` (NAIVE_BOOTSTRAP) or `mmap` (POSIX_BOOTSTRAP) depending on availability  
- Ensured compatibility across 8-bit, 16-bit, and 32-bit architectures  
- Wrote unit tests using Google Test to verify allocation, reuse behavior, and error handling  
- Structured the project as a clean, modular, compilation-ready C codebase  

**Tech stack:** C, Memory Management, Free Lists, mmap, Google Test, Git

### LRU Cache Implementation in C ([caching](https://github.com/mmmhdp/bscalg/tree/main/calg/caching))

*Pet / Educational Project*

Implemented a Least Recently Used (LRU) cache in pure C supporting constant-time operations

Built core data structures: a hash map for fast key → node lookup and a doubly linked list for tracking usage order (most recently used → least recently used) to support O(1) get/put semantics

Designed eviction logic that automatically removes the least recently used entry when capacity is exceeded

Managed memory manually, including dynamic allocation, pointer linking, and clean deallocation

Developed comprehensive unit tests validating correctness of cache operations, eviction policy, and edge cases

Structured code for modularity and reuse, with clear interfaces between data structures and cache logic

Tech stack: C, Hash map, Doubly linked list, Memory management, Unit testing, Git

---

## Education

### Municipal Secondary School No. 145  
**2006–2017**

Physics and Mathematics Program.

### National University of Science and Technology MISIS  
**2021 – 2025**

**Bachelor’s Degree in Systems and Software Engineering**  

Specialization: Intelligent Data Analysis Systems  

Program focused on software engineering, system design, and applied machine learning with emphasis on real-world applications.

---

## Additional Training

### [C Programming Course (MIPT)](https://www.youtube.com/watch?v=7YhRFx-oyW4&t=52s)
- Completed an intensive course on C programming
- Solved a large set of algorithmic and systems-level problems
- Implemented an LRU cache in C as a final course project
- Worked with low-level memory management and data structures

[Solutions](https://github.com/mmmhdp/bscalg)

Original tasks: 

- [Original repository](https://github.com/tilir/c-graduate)
- [Related Yandex Contests](https://contest.yandex.ru/contest/66459/problems)

---

### [C++ Programming Course (Bachelor Level, MIPT)](https://www.youtube.com/watch?v=Bym7UMqpVEY&list=PL3BR09unfgciJ1_K_E914nohpiOiHnpsK&index=1)

- Completed and documented a full undergraduate C++ course
- Topics included:
  - Object-oriented programming
  - RAII
  - STL
  - Templates
  - Modern C++ concepts
- Currently focusing on applying C++ knowledge in practical projects

---

## Early Professional Experience

### Private Tutor (Mathematics & Physics)  
**2017 – 2021**

- Provided individual and group tutoring in mathematics and physics
- Worked with students of different skill levels

---

### Co-founder, Educational Training Center  
**2019 – 2020**

- Co-founded and managed a small educational center
- Organized learning programs and coordinated instructors
