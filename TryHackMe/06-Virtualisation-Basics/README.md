## TryHackMe – Virtualisation Basics

### Status
Completed successfully – 100%

### Platform
TryHackMe

### Overview
In this room, I learned the fundamentals of virtualisation and how it allows one physical computer or server to run multiple isolated virtual machines.

I learned why virtualisation is widely used in modern IT environments to reduce hardware costs, improve resource utilisation, support scalability, and provide isolated environments for applications and testing.

### Tasks Completed

#### Task 1 – Introduction
I was introduced to the concept of virtualisation and why organisations use it.

I learned that running every application on a separate physical server can be expensive and inefficient.

Virtualisation allows organisations to make better use of physical hardware by running multiple virtual systems on the same machine.

#### Task 2 – Virtualisation Overview
I learned about the problems associated with using separate physical servers for individual applications.

These included:

- High hardware costs
- Low resource utilisation
- Slow deployment
- Difficulty scaling systems
- Increased electricity, cooling and maintenance requirements

I learned that virtualisation allows multiple applications and operating systems to safely share the resources of one physical server.

### Hypervisor
I learned that a hypervisor is software that creates and manages virtual machines.

The hypervisor distributes resources such as:

- CPU
- RAM
- Storage
- Networking

It also keeps virtual machines separated from each other.

I learned about two main types of hypervisors:

- Type 1 Hypervisor – runs directly on physical hardware
- Type 2 Hypervisor – runs inside an existing operating system

Type 1 hypervisors are commonly used in servers and data centres, while Type 2 hypervisors are useful for learning, testing and home lab environments.

Examples of Type 2 hypervisors include VirtualBox and VMware Workstation.

#### Task 3 – Virtualisation Components
I learned that a virtual machine behaves like a separate computer even though it shares physical hardware with other virtual machines.

Each VM can have its own:

- Virtual CPU
- RAM
- Storage
- Network connection
- Operating system
- Applications
- Settings

I also learned the difference between virtual machines and containers.

### Virtual Machines
A virtual machine contains a complete operating system and behaves like an independent computer.

### Containers
Containers are lighter than virtual machines and usually run individual applications.

Containers share the host operating system kernel, which allows them to start quickly and use fewer resources.

I also learned that Docker is commonly used to create and manage containers.

#### Task 4 – Managing Virtual Machines
In the practical exercise, I used a simulated Virtualisation Manager.

I inspected the status of multiple virtual machines and physical hosts.

I learned how administrators can monitor:

- Running virtual machines
- Stopped virtual machines
- CPU allocation
- Memory allocation
- Disk allocation
- Host resource usage
- Virtual machine status

I identified a problem with the Mail Server virtual machine and restored it to a running state.

I also analysed the environment to identify:

- The VM that had been running for the longest time
- The VM using the most memory
- The number of running VMs
- The physical host running the largest number of VMs

This helped me understand how virtualisation environments are monitored and managed in practice.

#### Task 5 – Conclusion
I reviewed the main concepts of virtualisation and its importance in modern IT.

I learned that virtualisation provides benefits including:

- Cost savings
- Better hardware utilisation
- Isolation
- Faster deployment
- Flexibility
- Portability
- Scalability
- Centralised management
- Safer cybersecurity testing

### Skills Practised

- Virtualisation fundamentals
- Virtual machine concepts
- Hypervisor concepts
- Type 1 and Type 2 hypervisors
- Virtual machine resource allocation
- CPU and memory monitoring
- VM lifecycle management
- Physical host monitoring
- Containers and containerisation
- Docker concepts
- Infrastructure troubleshooting
- Resource utilisation analysis

### What I Learned
This room helped me understand how one physical server can support multiple virtual machines while keeping each environment separate.

I learned the role of the hypervisor in managing physical resources and distributing them between virtual machines.

I also learned how virtual machines differ from containers and why both technologies are important in modern IT and cloud environments.

### Reflection
Completing this room strengthened my understanding of virtualisation, which is important for cybersecurity, networking, cloud computing, cloud security and digital forensics.

The practical Virtualisation Manager exercise also helped me understand how administrators monitor and troubleshoot virtual infrastructure in real-world environments.
