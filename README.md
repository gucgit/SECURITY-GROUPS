# SECURITY-GROUPS
A security group controls the traffic that is allowed to reach and leave the resources that it is associated with. For example, after you associate a security group with an EC2 instance, it controls the inbound and outbound traffic for the instance.
Types of secuirty groups 
Type	Protocol	Source
HTTP, HTTPS, SSH, RDP	TCP	SentinelDefaultSecurityGroupPublic (does not restrict outbound traffic)
MALZ bastions:
SSH	TCP	SharedServices VPC CIDR and DMZ VPC CIDR, plus Customer-provided on-prem CIDRs
