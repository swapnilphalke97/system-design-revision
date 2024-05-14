# system-design-revision

## [CS75 (Summer 2012) Lecture 9 Scalability Harvard Web Development](https://youtu.be/-W9F__D3oY4?si=oE2LquIcABKw5T8L)

Complete lecture is well summurised in  [Harvard_CS75_Notes](https://ninefu.github.io/blog/Harvard_CS75_Notes/)  and
[medium post/sakshi8699](https://sakshi8699.medium.com/notes-from-harvard-scalability-lecture-56d9c04f4ab2). 

More concise summuary is,
#### Vertical Scaling

- *Upsizing:* Make your machine stronger by upgrading its components.
- *Single Mighty Machine:* Enhance one machine's power instead of adding more.
- *Easy Setup, Limited Growth:* Simple but hits limits fast.

#### Horizontal Scaling

- *Teamwork:* Many small machines work together, sharing the load.
- *Divide and Conquer:* Spread work across multiple machines for easier handling.
- *Endlessly Expandable:* Keep adding machines as needed for flexibility.

#### Load Balancing with Bind

- *Equal Distribution:* Spread workload evenly across servers.
- *Managed Traffic:* Bind tool helps in fair load distribution.
- *Prevents Overloading:* Keeps servers from getting overwhelmed.

#### RAID 1, 10, 0

- *Data Protection:* RAID systems ensure data redundancy and/or speed.
- *RAID 1:* Mirrors data for safety.
- *RAID 10:* Combines safety and speed.
- *RAID 0:* Speeds up data access but lacks redundancy.

#### Caching

- *Quick Access:* Stores frequently used data for faster retrieval.
- *Temporary Storage:* Keeps frequently accessed data close by.
- *Boosts Performance:* Speeds up operations, especially for popular content.

#### Load Balancer

- *Traffic Management:* Distributes incoming requests among servers.
- *Smart Routing:* Sends requests to least busy server for balanced load.
- *Ensures Smooth Performance:* Prevents servers from becoming overwhelmed.

#### Security

- *Protection Layers:* Multiple security measures safeguard systems.
- *Comprehensive Defense:* Includes firewalls, encryption, and password protection.
- *Continuous Monitoring:* Keeps systems secure against potential threats.

#### Replication

- *Purpose:* Replication involves duplicating data across multiple locations or servers for redundancy and improved availability.
- *Techniques:* Master-slave replication, multi-master replication.
- *Benefits:* Enhances fault tolerance, reduces data loss risk, improves system reliability.
  
Another article to help understand scalibility - [https://newsletter.ashishps.com/p/scalability](https://newsletter.ashishps.com/p/scalability)
