# OperatingSystemLecture-notebook
Study note


An **Operating System (OS)** is the **core system software** that manages computer hardware and provides services to application programs. It acts as an **interface between the user, applications, and hardware**.

---

## 1️⃣ What an Operating System Does

### 🔹 Resource Management

* **CPU**: Process scheduling, multitasking
* **Memory**: Allocation, virtual memory, paging
* **Storage**: File systems, disk management
* **I/O Devices**: Keyboard, mouse, printer, network

### 🔹 Process & Thread Management

* Process creation and termination
* Inter-process communication (IPC)
* Context switching

### 🔹 File System Management

* Files & directories
* Access permissions
* Storage abstraction

### 🔹 Security & Protection

* User authentication
* Access control
* Process isolation

### 🔹 User Interface

* **CLI** (Command Line Interface) – e.g., Bash
* **GUI** (Graphical User Interface) – e.g., Windows Desktop

---

## 2️⃣ Main Components of an OS

| Component            | Description                                  |
| -------------------- | -------------------------------------------- |
| **Kernel**           | Core part managing hardware and system calls |
| **Shell**            | Interface for users to interact with OS      |
| **File System**      | Organizes and stores data                    |
| **Device Drivers**   | Control hardware devices                     |
| **System Libraries** | Provide APIs for applications                |

---

## 3️⃣ Types of Operating Systems

### 🔸 Batch OS

* Executes jobs in batches
* No user interaction

### 🔸 Time-Sharing OS

* Multiple users/processes share CPU
* Example: UNIX

### 🔸 Real-Time OS (RTOS)

* Deterministic response time
* Used in robotics, embedded systems
  *(relevant if you're learning robot programming)*

### 🔸 Distributed OS

* Multiple computers act as one system

### 🔸 Embedded OS

* Specialized OS for devices
* Example: FreeRTOS, VxWorks

---

## 4️⃣ Common Operating Systems

| OS          | Used For                        |
| ----------- | ------------------------------- |
| **Windows** | Personal & enterprise computing |
| **Linux**   | Servers, AI, cloud, embedded    |
| **macOS**   | Apple devices                   |
| **Android** | Mobile & embedded               |
| **iOS**     | Apple mobile devices            |
| **RTOS**    | Robotics, automotive, IoT       |

---

## 5️⃣ Kernel Architectures

| Architecture    | 특징                                   |
| --------------- | ------------------------------------ |
| **Monolithic**  | Fast, all services in kernel (Linux) |
| **Microkernel** | Minimal kernel, high stability       |
| **Hybrid**      | Mix of both (Windows, macOS)         |

---

## 6️⃣ Why OS Matters (Computer Science Perspective)

* Enables **abstraction** of hardware
* Ensures **efficient scheduling**
* Provides **security boundaries**
* Critical for **systems programming, AI servers, robotics**

---

## 7️⃣ If You Want to Go Deeper

Given your interest in **robot programming & system design**, useful next topics:

* Process vs Thread
* Scheduling algorithms (FCFS, Round Robin)
* Virtual memory
* Linux kernel basics
* RTOS vs Linux comparison

If you'd like, I can:

* Explain OS **from a robotics perspective**
* Give a **Linux OS learning roadmap**
* Compare **RTOS vs Linux vs ROS**
* Provide **OS interview-level explanations**

Just tell me 👍
