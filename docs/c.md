# Introduce Virtualization

Since c. 2006, the way we do business computing has changed radically. If you have the skills and understanding to embrace _virtualization_, you are on a roll! If not, you are missing a revolution in how our industry works…and you are in danger of appearing uneconomical in the way you do business. 

This technology is in use in the largest, cloud scale data centres in the world, it is the enabling technology behind the cloud revolution. In can also be used in small SMEs to increase availability and reliability and to solve problems which were not previously economic to solve. 

In our modules, we normally introduce virtualization by teaching how to virtualize on the desktop. This means using an ordinary computer or laptop, but making it act like a small data centre! Whenever we implement virtualization on resources we own and control, we refer to this as _private cloud_. And we refer to the tools and techniques as enterprise virtualization. 

Once we cover basic concepts in this way, we teach virtualization at the server as we would implement in a _Small/medium enterprise_ or SME. In Ireland, let’s call that a company of 100 employees or less. These were characterized by having many applications on diverse servers, with very little thought put into economy, scalability, availability or sustainability. Typically, when we baseline these servers, we see many devices at 10% CPU and <50% disk capacity. What a waste! Up to 2026, my preferred configuration for an SME is two physical servers and the use of public cloud services, almost regardless of what their requirements are. Microsoft Hyper-V was the most popular platform we saw for SME’s probably due to its familiarity and relative ease of use. 

At the next level up are enterprise data centres; we need to use special tools to allow for a highly reliable and flexible implementation of virtualization. Enterprise typically used VMWare or Microsoft’s Hyper-V for these implementations. With the takeover of VMWare by Broadcom, VMWare products have exited most of their previous market.

The largest scale we can operate at is referred to as the _Cloud Scale_; Amazon, Microsoft, Google, etc. These are the companies who offer almost unlimited resources, on demand and we have come to refer to this as public cloud. We are likely to see these people create their own platforms and applications or use open source projects like the _kernel virtualization module_ (KVM) and OpenStack.

By 2026, this all began to change. World instability has led to a move away from any service outside the legislative jurisdiction you are operating in. For us, that means the EU. Any other option does not guarantee privacy, security. The ability to operate with external platforms can be removed with zero notice. We refer to these changes as data sovereignty and I like the new term, _sovereign cloud_.
