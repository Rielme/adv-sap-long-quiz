## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
    - SOA or Service Oriented Architecture is an enterprise level approach when it comes to developing an application in which 
	it utilizes the sustainable software components or services such as checking customer’s debit and signing into the website.

2. List and discuss the characteristics of SOA.
    - Standardized Service Contracts – it is a service that has a well-defined set of guidelines to ensure that it follows the similar 
	guidelines to maintain their service contracts to express their purpose, and capabilities.

	- Loose Coupling – it reduces the dependency on each service, and every modification on one component should not greatly affect the 
	other services.

	- Abstraction – it hides unnecessary information of services, metadata, or data in the external view so that clients can only focus 
	on the main functionality of the service. It also plays a major part in the positioning and service composition designs.

	- Service Reusability – it is developing a service that can be reused in various business or organizations process.

	- Autonomy – services that can operate their logic independently despite external influences.

	- Statelessness – A service that does not store data and utilizes minimal usage of resources to achieve the scalability and 
	improvement of reusable services.

	- Discoverability – Service contract provides the necessary metadata for clients to easily discover the purpose and capabilities 
	of the service. 

	- Composability – It breaks down big problems into smaller pieces of an existing services that enables them work together easily by 
	promoting the reusability and adaptability.

	Interoperability – it is most considered in this generation that it is typically rejected as a principle. It sets a standard which 
	allows users to gain access to the service that it provides.

3. Define Microservices.
    - Microservices is an architectural style approach that is used to develop an independent software and is similar to SOA. 
	It is called microservice because it is made up of independent services that enables them to provide more scalable, resilient, and sustainable application. 

4. List and discuss the benefits of using Microservices.
    - Independently deployable – it plays significant role in the characteristics of microservices since it has the ability 
	deploy individual microservices independently using network, enhancing the overall productivity of the organization.

	- Right tool for the job - It helps the organization to choose the appropriate tools, application, and framework that is suitable 
	for their tasks. Implementing multiple, smaller services allows the organization to boost their productivity and is more cost efficient.

	- Precise scaling – it has the ability individually deploy services individually and can also be scaled individually. 
	It enhances the productivity, and it will be cost efficient because it will only scale the required components precisely rather than the entire application.

5. List and discuss the similarities and differences of SOA and Microservices.
    *Similarities:
	Reuse – In SOA, it develops a new service that can be recycled in different system which reduces the agility and resilience of an application. 
	Microservice usually prefer to copy and duplicate the data by recycling the codes.

	Synchronous Calls – Services in SOA uses predominantly synchronous protocols like APIs to reuse the available services in the enterprise. 
	Microservices implements real-time dependencies which can affect the performance and cause them a loss of resilience and latency.

	Data Duplication – They will both occur if there is a similar data that is stored in various services within the system. They are both performs a specific function.
	*Difference:
	Communication – Microservices is independently developed and has their own communication protocol. SOA mainly focuses on sharing common communication 
	mechanism in their service which is known as the Enterprise Service Bus.

	Interoperability – Microservice utilizes lightweight messaging protocols, While SOA has a standard set which allows the user to gain access to the service.

	Service Granularity – services in SOA have a small range but can provide a specialize services in enterprise-wide services. While Microservice is 
	mainly designed to accomplish a single task but is made up of highly specialized services.

	Speed – SOA has the ability to simplify in development and troubleshooting, but the operation of SOA will takes more time than microservice since 
	both SOA and Microservice shares a common architecture.

6. Define Web Services.
    - Web Services is software that uses the internet network to communicate and exchange data between the two systems.

7. List and discuss the benefits of using Web Services.
    a. Exposing the Existing Function on the Network – It gives other applications access to utilize the existing code functionality of your program if it is revealed on the network.

	b. Interoperability – it is a platform independent which allows different software to communicate and share information and services with each other in a secured connection.

	c. Standardized Protocol – Web services utilize the industry standard protocol that is used in communication, providing the various companies an advantage such as quality growth, 
	   a variety of options, and cost efficiencies as an outcome of increased competition.

	d. Low-Cost Communication – Web services prefer to use SOAP over HTTP protocol since this solution is much more efficient and you can use your existing cost-efficient network 
	   connection to implement web services.

8. List and discuss the characteristics of Web Services.
    a. XML-based – Since XML, or Extensible Markup Language, is a format utilized to encode documents that both humans and machines can read and understand, it does not require 
	   networking, operating system, or platform binding in Web services.

	b. Loosely Coupled – a strong bond of coupled system indicates that the logic between the client and server are linked together, specifying that other interfaces should be updated
	   as well if one interface is modified. The user interface of web services should be able to be modified over time without affecting the ability of the consumers to interact with
	   the service.

	c. Coarse-Grained – web services like Java allow their services to be available through individual methods. In corporate level, its task is to locate an operation which could 
	   provide a capability that could be beneficial, since a coarse-grained service has a broad scope of functionality. 

	d. Ability to be Synchronous or Asynchronous – the client of web services should have the ability to operate in synchronous and asynchronous. The client shall stand by as the
	   service is accomplishing its operation before proceeding in synchronous invocations, and they can receive their result after the service is done. Then in asynchronous, the
	   client is allowed to invoke a task and then proceed with different tasks, and they can get their results at a later point in time. 

	e. Supports Remote Procedure Calls (RPCs) – Web services should support the input and output parameters that are revealed by the Remote procedures. Clients can utilize an XML-based 
	   protocol to cite procedures, functions, and methods on remote objects.

	f. Support Document Exchange – XML’s beneficial feature is its simple approach to represents data and complex documents. This enables the web services to share and exchange data which
	   helps the business incorporation.

9. List and discuss the distinct roles in Web Services Architecture.
    a. Provider – it develops web services which various consumers can utilize to their application.

	b. Requestor – is a service provider which can help the client to contact a web service if they need it.

	c. Broker – is a service provider that provides access to UDDI for the client to locate web services.

	d. Publish – provider notifies the broker or the service registry using the broker’s publish interface that the web service already existing for the client to gain access to the
	   service.

	e. Find – the broker is given the task of locating a published web service that the requestor asks by the service provider.

	f. Bind – It is a collection of information that is gained from the service registry which the requestor is able to cite the web service that is needed.

10. List and discuss the Web Services Components.
    a. SOAP – Simple Object Access Protocol is a message protocol that communicates between applications and can operate on various operating systems. It is a platform and language
	   independent, and it gives permission to server firewalls.

	b. WSDL – Web Services Description Language is an XML-based language that is written in XML. It is useful when it comes to web services since it depicts the web services and the
	   method of gaining access to them. It also guides the individual by navigating them and other corporates to have access to the service.

	c. UDDI – Universal Description, Discovery, and Integration is a platform-independent open framework that utilizes the WSDL to convey the interface to web services. It is also
	   commonly used for a distributed web service registry.
