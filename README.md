# Lab 1: Linux Shell Implementation in C  
**Course:** Operating Systems (CSE X61)

## Overview
This project implements a **custom Linux shell** in **C**, developed as part of the Operating Systems course.  
The shell provides a simplified command-line interface that mimics core behaviors of Unix shells, focusing on **process creation, execution, and control flow**.

The objective of this lab is to gain hands-on experience with:
- Linux system calls
- Process management
- Command parsing
- Shell execution flow

---

## Features
- Execution of external Linux commands
- Support for command-line arguments
- Fork–exec execution model using `fork()` and `execvp()`
- Parent–child synchronization using `wait()`
- Continuous shell loop until termination
- Clean and readable execution flow

---

## Implementation Highlights
- Written entirely in **C**
- Relies on core Linux system calls:
  - `fork()`
  - `execvp()`
  - `wait()`
- Modular and structured code design
- Focused on clarity to demonstrate Operating Systems concepts

---

## Demo & Screenshots

### Screenshots
![Shell Execution](https://github.com/WorldisAmen/Linux-Shell-OS/assets/145727573/d5416bd5-e408-426a-a796-0b6685fc1f99)
![Command Handling](https://github.com/WorldisAmen/Linux-Shell-OS/assets/145727573/f01d8552-f84c-4e8c-acc1-7844a055dee9)
![Process Flow](https://github.com/WorldisAmen/Linux-Shell-OS/assets/145727573/b69946f3-f921-4484-9990-5e28afd8594d)
![Execution Output](https://github.com/WorldisAmen/Linux-Shell-OS/assets/145727573/2eec3420-b7e2-4dbb-91de-407107e2b0b7)

### Demo Videos
- https://github.com/WorldisAmen/Linux-Shell-OS/assets/145727573/3a114b27-aade-423f-8bf9-6afb951d3cec  
- https://github.com/WorldisAmen/Linux-Shell-OS/assets/145727573/5ebe7184-e837-4433-b69e-c9c0adb1bfde  
- https://github.com/WorldisAmen/Linux-Shell-OS/assets/145727573/26add34e-092e-4164-a4d6-34890f0806a7  
- https://github.com/WorldisAmen/Linux-Shell-OS/assets/145727573/4d682d98-ee2c-4053-bd07-67b6a8cd62e0  
- https://github.com/WorldisAmen/Linux-Shell-OS/assets/145727573/b84728de-18a4-4c0f-b2a9-e8b45ef74862  
- https://github.com/WorldisAmen/Linux-Shell-OS/assets/145727573/9018cdb4-736a-4f0f-a73f-2dbe1df55007  
- https://github.com/WorldisAmen/Linux-Shell-OS/assets/145727573/04cde82d-6e9d-46f2-99b3-36b8ec3e204a  

---

## How to Compile and Run
```bash
gcc shell.c -o shell
./shell
```
Run on a Linux-based operating system.
