# DDD(Domain Driven Design)
As you might know well, __Microservices__ are being popular approach in recent years.
and it's mostly because it makes our software __scalable and flexible__.
The general idea behind Microservices is every program runs __a small and single task__ and __it must do it really well__ namely in Microservice we divide a huge Software into some small programs.

briefly, __DDD is a way of structuring and modeling our software__. So this means the domain has to be considered DDD(Domain to be more specific) before writing the software. 

![Domain Driven Design](./ddd-113854.png)


### Domain
Domain is a topic that the software tends to work on. So in DDD the engineering team has to meet up with the topic expert(__Domain Expert__) to __share their knowledge__ with engineers.

_explain the treading website at this time._

As you can see DDD has 2 main parts which are __Tactical Design__ and __Strategic Design__.
> Strategic Design contains everything related to the business like treading techniques. 

> Tactical Design contains everything related to the implementing the business.

In essence, Strategic Design is about determining what we need to build. Tactical Design is about how we build it

### Domain Model 
Model is an abstraction of the needed components to handel the domain. And it's mostly made by Domain Experts and Technical Team.


### Ubiquitous language 
Basically talking in the same language between the Domain Expert and Technical Team. So we need a unified language.

### Prespective
Both Domain Expert and Technical Team should have the same idea about implementation the parts of software.

### Sub Domain
Every subdomain( or a __problem space__ ) is, therefore, a domain, and most domains are a subdomain. The only time I wouldn’t say a domain is also a subdomain is when our model does not contain a higher-level parent domain.  
![Domain Mode](./blg_line_domain_driven_design_1.png)
> Identifying the problem areas in a domain is called __Problem Space Analysis__. This requires close collaboration with __Domain Experts__, the people who know the business best.

Generally speaking there are 3 kinds of subdomains:
 - Core Domain
 - Supporting Domain
 - Generic Domain
 The Core Domain
 
### The Core Domain
The most investment should be put into the subdomains where the business creates a __competitive advantage__, the Core Domains. Without it the business would fail.

A Bounded Context should be created for the Inventory subdomain and the best possible team should be built out to work on this. 

### Supporting subdomain
subdomain, which is less valuable for business than Core domain. Without it business may be can even__ survive for some time__. But it still is quite important (supports core domain), it also is specific for the domain and has to be developed. In this case, for some reason, we __can't buy an existing software__ or component to solve the problem.

 ### Generic subdomain 
 subdomain which is less valuable for business than Core domain. It also is generic enough to allow buying it off the shelf __(unlike supporting domain)__.
 ![](./1_eXtFuCxdStajdCioEEsgkw.webp)

 ### Bounded Context 
 bounded context defines the clear boundaries within which a particular domain model operates, ensuring that each service only deals with its specific domain. This helps to maintain separation of concerns and enables independent development and
## Resources
1.[What actually is a subdomain in domain-driven design?](https://stackoverflow.com/questions/73077578/what-actually-is-a-subdomain-in-domain-driven-design)

2.[Domain, Subdomain, Bounded Context, Problem/Solution Space in DDD: Clearly Defined](https://medium.com/nick-tune-tech-strategy-blog/domains-subdomain-problem-solution-space-in-ddd-clearly-defined-e0b49c7b586c)

3.[Domain Driven Design in 10 minutes](https://www.thoughtworks.com/en-au/insights/blog/evolutionary-architecture/domain-driven-design-in-10-minutes-part-one)

4.[DDD, identifying the core domain](https://stackoverflow.com/questions/25274226/ddd-identifying-the-core-domain)

5.[Core Domain Patterns](https://medium.com/nick-tune-tech-strategy-blog/core-domain-patterns-941f89446af5)

6.[All  Domain-Driven Design (DDD) How do you apply DDD to different types of domains?](https://www.linkedin.com/advice/0/how-do-you-apply-ddd-different-types-domains#ddd-benefits)