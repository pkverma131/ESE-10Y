# 8 Principles of Service-Oriented Architecture: Is SOA Dead? 


If you bring service-oriented architecture (SOA) up in a conversation, there’s a good chance someone will tell you that SOA was a failed idea. But you should challenge that line of thinking. If you revisit the actual principles of SOA, you will see they are as relevant today as they were when they were first constructed. We’ll explore each of the principles and their relevance to the drive for the digital transformation you face today. 

**Service-oriented architecture (SOA)**

SOA is often coupled with SOAP. SOAP is a technical implementation of the SOA principles, but it is not the same as service-oriented architecture. SOA is an architectural style used to describe a set of principles on how organizations can transform their enterprise in an effective and agile manner. SOAP is just one approach to implementing SOA.

**What is a service in the context of SOA?**

A service represents a business capability as a repeatable activity with a specified outcome. An organization might have a product service that, when called, can return a list of product attributes for a given set of products. A developer could use this service to list product details on a web page for an e-commerce site. Think of services as nouns (orders, tickets, products) that you apply verbs to (create, validate, update, delete, list).

A service should be self-contained. The SOA principles refer to this as being autonomous. A product service should be independent of the other services. While independent, another SOA principle, composability, promotes the concept of combining services to produce business value. Combine customer service and product service to create an order service.

A service is exposed for consumption as technology agnostic. One of the main benefits of services is the abstraction of the underlying technology. One team can build their services in MuleSoft while the other utilizes .NET or NodeJS. The backend development model does not impact the team’s ability to use the other team’s service. The ability to share services is because SOA promotes the concept of a standardized service contract. In the early days of SOA, this standard contract was SOAP and WSDL. 

While effective, it was developer-heavy. In 2000, Roy Fielding introduced REST web services. REST allowed the ability to call web services in a lightweight resource-centric model. Emerging patterns like gRPC and GraphQL continue to offer additional service contract patterns.  Google map API is an example that supplies a series of logistical capabilities. A weather API offers detailed weather capabilities in an easy-to-consume manner.

Now we’ll go through the eight principles of SOA and see how relevant they are to today’s digital needs.

**8 principles of a service-oriented architecture**

SOA is supported by a set of eight architectural patterns that define it: 

1. Standardized service contract
2. Loose coupling
3. Abstraction
4. Reusability
5. Autonomy
6. Statelessness
7. Discoverability
8. Composability 

Let’s explore each in depth. 

**1. Standardized service contract**

SOA was initially implemented using the SOAP protocol.  SOAP requires the use of a WSDL to utilize the service. REST simplifies this model in an easy-to-use implementation model. REST uses a request-response model to transmit data with a set of resources and verbs. 

A RAML or Open API specification defines these resources and other features. The specification helps the consumer use the service. It is essential to allow service consumers access to these specifications. Discovery portals like MuleSoft Exchange Anypoint Platform or MuleSoft API Community Manager allow a comprehensive mechanism to document and share the service consumption requirements and capabilities.

**2. Loose coupling**

A primary benefit of SOA is the agility brought about by loose-coupling through services for the clients that interact with providers that support them. Instead of connecting a client app directly to a ticketing system, you put a service in between that disconnects the two systems breaking the dependency. 

An Enterprise can now treat each layer independently from the other. The value-add is that the backend systems can be replaced with little or no impact on the front end, providing minimal business disruption. 

**3. Abstraction**

A service hides its underlying technology from the consumer. Abstraction allows the Enterprise to define technology in the context of a business process.  Abstraction breaks dependencies and introduces agility.  In the MuleSoft API-Led Connectivity model, a system API might abstract away an SAP instance. In this way, clients do not need to concern themselves with the language of SAP, IDocs and BAPI. 

Instead, the Enterprise works in a canonical business model that defines its flow in the process layer of the MuleSoft approach. This approach reduces the number of subject matter experts needed for these tools freeing up resources. You can now use that found capacity to focus on your business process and customer experience needs. 

**4. Reusability**

I have promoted my own architectural law for years now. Park’s law states that Always is cheap and sometimes is expensive. How many ways does your organization have for doing the same thing? If you drive the culture of the Enterprise to look for reuse before creating new services, you can reduce development time and the associated support costs. 

Reusability creates a flywheel effect for innovation. Push teams to look for existing services before creating new ones. A critical component of driving reusability adoption is educating the consumers about what exists to date. The MuleSoft Exchange and API Community Manager tools address this specific need in a state-of-the-art fashion.

**5. Autonomy**

Services must stand on their own and abstract away any dependencies. Consumers need the defined service contract engagement methodologies to interact with the service. Nothing to install, nothing to register other than access control. In a REST model, a consumer can read the RAML or Open API specification and know what is required to interact with the service. 

Users can then consume this service in a secure defined way in any compatible front end with no other needed dependencies. Utilizing the MuleSoft Exchange portal, users can register to consume a service. The portal helps to track the use of a service. While services should be able to stand alone, you need to watch them for performance and usability. What’s more, MuleSoft’s AnyPoint platform offers this end-to-end visibility.

**6. Statelessness**

A service deals with moments in time. It has no memory. If a client asks for data the service responds but does not keep track or store any data. If the context is needed for subsequent calls the onus is on the client to manage that context. You can cache data but that is a capability that the service can utilize as an option but will not depend on it. It is not part of the service. MuleSoft offers capabilities to manage the state in support of published services.

**7. Discoverability**

To support reuse, a service must be able to be found by a consumer. The system must educate the consumer on the proper mechanism to interact with the service and offer as much detail as possible to accelerate its use. MuleSoft Exchange and the MuleSoft API Community Manager allow for such discoverability. A discovery portal promotes reuse through clear and concise search and documentation. They accelerate adoption through sample payloads in the form of easy-to-consume mocking services.

**8. Composability**

The building blocks of the Enterprise are the composable services it offers to its user community. And as we’ve heard, the future of business is composable.  Enable your organization to combine packaged business capabilities to define business processes. Service orchestration and choreography provide solid support for composing services and achieving business goals. Allow consumers to discover business capabilities as services that can be stitched together to build more complex business processes. MuleSoft is leading the tech space in the world of composability.

Does SOA address automation? 
One area that SOA does not address is automation. Business demand will continue to outpace IT capacity. Automation capabilities can help reduce this contention by enabling the business with self-service technology. Augment packaged business capabilities with automation via low code/no-code and RPA tool sets. 
