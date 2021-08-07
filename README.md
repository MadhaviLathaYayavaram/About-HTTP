# HTTP and History

## What is HTTP? ##

HTTP is an acronym for **Hyper Text Transfer Protocol**, which is an application layer protocol/Internet Protocol for data communication in World Wide Web (www).  We can see various links in a website, which are linked to other webpages or sites. These hypertext documents and hyper links are managed by HTTP servers. HTTP was developed by **Tim Berners-Lee** in 1989 at CERN, an European Organization for Nuclear Research. It was used in a semi-secured environment to exhcange only text files. RFC - HTTP (Requests for Comment)s were developed at the first stage with the coordination of World Wide Web Consortium (W3C) and Internet Engineering Task Force (IETF). 


## History of HTTP ##

At first, Ted Nelson initiated the term Hypertext in 1965. The CERN team headed by Tim Berners-Lee founded HTTP, its associated technology for a web server and also a text based web browser. He also started **World Wide Web** project in 1989, in which **Uniform Resource Locator (URL)** that connects the web documents, links, and all resources through an internet connection. Only **GET** method was available in the first version that requests for a webpage (HTML) from server. 

* The First Version  **HTTP 0.9** was documented in the year 1991. 

* The HTTP Working Group (HTTP WG) was formed in 1995 to develop rich meta-information, header fields, security protocol, and extended operations on HTTP. RFC (Requests for Comments) publication from the Internet Society approved **HTTP Version 1.0** in the year of 1996.

* **HTTP Version 1.1** was published in December 1995, which was officially implemented in January 1997. 

* **HTTP Version 2.0** was released in 2015, after many reformations through six partitions in Version 1. 

* **HTTP Version 3.0** is under development since 2020. 



### The important specifications of HTTP ###

HTTP provides basic authentication access and digest authentication access at the server before allotting the requested content to the client. HTTP performance can be accounted in the form of sessions that deal with network request and response transactions. Transmission Control Protocol (TCP) is connected to a server through ports to recieve client requests. Web applications can implement server side sessions, cookies, and hidden variables at the client location to manage the server data. 



## HTTP Version 0.9 ##

* The connection through port and TCP is closed after a single request and response action pair. 
* Only 'Get' method was used to transmit only HTML files, no other documents.
* No status codes are error codes were described to the client.


## HTTP Version 1.0 ##

* HTTP Headers were introduced for requests and responses which transmit the meta data and make the protocol flexible and extensible.
* A status code can be sent to the browser as the symbol of successful server response for a request.
* Documents and files other than HTML were able to get transferred. 


## HTTP Version 1.1 ##

* Persistent connections through keep-alive mechanism was achieved to reuse the connections for more than one client request. The 3-way Handshake connection would be used after the first request. 

* Chunk Transfer Encoding was introduced to stream persistent connections through pipelining rather than buffering. Multiple requests can be sent to server at a time and can utilize byte serving to receive a portion of resources. 

* Cache control mechanisms and content negotions were established. 

* server Colocation can be done using 'Host' header to avail the facility of hosting many domains at a same IP address.

* Netscape communications added SSL to encrypt and guanrantee the authentication of exchanged data through transmission. 

* Server-sent events and web sockets were introduced through advanced server APIs.


## HTTP Version 2.0 ##

* Binary protocals are impemented instead of text, and also opetimized for better performance. 

* Parallel requests can be handled at the same time through multiplexed protocol structure to avoid blocking constraints. 

* Duplicate headers are compressed among multiple requests.

* Server Push mechanism was developed that stores data in clients' cache to execute whenever required.


## HTTP Version 3.0 (under developement) ##

* HTTP extensibility is under research to add new extensions and features.

* Smarter CDN Caching mechanism is developed that allows the dissociation of identification of resources. 

* Client-hits are introduced to request the server according to local hardware and components requirement. 

* Cookie header is prefixed with secured cookies that cannot be altered, heading to secured connections.



## HTTP Request Methods ##

**Get, Head, Post, Put, Delete, Connect, Options, Trace, Patch** are the methods used to indicate the actions to be performed on different resources that are existing in the connection. 



