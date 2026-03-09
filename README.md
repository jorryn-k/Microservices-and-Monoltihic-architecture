## Microservices
Microservices are a software design model that structures an application as a collection of small independent services. Each services focuses on one specific business capability and can be developed, deployed and maintained separately.
### How Netflix uses Microservices
Separate services handle specific tasks like User recommendtations, Billing, Search and others. In order to prevent a single point of failure, each service has its own database. This ensures that if User recommendations fails, the user can still search and watch movies.
#### Other companies that use Microservices
1. Spotify
2. Uber
3. WhatsApp
4. Instagram
##### Why they use Microservices
1. It allows companies split into small different teams each working independently from the others. Meaning, if a single line of code is changed under one team, the other teams do not have to re-test and re-deploy their segements.
2. If there is a bug in one module, it does not affect the rest of the code.
3. There is a lower rsik of failure, in that, if a new service is deployed and it is not like by the customers, it can easily be deleted.
## Monolithic Architecture
Monolithic Architecture/ Macroservices also known as Monolith is a software design model where an application is built as a single, unified unit where all components are deployed together as a single package.
#### Apps that changed back to Monolith and why 
1. Amazon Prime Video (The Video Quality Analysis tool)

    It was becoming expensive to orchestrate many pings to check video quality.
3. Segment

    Every time they added a feature, they had to update many other different repositories which was not ideal for them.
5. Istio

   Managing seven different services for one tool was too complex for users.

