# Hypervisors

The magic bit of software which allows operating systems to be virtualized is called a _hypervisor_, or sometime called a _virtual machine manager_ or VMM. There are several types on the market. The first distinction in hypervisors is based on what operating system they run on. In some cases, the hypervisor runs on top of a full operating system. This is the case with desktop products like VMWare Workstation, Microsoft Hyper-V and Oracle Virtual Box. In the data centre, having a full operating system on a host being used for virtualization is a waste of resources; more seriously, it means there are many other security vulnerability vectors. These are sometimes referred to as Type II hypervisors. 

Data centre products are typically VMWare ESXi or Microsoft Hyper-V. These can both be run without a full local OS. In VMWare’s case, ESXi is a completely cut down version of Red Hat Linux. In Microsoft’s case, Hyper-V Core runs with no GUI and almost no functionality from the console. These are sometimes referred to as Bare Metal or Type I hypervisors. 

Differentiating hypervisors based on being type 1 or type 2 can be quite misleading, however some vendors love to do so! 

In full virtualization, the VMM provides an abstraction which is identical to the underlying hardware. Some computer architectures are not fully capable of being virtualized and in these cases, paravirtualization must be used. The guest operating system is modified to include some virtualization instructions to allow it to operate as a VM.