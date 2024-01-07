# DDD(Domain Driven Design)
As you might know well, __Microservices__ are being popular approach in recent years.
and it's mostly because it makes our software __scalable and flexible__.
The general idea behind Microservices is every program runs __a small and single task__ and __it must do it really well__ namely in Microservice we divide a huge Software into some small programs.

briefly, __DDD is a way of structuring and modeling our software__. So this means the domain has to be considered DDD(Domain to be more specific) before writing the software. 

![Domain Driven Design](./ddd-113854.png)

### Domain
Domain is a topic or a __problem space__ that the software tends to work on. So in DDD the engineering team has to meet up with the topic expert(__Domain Expert__) to __share their knowledge__ with engineers.

_explain the treading website at this time._

### Model
Model is an abstraction of the needed component to handel the domain.

### Core Domain
The basic Topics or Domains we name them "Core Domain".

### Sub Domain
Every subdomain is, therefore, a domain, and most domains are a subdomain. The only time I wouldn’t say a domain is also a subdomain is when our model does not contain a higher-level parent domain.  

### Ubiquitous language 
Basically talking in the same language between the Domain Expert and Engineer. So we need a unified language.

## Resources
1.[What actually is a subdomain in domain-driven design?](https://stackoverflow.com/questions/73077578/what-actually-is-a-subdomain-in-domain-driven-design)

2.[Domain, Subdomain, Bounded Context, Problem/Solution Space in DDD: Clearly Defined](https://medium.com/nick-tune-tech-strategy-blog/domains-subdomain-problem-solution-space-in-ddd-clearly-defined-e0b49c7b586c)