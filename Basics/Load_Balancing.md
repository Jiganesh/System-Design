Load Balancing : 
Load balancing is the method of distributing network traffic equally across a pool of resources that support an application. 
Modern applications must process millions of users simultaneously and return the correct text, videos, images, and other data to each user in a fast and reliable manner.

![LoadBalancer](/images/LoadBalancer.png)


Load Balancing Algorithms

There is a variety of load balancing methods, which use different algorithms best suited for a particular situation.

- Least Connection Method — directs traffic to the server with the fewest active connections. Most useful when there are a large number of persistent connections in the traffic unevenly distributed between the servers.

- Least Response Time Method — directs traffic to the server with the fewest active connections and the lowest average response time.

- Round Robin Method — rotates servers by directing traffic to the first available server and then moves that server to the bottom of the queue. Most useful when servers are of equal specification and there are not many persistent connections.

- IP Hash — the IP address of the client determines which server receives the request.



Load Balancing Easy : https://www.youtube.com/watch?v=K0Ta65OqQkY&list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX&index=3

Load Balancing Deep : https://avinetworks.com/what-is-load-balancing/