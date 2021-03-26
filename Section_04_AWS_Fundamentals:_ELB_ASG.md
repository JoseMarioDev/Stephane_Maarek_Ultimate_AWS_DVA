### 33. High Availability and Scalability

- scalability: vertical(up/down) and horizontal(in/out)
- HA: running your app in at least 2 data centers/AZs
  - goal is to survive data loss
  - can be passive/active

#

### 34. Elastic Load Balancer(ELB) Overview

- nothing new to add

#

### 35. About the Gateway Load Balancer

- new service, shouldnt appear on exam for a while
- check for updates

#

### 36. Classic Load Balancer(CLB) w/Hands On

- does not use target groups
- no longer recommended by aws

#

### 37. Application Load Balancer(ALB) w/Hands On

- can setup target groups and rules to route traffic by /path

#

### 38. Network Load Balancer(NLB) w/Hands On

- can assign a elastic ip, only lb that will allow that

#

### 39. Elastic Load Balancer - Stickiness

- not avail on nlb

#

### 40. Elastic Load Balancer - Cross Zone Load Balancing

- not charged for cross zone load balancing for clb and alb
- there is a charge for nlb cross zone load balancing

#

### 41. Elastic Load Balancer - SSL Certificates

- ELB using ssl between client and elb, using http inside between elb and ec2 inst
- can use Amazon Certificate Manager to setup a ssl cert or bring your own
- sni
  - load multiple ssl certs onto 1 server
  - is a newer protocol requires client to specify the hostname of target server when initiating handshake
  - only works on alb and nlb and cloudfront
  - does not work with clb

#

### 42. Elastic Load Balancer - Connection Draining

- time it takes to complete inflight requests while an instance is unhealthy or deregistering

#

### 43. Auto Scaling Groups(ASG) Overview

- nothing to add

#

### 44. Auto Scaling Groups Hands On

- nothing to add

#

### 45. Auto Scaling Groups - Scaling Policies

- target tracking scaling
  - ex around 40%
- simple/step scaling
- scheduled action - time based; ex 3pm on friday

- cooldown 300 sec default

#

### Quiz 3: Fundamentals 2 Quiz

-

#
