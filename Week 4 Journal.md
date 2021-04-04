# Journal for week 4

This week, I started working on my tasks. 
Some of the issues I expected MDS to face are,
- High latency when accessing the data from other countries (because the servers are not distributed).
- Packet loss
- Single Point of failure
- Complex and hard to maintain network
- Possible Monolithic nature of the server
- Too many ad hoc expansions made the network make it difficult to perform maintenance on servers or the network. 


Approaches that have the potential to solve the problems faced by MDS:
- Migrate to Microservices architecture: This may work but this will require a lot of development work that is out of the scope of this project. So, this idea is not considered.
- Host site at multiple data centres: This will eliminate the issues with High latency, packet loss and single point of failure. 
- Migrate to the cloud: Migrating to the cloud will not only solve the issues that are solved by hosting the data at multiple data centres but also make it very easy to manage the infrastructure. The cloud also makes it possible to use technologies like load balancers and distributed databases 
