## AWS location hierarchy 
Region > AZ > Data Centres

## Criteria for Region selection
1. compliance/governance regulations
2. Service Availability
3. Proximity - client locations
4. Cost


## Edge Locations - services
==tackles latency by bringing the caching near to customer==
1. CF
2. Lambda@edge
3. Route 53
4. WAF - for protection against DDoS attacks


## Local Zones
- Deployed to tackle critical/sensitive latency issues for services deployed on a region, but customer still far away.
- kinda like a ad hoc DataCenter or a AZ near a customer
- ==tackles latency  by bringing compute power near to customer==
- 