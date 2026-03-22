# Characteristics

There are some key characteristics which most authorities attribute to virtualized environments. 

## Partitioning 
The first key concept in virtualization is that we can partition the memory of a computer such that multiple operating systems can operate simultaneously. We can run a server with ESXi or Hyper-V and using that operating system’s hypervisor, we can load in other OSs such as Linux, Windows or BSD. Partitioning can occur at different layers within a system; we can partition hardware, operating systems of applications. 

## Isolation 
VMs are isolated from each other and from the host operating system in which they run. In theory, any failure in a VM does not cascade beyond that VM. A malware infection in one VM should not be able to access any other VM. 

## Encapsulation 
Physically, a VM is made up of a settings file and a hard disk file (it may be more complex than this in some cases, but there are still just additional files). So a VM can be copied from place to place just like a file. It can be backed up, moved, etc. Where we have virtualization of other things like networks, we can represent an entity by files and scripts. In every case, the virtual entities are encapsulated and easy to manipulate. This has an enormous effect on the flexibility with which an administrator can manipulate them. 

## Hardware Independence 
A VM does not access the hardware of the host directly, instead it uses the virtual hardware layer which the host exposes to it. For example, the host might have one physical network card made by Intel, the VMs might have four network cards each, all emulated as if they were Broadcom cards. We can easily move a VM from a host with an Intel processor and 16GB of RAM to a host with an AMD processor and 192GB of RAM. There are some limitations when we do some very advanced functions like moving live VMs from system to system (called live migration).