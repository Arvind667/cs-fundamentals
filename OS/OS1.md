# Operating Systems — Day 1 Notes

# 1. What is an Operating System?

Operating System (OS) is system software that acts as an interface between:
- User
- Applications
- Hardware

Main Work:
- Manage CPU
- Manage Memory
- Manage Files
- Manage Devices
- Manage Processes

Examples:
- Linux
- Windows
- macOS
- Android

Simple Definition:
> OS is a resource manager.

---

# 2. Goals of Operating System

- Convenience → Makes computer easy to use
- Efficiency → Uses hardware efficiently
- Resource Management → Handles CPU, memory, disk
- Security → Protects system and data
- Multitasking → Runs multiple programs

---

# 3. Types of Operating Systems

## 1. Batch OS
- Jobs executed in batches
- No user interaction

Drawback:
- Slow response time

---

## 2. Time Sharing OS
- Multiple users share CPU
- CPU gives time slices

Examples:
- Linux
- UNIX

---

## 3. Distributed OS
- Multiple computers work together
- Appears as one system

Advantages:
- Faster computation
- Resource sharing

---

## 4. Real-Time OS (RTOS)

Used where fast response is required.

Examples:
- Airbags
- Medical systems

Types:
- Hard RTOS → Missing deadline = failure
- Soft RTOS → Missing deadline acceptable

---

# 4. Kernel

Kernel is the core part of the Operating System.

Functions:
- Process Management
- Memory Management
- Device Management
- File Management

---

# Types of Kernels

## Monolithic Kernel
- Entire OS works in kernel space

Example:
- Linux

## Microkernel
- Minimal functions inside kernel

Advantages:
- Better security
- Better modularity

## Hybrid Kernel
- Combination of both

---

# 5. User Mode vs Kernel Mode

## User Mode
- Limited access
- Applications run here

Examples:
- Chrome
- VS Code

## Kernel Mode
- Full hardware access
- Operating System runs here

Why two modes?
- Security
- Prevent crashes
- Prevent unauthorized access

---

# 6. System Calls

System calls allow programs to communicate with OS.

Flow:
Application → System Call → Kernel

Examples:
- fork()
- exec()
- open()
- read()

Important:
System calls are expensive because:
- Context switching happens
- User mode changes to kernel mode

---

# 7. Booting Process

Steps:
1. Power ON
2. BIOS/UEFI starts
3. Bootloader loads kernel
4. Kernel initializes hardware
5. System services start
6. Login screen appears

---

# Types of Booting

## Cold Boot
- Starting system from OFF state

## Warm Boot
- Restarting system

---

# Important Interview Questions

## Q1. What is an Operating System?
OS is system software that manages hardware and software resources.

---

## Q2. Difference between OS and Kernel?

| OS | Kernel |
|----|----|
| Complete software | Core part of OS |
| Includes UI/utilities | Manages hardware |

---

## Q3. Why is kernel mode protected?
To prevent:
- System crashes
- Unauthorized access
- Memory corruption

---

## Q4. Why are system calls expensive?
Because mode switching and context switching happen.

---

# Quick Revision

- OS = Resource Manager
- Kernel = Core of OS
- User Mode = Limited access
- Kernel Mode = Full access
- System Calls connect applications with OS
- Bootloader loads kernel

---

# Memory Trick

PMFD

- P → Process Management
- M → Memory Management
- F → File Management
- D → Device Management