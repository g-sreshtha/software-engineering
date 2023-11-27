# Microservices - What are they?

Microservices are an organisational approach to software development where an application is split into smaller independent services based on their specific business functionalities. They then can communicate over well-defined API's.
It is known that these services must be self contained and independent to eachother in an application which is called ***loose coupling***. This means that services can be built and deployed separately for example for an ecommerce website, if a customer chooses to pay for a product, then the APi needs to only build and deploy the payment service separately and none of the other services will be affected given that the different functionalities will be split up into correct microservices.

This is different to the traditional Monolithic Architecture where all processes are ***tightly coupled*** and run as a single service so all components of the application are built and deployed at the same time which can affect the processing time as well as increasing the impact of single process failure.

![image](https://github.com/g-sreshtha/software-engineering/assets/146075375/15d9fd13-0613-4fc3-a84e-5f8ac7f4afbf)

## Advantages and Disadvantages of Microservices

### Advantages:
**Scalability**: Microservices allow for independent scaling of individual services based on the specific needs of each service. This enables better resource utilization and cost efficiency.

**Flexibility and Agility**: Microservices enable faster development cycles as teams can work on and deploy individual services independently. This flexibility is crucial in dynamic and rapidly changing business environments.

**Technology Diversity**: Different services within a microservices architecture can be developed using different technologies, frameworks, and programming languages. This allows teams to choose the best tools for the specific requirements of each service.

**Fault Isolation**: If one microservice fails, it does not necessarily affect the entire system. Isolating failures to specific services makes it easier to identify and fix issues without impacting the entire application.

### Disadvantages:
**Complexity**: Managing a system with many microservices introduces complexity in terms of service discovery, communication, and data consistency. The distributed nature of microservices can make development and debugging more challenging.
-> however there are tools being developed to combat this

Data Management Challenges: Handling data consistency and integrity across multiple microservices can be complex. Maintaining a consistent view of data across services may require additional effort and coordination.

Initial Development Costs: Adopting a microservices architecture may require significant upfront investment in terms of infrastructure, tooling, and training. The benefits often become more apparent in the long term.

Integration Testing Challenges: Testing the interactions between different microservices can be challenging. It requires thorough integration testing to ensure that all services work correctly together.

Security Concerns: The distributed nature of microservices introduces new security challenges, such as securing communication between services, managing access control, and ensuring data privacy.
## the downsides of microservices:
- new challenges are introduced
- configuring the communication between services adds complexity just by the fact that it is a distributed system.

-> however there are tools being developed to combat this i.e kubernetes
- 
