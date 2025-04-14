Today we delved into Lesson 10 System & Services Adminstration wholeheartedly.
A process is a running program.
A daemon is a noninteractive program or special process that runs when system starts. It has no direct communicaiton with the user and detached from the keyboard and display.
It operates in the background and runs continuously without producing visible output.
A service is a interactive program running on the system. It operates in the background and can communicate with the end user.
A service is what a server provides.
Linux boot process involves the processor checks for the BIOS/UEFI firmware and executes. The BIOS/UEFI checks and locates bootable media, loads primary boot loader into memory which is a small program used to load the OS kernel.
The kernel configures hardware drivers (processor, bus, storage, and etc.).
The kernel is the core interface between hardware and processes. It loads initrd and mounts primary storage partition.
System initialization is the process that begins when the kernel is loaded into memory.
Systemd is set of tools to manage system resources and services. It's always assigned process ID 1 (pid-1).
Systemd manages all daemons, processes, targets, services as units - including itself.
Systemd unit is a unit which defines resources and services.
Systemd unit files are configuration files which define actions of resources and services.
Systemctl - main command for controlling systemd units, executes all tasks involving unit activation, deactivation, execution, interruption, and monitoring.
