# Day 08 - [Topic]

## Objective

What was the goal for today?

Architecture of Linux 

---

## What I Learned

- Linux follows a layered architecture, where each layer has a specific role and responsibility. The main components of Linux operating system are: Kernel, Shell, Hardware, Application and Utilities
- The Kernel is the core component of the Linux operating system that sits between the hardware and user space, managing system resources and ensuring smooth communication between software and hardware. The kernel is responsible for: Memory management, Process management, Resource allocation, Device management, Application interaction and
Security.
- Types of Kernel:
- 1. Monolithic Kernel: Offers high performance due to direct communication between components, but the large kernel size makes it more complex and harder to maintain. All core operating system services such as process management, memory management, device drivers, and file systems run in kernel space, sharing the same memory.
  2. Micro Kernel: Only essential services like process scheduling and memory management run in kernel space, while other services execute in user space. Micro kernel provides better security and modularity, but may suffer from performance overhead due to frequent inter-process communication.
  3. Exokernel: exposes hardware resources directly to applications, allowing them to manage resources at a low level. Enables high flexibility and performance, but increases application complexity due to minimal abstraction provided by the kernel.
  4. Hybrid Kernel: Combines features of monolithic and microkernel architectures, keeping critical services in kernel space while supporting modular components. Delivers balanced performance and flexibility, making it suitable for modern systems that require both speed and stability.

- Shell: can be determined as the interface to the kernel. It takes commands from the user and interprets them. The shell transmits these commands to the kernel, which then performs the requested operations. Users can just enter the command by using the kernel's function that specific task is performed accordingly.
- Different types of shell: Each shell offers unique features and user experiences for interacting with Unix/Linux systems, from basic scripting to advanced customization.
- 1. Bourne Shell (sh): its one of the earliest Unix shells, providing basic command execution and simple scripting capabilities. It is also reliable and lightweight, and still widely used for system scripts and compatibility purposes.
  2.  C Shell (csh): Designed with a syntax similar to the C programming language, making it familiar to C developers. It is less suitable for complex scripting.
  3.  Bash (Bourne Again Shell): This is an enhanced version of the Bourne Shell with features like command history, tab completion, and scripting improvements. It is the default shell used on most Linux distributions.
  4.  Korn Shell (ksh): it combines features of the Bourne Shell and C Shell while maintaining backward compatibility. It is widely used in enterprise environments for its powerful scripting and stability.
  5.  Z Shell (zsh): is a highly customizable shell that integrates features from Bash, ksh, and csh.
Popular among developers for its themes, plugins, and advanced auto-completion.
---

## What I Built / Practiced

- 
- 

---

## Challenges Faced

- 
- 

---

## Key Takeaways

- The kernel is the core of the operating system that manages hardware and system resources. It controls how processes are executed, scheduled, and isolated to maintain system stability and security.
- The Shell is the command interpreter that processes user input.Different types of shell offer unique features and user experiences for interacting with Unix/Linux systems, from basic scripting to advanced customization.eg Bash,Zsh,ksh,csh

---

## Resources

- https://www.geeksforgeeks.org/linux-unix/architecture-of-linux-operating-system/

---

## Output

(Include links, screenshots, code snippets, or results)
