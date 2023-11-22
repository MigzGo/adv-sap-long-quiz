## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
-The Service Oriented Architecture or SOA is a software were you can reuse and able to exchange 
the informations tru service interface. So this service contract between the service provider
and the service consumer, also this service used standard network protocol such as SOAP(simple 
object access protocol)/HTTP or JSON/HTTP to send and requests to read or exhange datas.

2. List and discuss the characteristics of SOA.
-•Standarize Service Contract - usually used to outline agreements in low-risk and low-value 
scenarios. They’re especially helpful if you need to send out contracts on a large scale.

•Loose coupling - this characteristics specify how this service minimize the dependencies on each other and create specific types of relationship between service contract, service implementation, and service consumers.

•Abstraction - This characteristics is one of the most important principle in SOA because it avoids the unnecessary service information or even data. This principle reduces the number of subject matter experts needed for these tools freeing up resources.

•Reusability - This characteristic is creates a innovation from the existing services and maximize the potential of the old services.

•Autonomy - This characteristic is about the ability of a service must stand alone on it's own and not depending on others and must be more isolated means away and carrying on it's own.

•Statelessness - A service deals with moments in time. Meaning you, it has no memory and does not track any data or even store it.

•Discoverability - Simply this characteristic is about your service must be able to reach or to found by a customer. A discovery portal promotes reuse through clear and concise search and documentation.

•Composability - this principle make the bigger problem into smaller one to make it easier to solve it 

•Interoperability - Your service must be flexible and having the structure and codification of data is uniform among all systems involved

3. Define Microservices.
-Microservices is like a SOA having those characteristics but in microservices typically builds application that makes them more efficient, quickly to use and also resilient. On the pther hand, microservices is a architectural style that structures an application as a collection of services that are Independently deployed, loosely coupled and own my small team.
4. List and discuss the benefits of using Microservices.
-•Componentization via Services - It is independently replaceable and upgradable unit of software.

•Organized around Business Capabilities - this principle is breaking down services by its capabilities.

•Products not Projects - The whole responsibility for the software in production relies with the development team.

•Smart endpoints and dumb pipes - aim to be as cohesive and detached as possible, so they have their own domain logic and use Restful APIs to receive requests, apply logic, and provide responses.

•Infrastructure Automation - This means that deployment should be automated for each new environment and microservice independently.

•Scalable - This makes it possible for teams to assign resources more effectively and guarantees that the application can manage higher usage or traffic volumes.

•Technology Agnostic - As a result, selecting the appropriate tool for the task becomes simpler and is not dependent on a certain technological stack.

5. List and discuss the similarities and differences of SOA and Microservices.
-•Communication - In the difference between SOA and microservices in terms of communication is in Microservices is they are independently functional so it doesn't affect one another. On the other hand, SOA is using common communication mechanism that may affect one another if the othe system got slower or may failed.

•Interoperability - SOAs are open to diverse messages and protocols. Microservices keep things simple and use messaging such as HTTP/REST.

•Service granularity - the similarity of both service is same service are flexible and having the structure and codification of data is uniform among all systems involved. Thus, SOA offers a wide range of services. These range from little, specialized services to enterprise-wide services. All microservices are specialized. Each is designed by programmers to perform a certain function very effectively.

•Speed - Sharing a basic architecture can assist SOAs when simplifying troubleshooting and ongoing development. On the other hand, SOAs may work more slowly, which limits sharing and favors duplication.

6. Define Web Services.
-A web service is a software feature that may use common protocols to interact via the internet with other applications.
Also, web service is a dynamic applications that can be described, published, located or invoked over the network to create product, process and supply chains.

7. List and discuss the benefits of using Web Services.
-•Exposing the existing function on the network - You can access the exisitng funtion using HTTP request. So other program can use and access the funtionality of your program.

•Interoperability - Lots of program or application can communicate to each other using some application like VB and .NET that can interact with JAVA web service. Also it can run independently.

•Standarize Protocol - At both the transmitting and receiving sides of the system, certain guidelines and protocols must be agreed upon in order for device communication to be effective. These guidelines and protocols.

•Low Cost Communication - You can implement web services using the inexpensive internet you currently have. Compared to proprietary systems like EDI/B2B, it is far less expensive. It is also possible to deploy web services using dependable transport protocols such as FTP.

8. List and discuss the characteristics of Web Services.
-•XML-Base - Web services employ XML as its data format, which guarantees network and cross-platform compatibility. As a result, web service applications have high interoperability.

•Loosely Coupled - A system, network, or software application that relies on its components to the least amount possible is said to be loosely coupled. The degree of direct knowledge that one element possesses about another is referred to as coupling.

•Coarse-Grained - More complexity in design, fewer cells for different operations, and a wider service scope for coarse-grained services compared than fine-grained services. Meaning we can transform the whole dataset but not an individual element on the dataset

•Ability to be Synchronous or Asynchronous - Asynchronous capability is essential for enabling loosely coupled systems. Synchronous clients receive their results immediately upon completion of the service, while asynchronous clients receive their results later.

•Support RPCs - Through the use of an XML-based protocol, web services enable clients to call functions, procedures, and methods on the remote object. The input and output parameters that a web service needs to support are exposed by remote procedures.

•Support Document Exchange - These documents can be a simple as representing a current address, or they can be as complex as representing an entire book or RFQ. Web services allow documents to be exchanged transparently, which makes business integration easier.

9. List and discuss the distinct roles in Web Services Architecture.
-•Provider - The web service is created by the provider and made available to client applications upon request.

•Requestor -A requestor is a client application, such as a Java or.Net app, that looks for functionality via a web service.

•Broker - The broker can access the UDDI that enables the client application to locate the web service.

•Publish - The publish make the interface service accessible to the clients.

•Find - The requestor consults the broker to locate a published web service

•Bind - This is from the broker, the requestor or a client can able to bind and/or invoke the service.

10. List and discuss the Web Services Components.
-•SOAP - The message format for this application communication protocol is XML. Furthermore, SOAP is an independent platform built on top of XML.

•WSDL - WSDL is used to describe web services. It specifies the location of the service, and the methods of the service

•UDDI - Another XML-based standard for publishing, describing, and locating information about web services is called UDDI. This specific group of globally replicated registries represents what it is.

•SOAP web services - A SOAP web service is a network protocol that allows various computers or applications to exchange structured data based on XML. Also this is similar to other platform that is language independent
