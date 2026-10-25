[English](./index.md) | [Русский](./ru.md)

# Nikita Maltsev

C++ Developer

---

## Contact Information

Location: Moscow, Russia

Telegram: `@hfhhdp`

Email: `malcevnik99@gmail.com`

GitHub: [mmmhdp](https://github.com/mmmhdp)

---

## About Me

C++ developer working on on-device recognition software and the tools used to develop, debug, and test it.

---

## Technical Skills

**Programming languages:** C++, C, Python

**Libraries and frameworks:** Qt6, Google Test 

**Build and development tools:** CMake, CTest, Make, Git, Docker

**Languages:** Russian, English (C1)

---

## Professional Experience

### SmartEngines — Junior C++ Developer

**March 2026 – Present**

Member of both the Face Recognition Engine team and the Internal Tools team, developing on-device recognition software, debugging tools, and automated testing infrastructure.

- Refactored the face recognition pipeline into separate frame and region-processing components, enabling parallel processing of detected faces within a frame; also parallelized face embedding computation using the company’s cross-platform concurrency library.

- Improved responsiveness of a Qt6 debugging application by moving log parsing and process management off the GUI thread and implementing batched UI commands with configurable update frequency and batch size.

- Extended the debugging application with legacy-protocol support, configurable loggers, reusable launch configurations, and integration with GDB and Qt Creator on Linux.

- Developed reusable Google Test infrastructure and migrated test suites across document and identity recognition engines. Reduced execution time of an identity-engine test suite from approximately 705 to 402 seconds (43%) through parallelization, decomposition, and removal of redundant executions; confirmed results locally and in the build infrastructure.

- Rebuilt liveness timers around a consistent, typed interface using `std::chrono`; implemented specialized timers, controllable test doubles, and tests for timing-dependent behavior.

- Developed a Python parser for CTest and Google Test logs, producing structured JSON reports with failed test cases and diagnostic details, including sanitizer output, for automated developer notifications.

- Added Linux SDK build and test support for ASan, UBSan, and LSan; configured UBSan findings to fail automated tests, with targeted suppression lists for third-party code.

---

## Selected Projects

### EEPROM SPI Memory Driver — C++

[Source code](https://github.com/mmmhdp/infotecs_junior_position_assigment)

*Technical assessment project*

- Implemented a C++ abstraction for accessing 25LC040A SPI EEPROM through a bit-banging driver.
- Developed an API for reading and writing individual bits, bytes, and byte arrays; documented public interfaces using Doxygen.

**Technologies:** C++, CMake, Doxygen

### Custom Fixed-Size Memory Allocator — C

[Source code](https://github.com/mmmhdp/infotecs_junior_position_assigment)

*Technical assessment project*

- Implemented a memory allocator supporting two fixed allocation sizes.
- Wrote Google Test unit tests covering allocation, block reuse, and error handling.

**Technologies:** C, Google Test, CMake

### Farseer — Real-Time Video Stream Analysis Service

[Source code](https://github.com/mmmhdp/farseer)

*Coursework*

- Developed an asynchronous service for analyzing RTSP video streams using a microservices architecture.
- Implemented a REST API for managing service requests and integrated YOLO-based object detection.

**Technologies:** Python, FastAPI, PostgreSQL, Redis, MinIO, Docker

---

## Education

### National University of Science and Technology MISIS

**2021–2025**

**Bachelor’s Degree in System and Software Engineering**

Specialisation: Intelligent Data Analysis Systems

Coursework in software engineering and applied machine learning.

---

## Additional Training

### MIPT C and C++ Programming Courses

Completed bachelor’s-level courses in C and C++.

- [C programming course](https://www.youtube.com/watch?v=7YhRFx-oyW4&t=52s)
- [C++ programming course](https://www.youtube.com/watch?v=Bym7UMqpVEY&list=PL3BR09unfgciJ1_K_E914nohpiOiHnpsK&index=1)
- [C programming assignments](https://github.com/mmmhdp/bscalg)
