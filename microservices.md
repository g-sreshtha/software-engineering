# Microservices - What are they?

Microservices are an organisational approach to software development where an application is split into smaller independent services based on their specific business functionalities. They then can communicate over well-defined API's.
It is known that these services must be self contained and independent to eachother in an application which is called ***loose coupling***. This means that services can be built and deployed separately for example for an ecommerce website, if a customer chooses to pay for a product, then the APi needs to only build and deploy the payment service separately and none of the other services will be affected given that the different functionalities will be split up into correct microservices.

This is different to the traditional Monolithic Architecture where all processes are ***tightly coupled*** and run as a single service so all components of the application are built and deployed at the same time which can affect the processing time as well as increasing the impact of single process failure.


## the downsides of microservices:
- new challenges are introduced
- configuring the communication between services adds complexity just by the fact that it is a distributed system.

-> however there are tools being developed to combat this i.e kubernetes
- 
