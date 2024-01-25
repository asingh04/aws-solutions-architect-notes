

In AWS VPC, the max number of IPs supported dedpends on the number of host bits in the IP address.

Make CIDR range value is
x.x.x.x/28 to x.x.x.x/16
16 IPs.    to          65534 IPs



## Routing tables

Examples:
### Default Routing Table
192.168.0.0/16  ------------ Local


### Public Routing Table
192.168.0.0/16  ------------ Local
0.0.0.0/0 ------------- IGW (Internet Gateway)

### Private / protected Routing Table
192.168.0.0/16  ------------ Local
0.0.0.0/0 ------------- NAT Gateway 


## Reserved IPs in AWS VPCs
x.x.0.0 ------> reserved for the network identification

x.x.1.1 ------> the router // by aws
x.x.1.2 ----- > DNS server // by aws
x.x.1.3 ----- > currently not in use but still reserved // by aws


x.x.255.255 ----> reserved for broadcast



# IMP to know the default behaviour of the NACL and SGs
# IMP: Exam ask about NACL and SG, especially about the DENY rule in NACL but not in SG


## In NACL, make the more specific rule first, then define the generic / wildcard rules later



==Difference between Direct COnnect Router and Direct Connect Gateway==

DCR is regional resource

DCG is Global resource

==Transit Gateway is a regional resource==
==> So TGW can attach with another TGW
