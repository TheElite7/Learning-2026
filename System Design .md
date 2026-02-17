# System Design

**1. Client Server Architecture**
+ It's a computing model where tasks and workloads are distributed between providers or resources or sercices and requesters of those services (Client).
+ The core concept is
  + Client - Initiates requests for services ( EX:- Web Browser, Mobile app)
  + Server - Listens for and responds to client requests ( EX:- Web server, Database server, file server )
  + Network - Communication medium between clients and servers, can be LAN, WAN or internet ( HTTP, FTP, SMTP )



**2. IP Address**
+ 



**3. Domain Name System**
+ It translate human-readable domain names (google.com) into machine-readable ip addresses (142.250.185.24).

```
User/Browser --> Local DNS Cache --> DNS Resolver --> Root DNS Server --> TLD Server --> Authoritative --> Website 
                                     (ISP/Public)    (13 Root Servers)  (.com .org, etc)   Name Server
```


**4. Proxy & Revers Proxy**
+ A proxy server acts as an intermediary or gateway between your device and the internet. When you use a proxy, your internet traffic first goes to the proxy server, which then forwards your request to the destination website. The website's response comes back to the proxy, which then sends it to you.

```
Your Device → Proxy Server → Internet → Website
Your Device ← Proxy Server ← Internet ← Website
```
+ Reverse Proxy works,

```
Internet User → Revers Proxy → Web Server 1
                             → App Server
                             → DB Server

```

**5. Latency**
+ Deploy the application in Multiple DataCenter in world wide.
+ The other countire user's can connect nearest Server in DataCenter.

**6. HTTP/HTTPS**
+ HTTP (Hypertext Transfer Protocol) is the foundation of data communication on the World Wide Web.
+ 

**7. Application Programming Interface (API)**
+

**8. REST API**
+ 

**9. GRAPHQL (API)**
+

**10. Data Base**
+ 

**11. SQL & NOSQL**
+ 

**12. Vertical Scaling**
+ 

**13. Horizontal Scaling**
+ 

**14. Load Balancer**
+ 

**15. Inexing**
+ 

**16. Replication**
+ 

