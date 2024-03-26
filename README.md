# HTTP


### What is the common thing that all the website have ?
In the address bar at the very fron HTTP , the hypertext transfer protocol.
Evey time to interect with website you use , http to request and response from browser and server.
Http defiles that how these , information transformed and transmitted over the internet.
Http helps to get the data from the server or databse and to post the data in data base through server.
Its the base for every website over internet. 


## What is HTTP?
Http is an acronium for Hypertext transfer protocol. 
A protocol to transfer hypertext. 

1. What is protocol?
2. What is hypertext?

In this context a protocol is the set of rules that allow for communication of an information between different entities like computers. 
Hypertext is the text that is displayed on a computer screen that contain hyperlink to other text. Web documents.


Http is the set of rules , servers and browsers use to transfer web documents back and forth.Thats why every url starts with http.



### Nature of http?

Its a plain language and human redable.
You can know its working by only knowing its name.

All http uses simple human language verbs.

 1. GET
 2. POST
 3. PUT
 4. DELETE
 5. CONNECT
 6. HEAD

### HTTP is a stateless Protocol

Every http request is unique and no other request is connected with single request.
Means http has no memory of previous request.
You can not go to the previous url.
SO that http provide us Session for sequence. 
Store state of usl between browser and server.
To detect the visitor of site , browser and server use cookie.
Cookie say that heyy you are looking to that picture last time.
HTTP is stateless but not session less.
Cookies store the session.

### For conversation of browser and server simultanuously we can add header.
HTTP Header:- Header contain every type of information about type of data and person who request with their machine.

1. What type of client sent the request.
2. Server configuration.
3. Time and date of the response.
4. Duration of data Storage
5. Data format.
6. Cookies to track session.

HTTP works based on request and response pairs.


## HTTP,HTTP_2,HTTPS?
Just like other technology http is also evolving and so many new features anre added to it . For fast and secure communication between server and computer.
HTTP/1.1 is old but HTTP/2 is new and it handle 70% of web transections.
HTTP/2 is more faster and secure. It uses compression algorithm to speedup request allows for multiplexing .allows to send multiple files over connection over time. And provide an incripted connection between client and server through HTTPS.




### HTTP/1.1


1. Uncompressed header.
2. Transfers one file at a time.
3. No default encryption.


#### Ideal

every HTTP>HTTPS using HTTP/2 protocol

#### Real

most HTTP>HTTPS over HTTP/2> Unencrypted HTTP/1.1




## HTTP Terminology


1. Browser:- Application used to access and navigate between HTML documents.(Types of browsers)
2. User Agent :- Client application. or application acting on the behalf of the user- typically a browser. or what ever application transporting the data from user to a server back.
3. TCP :- Short for transmission Control Protocol, one of the main internet protocol used by the World Wide Web, email, FTP and remote administration.
4. IP :- Short for internet Protocol, Ip is used to actually transfer data between computer over a network. Every device connected to the internet has an IP address.
5. URL :- Short for uniform resource locator, an address pointing at a resource on the web. A universaly understood address pointing at a resource pointing to a resource on the web.
6. DNS :- Urls are human redable address , stored in Domain Name Server, and configure to the IP adderess of  web servers. or Short for Domain Name Server, DNS catalogs all domain name URLs and points them to the IP address of servers. It contain both the URL and IP address.
7. Resource :- When you type in a Web address In the address abr of your browser. That address is automatically PREFIX with the HTTP or HTTPS telling you that you are using the Hyper text transfer protocol to access the resource  at the other end of that universal locator.
8. Server :- A server is a computer on the internet running some form of data storage and sharing application, most commonly a web server application. Allowing users to access their data through http protocol. HTTP is a client server protocol. Means the client or the user ,most commonly the browser Sends the request to the server and server sends the responses back to the client.
9. Proxy :- Proxy is a service Either software or hardware service acting as a middle person betwenn clients and servers. Pxoxies are offten used to hide the IP address of server . Its a proxy that handles data abck and forth eg: cognito mode hide the IP of your computer uses Proxy or you can use the Proxy to access the websites which are not commonly allowed to your browser.
10. Request - Response Pairs :- Client and server communicate over HTTP using request-response pairs. A request is sent, and a response is returned. When ever a client or browser tawlks to a server it does this by sending HTTP request to the server that request contain request method describing what action is requested. and address pointing to an resource and other r=information about the client.Response send a status code and the information about successful request.
11. Header :- request and response uses a HTTp Header to pass information back and forth. used to identify themselves and give information about what they want. Every request and response has a header. and some also have payloads. The header contains the metadata about request for clear communication between client and server.
12. HTTP Request Method/Verb :- Every HTTP request contains a request Method a verb. Explaining what action the sender wants to perform on the resource. eg GET to get something ,PUT to put something , UPDATE to update something and also for DELETE.
13. Status Response Code :- the header of an HTTP response always contains a Status response code. These are NUmerical code in the 100 to 500 range describing what type of response the server sent back to the client. 200 ok 404 not fount 500 server error etc.
14. Cache :- web servers and clients can cash so litterly store data for specific length of time to speed up of transfer and performance. eg when you visit a regular website your browser  likely download the css for that websites once and then cash it in its memory so when you nevigate to the next page and come to the side back later you dont need to redownload the css file website and webserver instruct browser to cash file clear cahed files. or update specific cashed files. All these things are done by the passing a cash header .
15. Stateless :- HTTP is a stateless protocol meaning every request and response unique , and no state is stored.
16. Cookie :- state is maintained by Cookies. Its String of data passes back and forth between the client and server to create a stateful session.
17. Session :- If you login to a site it state Logedin . It sote the login data of yours and when you open it again it makes request with your login data which is present in your browser cash. 

























