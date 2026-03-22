# Virtualization Scope

Virtualization is the concept that we can separate the services (what the user or consumer sees and uses) from the underlying hardware and there are many scenarios in which we can do this.

We can virtualize computers, allowing us to run many virtual computers (VMs) within a single physical one (host). To differentiate from other forms of virtualization, we refer to this as _compute virtualization_. Most servers now run as virtualized instances.

We can virtualize the entire desktop, this can be a cheap and functional way of controlling configuration, applications and security. With desktop virtualization, workstations can be diskless and relatively inexpensive. Or desktops can reside in public cloud as _Virtual Desktop Infrastructure_ (VDI).

We can also virtualize desktop applications. This has many advantages in configuration stability and deployment but also deals with incompatible applications; years ago, we had two separate system, provided by the same government agency, which required different versions of Java and broke if the wrong version was also present!!

We can virtualize storage, letting a single storage array “pretend” to be hard disk storage space for many separate systems, creating advantages in terms of scalability, cost, efficiency, backup and data recovery. Modern techniques allow us to integrate storage from many locations to appear as an integrated, reliable system.

We can virtualize the network. Originally VLANs were a technology which allowed us to separate the logical network from the physical network. We still use VLANs in network design, but we have much more powerful tools in modern virtualization. We have the capability of creating switches, routers and firewalls which don’t physically exist. This field is called _Network Functions Virtualization_ or NFV. 

In all these kinds of virtualization, we are taking something like an operating system and running it in a container of some kind. The container appears to the operating system to be real hardware. For anyone who has seen the movie, its Neo in the Matrix; he thinks he is in the real world, but its just a virtual realty built around him. We didn’t know or predict many of the advantages of taking this approach, some of the advantages only became obvious as we began to use the technology. 

_Availability_ might be defined as a probability a system will be working at any point in time. As we separated our services from the underlying hardware, we were no longer exposed to outages because of hardware failures, limitations or maintenance. The ability to move live systems without service outages is called _live migration_, and this further improved our availability and fault-tolerance and our capability to create _high-availability_ (HA) systems. 

_Business Continuity_ considers our ability to become operational again after an event like a fire. You can now put a small enterprise data centre on a <€100 USB drive, go to any room with computers in it and re-establish the data centre. At a larger scale, replication from site-to-site is cheaper and more flexible. 

_Disaster recovery_ is at a different scale, but also becomes much more manageable. 

In a non-virtual world, most of our assets have low utilization, always a problem when justifying costs. Productivity and _Return on Investment_ (ROI) can be a big issue in the enterprise, where IT Services are often structured as a _cost centre_ rather than a _profit centre_. We can also optimize usage, moving services and shutting down equipment which is not required. 

Finally, there are logistical issues in any environment where our responsiveness is restricted by the availability of hardware. The new field often referred to as _Development Operations_ (DevOPs) requires flexibility and automation of resource allocation and configuration. Hardware based systems do not allow this flexibility. Our response is _Systems Operations_ or SysOPs. 