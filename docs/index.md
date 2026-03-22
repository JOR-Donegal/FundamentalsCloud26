# Introduction

!!! abstract "Fundamentals of Cloud Computing"

The first week in all my modules is introductions and by now, you should have gone through my "Getting Started" notes.

Everyone has heard the term _cloud computing_, but very few people know how to define it succinctly. 

Up until 2005 or so, every time we had to create a new service in a company or on the Internet, we had to have a big, expensive, and complex infrastructure to make that service work. 

Imagine we were creating a new service… say a web site. First, we would need to spend thousands of Euro on servers, big powerful computers with a lot of memory and storage space. Then we would need to get all the add on bits to make things work. Then we need all the network equipment, switches and routers, firewalls, and load balancers. Getting someone to configure all of this is expensive; consulting rates in our business might be between €500 and €2,000 per day. Then we must buy software licenses, this might cost more than all the other stuff we have just bought! Finally running all this equipment is also very expensive, in fact the running costs of this equipment over 2 years will be more than all the equipment cost in the first place. 

There are two types of expense. 

__CAPEX__ or capital expenditure. You buy the equipment and right-off the cost over five years or so.

__OPEX__ is operational expenditure. You pay per week/month/resource to operate something. 

In classical computing, we purchase €100,000 of equipment and have operating costs €40,000/year in power, heating, repairs, and maintenance etc. And you are located at one place only. 

As you can imagine that old way of doing business was slow, inflexible, and very expensive! And if you run out of capacity, it takes weeks and ++money to add capacity. 

Think about retail operations around December each year in Ireland, they peak in operations for Christmas, during business hours. A traditional IT operation must size everything for that peak. 

These days, we do things in a much smarter way. Computers are now so powerful that we can divide up their memory and run many “virtual” computers inside one physical computer or _host_. All these _virtual machines_ think they are real, that they have their own memory and network connections and hard disk space… but they do not. If you have seen the movie, the Matrix, then you probably get the idea (mandatory viewing fo0r cloud students).

Lean the terms, this module is all about them. We call these physical servers _hosts_ and the virtual computers which run inside them _virtual machines_ or _VMs_ for short. 

Whenever we need to create a new service, we connect to a host and copy a pre-made template. It takes about a minute to create a new, fully configured, complicated server as a VM. In the old days it might have taken us weeks from the start of a project until we had our server running. And we can do this repeatedly, without needing extra hardware, without spending more money on equipment and without even being on the same continent where the equipment is. 

Magic!