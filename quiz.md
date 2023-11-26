## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
 **In my view, SOA is a software development approach that promotes the reuse of code and services. This means that each service can be used over and over again in different applications. SOA services are designed to be self-contained and have their own data and code. This makes them easy to test and maintain. SOA is a good fit for business applications because it allows each service to perform a specific business function. SOA services can also communicate with each other, which makes it possible to build complex applications. SOA can be used to integrate software systems from different business domains. This makes it a versatile approach for software development.


2. List and discuss the characteristics of SOA.
** - Here are some of the characteristics of SOA 
*Standardized Service Contracts: Services need to follow a clear and consistent description of what they do, their capabilities, and their purpose. This involves using formal and standardized service contracts to make sure everything is clear and works well together.

*Loose Coupling: In this case, services should try to have as few dependencies on other services as possible and keep clear boundaries between them. This helps make sure that changes in one service don't affect others too much, making the whole system more flexible and easier to maintain.

*Abstraction: From my point of view, abstraction means that services hide their inner workings from outside users. This helps keep services loosely connected and allows clients to use services without needing to know how they work internally.

*Service Reusability: This is about designing services so that they can be used again in different situations. By putting specific functions into independent units, services become easy to reuse in various applications. This saves time in development and ensures consistency.

*Autonomy: Services should have the ability to control what they do without being influenced by external factors. This independence makes services more reliable, predictable, and isolated, contributing to the overall stability of the system.

*Statelessness: Services should aim to be stateless, meaning they don't store much data between interactions. This helps with scalability and makes service management simpler, as each request can be handled on its own without relying on previous states.

*Discoverability: Services should be easy for other services or clients to find. This can be done using service registries or metadata repositories that store important information about the service's purpose, capabilities, and how to use it.

*Composability: This means designing services to break big problems into smaller, more manageable parts. This modular approach encourages reuse and simplifies putting services together to create complex applications from reusable building blocks.

*Interoperability: Services need to follow industry standards and protocols to work well with different clients and users. This ensures smooth integration with various systems and platforms, making communication and data exchange easier.

3. Define Microservices.
**    In my view, Microservices are a bit like SOA because they both use separate pieces that work together to do a big job. But, unlike SOA that covers the whole company, Microservices mostly work on making separate applications. This helps these applications perform better, grow bigger, and stay strong. Microservices follow a cloud-based way of making things, so teams can change their code, use different tools for different parts, and make each part bigger on its own. This way is more flexible and costs less compared to making the whole application bigger just because one part needs it.

4. List and discuss the benefits of using Microservices.
** After reading the handout, I understood that Microservices are a popular way of designing applications that both developers and business leaders like because they fit well with how organizations want to structure their teams and development processes. Microservices break down applications into smaller, independent services that can be worked on, put into action, and adjusted independently. This way of doing things has several benefits:

*Faster Deployment: Small, independent services can be put into action fast without affecting the whole application. This lets organizations bring out new features and updates more frequently.

*Better Team Organization: Microservices make it possible to create small teams that work well together around a single service. This helps with working together and being flexible, making it easier for new team members to understand the code.

*Flexible Technology Choices: Each microservice can use the best tools and technologies for what it needs. This flexibility allows organizations to easily adopt new technologies.

*Precise Scaling: Separate services can be adjusted independently, made bigger or smaller as needed. This helps organizations use resources wisely and avoid using too much.

Microservices are often used with cloud-based infrastructure because the cloud gives access to on-demand, pay-as-you-use resources that microservices need to adjust efficiently. Cloud services also make managing microservices simpler by offering infrastructure as a service and platform as a service  choices.

5. List and discuss the similarities and differences of SOA and Microservices.
**  The main difference between SOA and Microservices is how they talk to each other. SOA, or Service-Oriented Architecture, is a way of building software systems where everything is treated like a service. It helps services talk to each other, often for sharing information and finishing different tasks. SOA has strong points like Standardized Service Contracts, Loose Coupling, Abstraction, and more.

On the flip side, Microservices are about a bunch of services that break down into small, shareable parts. This way is used for making applications and lets them talk in different ways, like using different programming languages and saving data. Microservices say this is good because it makes things happen quicker, organizes teams better, and has other benefits.

Even though SOA and Microservices are different, they also have some things in common. Both use a modular way of building, breaking big applications into smaller parts. This makes things flexible, easy to grow, and can be used again. They also keep things loosely connected, letting services work on their own and be changed without messing up the whole application. Another shared thing is the size of services: SOA services are bigger and do many things, while Microservices are smaller and do specific tasks. Both use common ways of talking, like HTTP and REST, so they can easily share information. Lastly, both SOA and Microservices are good for using in the cloud, where things can grow or shrink as needed.

6. Define Web Services.
** based on my understanding the Web Service is one of the piece of software that expressing itself through internet that using a standardized system that passes a message. Web services is a self contained, it is a modular, distributed and dynamic application that can feature, discover or call the different network to create a product, process and supply chains. It is also a collection of a open protocol and standardize that using a software that contains different languages and a program that can run different platform that can use a web services to change the data to computer network just like the internet in a way they are the same when it comes to inter-process communication of a computer

7. List and discuss the benefits of using Web Services. 
** Talking Between Applications

This benefit of a web service is the one that provides a way for different programs to communicate and exchange data and services with each other. It can also be used with diverse web services, such as VB or .NET, which can connect to Java web services and vice versa. It is also used to achieve collaboration among independent applications on various platforms and technologies.

**Using the Same Language

In this aspect, the web service follows a common industry protocol for communication. All four layers use specific protocols in the web services protocol stack. The alignment of the protocol stack can provide several benefits to different companies, such as choices, lower prices due to competition, and quality control.

**Cost-Effective Communication

Web services use protocols like SOAP over HTTP, providing clients with the ability to leverage the benefits of the internet for fulfilling web services. This approach is more reliable compared to exclusive solutions like EDI/B2B. It also offers a more efficient means of transportation, such as FTP.

8. List and discuss the characteristics of Web Services.
** XML-Based
-In web services, XML is utilized to represent and move data. The use of XML eliminates any limitations tied to networking, operating systems, or platforms. Applications developed using web services are highly compatible at their core.

** Loosely Connected
When a user engages with a web service, there is no direct dependency on that service. The web service interface can evolve without impacting the user's ability to interact with it. Conversely, in a closely connected system, modifications in one part necessitate updates in the other.

**Broad Scope
-Object-oriented technologies like Java expose their services through distinct methods, each designed to deliver substantial capabilities at a corporate level. Businesses and interfaces revealed by Java should possess an extensive scope. Web services technology inherently defines services accessing an appropriate amount of business logic.

**Synchronous or Asynchronous Capability
-Synchronicity denotes the link between the client and service execution. During synchronous calls, the client awaits the service completion before proceeding. Asynchronous operations permit clients to invoke a service and undertake other tasks. Asynchronous clients retrieve results later, whereas synchronous clients receive results upon service completion. Asynchronous capability proves vital for loosely connected systems.

**Support for Remote Procedure Calls (RPCs)
--Web services empower clients to invoke procedures, functions, and methods on remote objects using an XML-based protocol. Remote procedures establish the input and output parameters that a web service must manage.

**Support for Document Exchange
--The generic representation of XML allows it to portray not only data but also intricate documents. These documents vary from a basic current address to an entire book or Request for Quotation (RFQ). Web services ease the transparent exchange of documents, simplifying business integration.

9. List and discuss the distinct roles in Web Services Architecture.

**Provider - The service provider is the one who creates a web service and offers it to client applications that want to use it.

**Requestor - The requestor is a simple client application that needs a connection to a web service. This client application can be based on .Net, Java, or any other programming language, and it seeks some kind of capability through a web service.

**Broker - The broker is the application that provides access to UDDI. UDDI, as mentioned in

**Publish - The provider informs the broker (service registry) about the existence of the web service by using the broker's publish interface, making the service available to clients.

**Find - The requestor asks the broker to find a published web service.

**Bind - Using the information obtained from the broker (service registry) about the web service, the requestor can bind or call the web service.

10. List and discuss the Web Services Components.

**SOAP
--SOAP is a protocol that uses XML for transferring information between computers.

--SOAP stands for Simple Object Access Protocol.
--It's a communication protocol used between applications.
--It can run on any operating system.
--It describes how to encode an HTTP header and XML file for communication between two computers.
--It doesn't depend on the platform and programming language.
--It allows server firewalls.

**WSDL
--WSDL is a language that uses XML to describe web services and how to access them.

--WSDL stands for Web Services Description Language.
--It's written in XML and used to describe web services and the process of accessing them.
--It's part of UDDI, helping businesses list themselves and their services on the Internet.
--It guides individuals and other businesses to access the service.


**UDDI
--UDDI is a standard that uses XML to describe, publish, and find web services.

--UDDI stands for Universal Description, Discovery, and Integration.
--It's an open framework and doesn't depend on the platform.
--It's one of the three main standards of web services along with SOAP and WSDL.
--It uses WSDL to describe interfaces to web services.
--It's a specification for a distributed registry of web services.

SOAP Web Services

SOAP is an XML-based protocol for application communication, even though it's slower and requires more resources. It still doesn't depend on the platform and programming language.
In the Java ecosystem, Java EE provides the JAX-WS API for creating SOAP-based web services.
With JAX-WS, you can define a SOAP service in both RPC or Document style. Both styles use a set of annotations applied to your classes, generating XML files.
