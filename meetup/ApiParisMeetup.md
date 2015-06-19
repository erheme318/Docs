
## Our journey implementing, testing & maintaining 14 API clients (talk1)
by @sylvainutard

df: SAS, A hosted search API (Rest API + JSON)

### Infrastructure

 - Fault-tolerant, high available
 - Master/master replication
 - Advanced queries routing (closest data center)
 - GEO IP - based on location respond nearest data center
 - 99.99% SLA
  - Query fails are highly penable

API clients:
 - Community or Internal was question and decided to keep it interal.
 - Backward compatibility is hard for community. No one is going to fix a bug if you need to fix it ASAP.

### Implementation

- Coding style, naming convention (joke there)
- Validate your dependencies


### Documentation

They uses generator and may externalize it to readme.oi.

### Tests

 - Multiple environments & OS
 - Code coverage
 - Code climate

### Blog

Spread the word: attract the gurus (skilled developers)

### Quality:
 - Same naming conventions
   Customer who changes their client has no worry about the details of API and it's naming convention.
 - Every client provide same quality


### Deployment

Every feature aer deployed for all clients on same time. But client don't really have to have same versioning.


### Culture

Every engineer in Algolia answer the support including CTO.



## MDN Mozilla  (talk2)
by jeremi

MDN developer wiki exists for 10 years.

Browser compatibility for feature doesn't exist any other site or specification.


