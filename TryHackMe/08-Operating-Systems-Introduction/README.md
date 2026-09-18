## TryHackMe – Operating Systems: Introduction

### Status
Completed successfully – 100%

### Platform
TryHackMe

### Overview
In this room, I learned the fundamentals of operating systems and the role they play in managing computer hardware, applications, users, files, and system resources.

I also explored how operating systems separate privileged system functions from normal user applications and how different operating systems are designed for different devices and environments.

### Tasks Completed

#### Task 1 – Introduction
I was introduced to the role of an operating system and why it is important in modern computing.

I learned that the operating system acts as the main layer between the user, applications, and the physical hardware.

### Operating System Structure
I learned that the basic relationship is:

- User
- Applications
- Operating System
- Hardware

The operating system manages the interaction between applications and the computer’s physical components.

#### Task 2 – The Invisible Manager
I learned that an operating system manages many important system resources and activities.

These include:

- Process management
- Memory management
- File system management
- User management
- Device management

### Kernel Space and User Space
I learned about two important privilege areas:

#### Kernel Space
Kernel space is the highly privileged area of the operating system.

It has direct access to:

- CPU
- Memory
- Storage
- Hardware devices

The kernel runs inside kernel space and manages core system resources.

#### User Space
User space is where normal applications run.

Applications in user space do not have unrestricted access to hardware.

Instead, they request services from the kernel using system calls.

This separation improves security and system stability.

### Operating System Security
I learned that operating systems provide important security features such as:

- Authentication
- Permissions
- Process isolation
- System protection
- User account management

These protections help prevent unauthorised access and reduce the risk of applications interfering with each other.

### Hands-On System Investigation
In the practical exercise, I used the Ubuntu system monitor to inspect the system.

I identified:

- Ubuntu MATE version: `1.26.2`
- Memory allocated: `1.9 GiB`
- File system type for `/dev/root`: `ext4`

I also explored the Linux file system and identified three user home directories:

- `alex`
- `guest`
- `ubuntu`

I navigated to Alex’s home directory and opened the `Documents` folder.

Inside `note.txt`, I found the flag required for the exercise.

#### Task 3 – OS Interaction and Landscape
I learned about the two main ways users interact with an operating system:

### Graphical User Interface – GUI
A GUI allows users to interact with the system through:

- Windows
- Icons
- Menus
- Buttons
- Mouse and touch controls

### Command-Line Interface – CLI
A CLI allows users to interact with the operating system using text-based commands.

The CLI provides more direct and precise control over the system.

### Operating System Types
I learned about different categories of operating systems:

- Desktop operating systems
- Server operating systems
- Mobile operating systems
- Embedded operating systems
- Virtual and cloud operating systems

### Examples of Operating Systems
I learned about several operating system families and examples:

#### Desktop
- Windows
- macOS
- Linux

#### Server
- Windows Server
- Ubuntu Server
- Debian
- Red Hat
- Unix

#### Mobile
- Android
- iOS

#### Embedded and IoT
- Embedded Linux
- Real-Time Operating Systems

#### Virtual and Cloud
- Ubuntu LTS
- Amazon Linux
- Rocky Linux
- Alpine Linux

I learned that different operating systems are designed for different requirements such as performance, security, reliability, battery efficiency, scalability, and hardware limitations.

#### Task 4 – Conclusion
I reviewed the main operating system concepts covered in the room.

These included:

- Operating systems
- Kernel space
- User space
- GUI
- CLI
- User management
- Memory management
- Process management
- File systems
- Device management
- System security

### Skills Practised

- Operating system fundamentals
- Linux file system navigation
- System monitoring
- User directory identification
- File system inspection
- GUI navigation
- Kernel and user space concepts
- User and permission concepts
- File system concepts
- Basic system investigation

### What I Learned
This room helped me understand how an operating system controls and coordinates the different parts of a computer.

I learned how the operating system manages processes, memory, files, users, devices, and security.

I also gained practical experience navigating a Linux system, inspecting system information, identifying user directories, and locating files.

### Reflection
Completing this room strengthened my understanding of operating systems, which is important for cybersecurity, digital forensics, networking, cloud security, and system administration.

The practical exercises also helped me become more comfortable navigating Linux and inspecting system information.
