# pa_egress_ip_addresses

## Introduction
This python script allows you extract the public IP addresses assigned to the Palo Alto Prisma Access services, and display those in an more explained and readable format
Overview about Prisma Access Egress Public IP Addresses.

## Overview about Prisma Access Egress Public IP Addresses.
If you are manually adding IP addresses of your Prisma Access infrastructure to an allow list in your network or to egress traffic to the internet and SaaS apps, or if you need to enforce IP-based restrictions to 
limit inbound access to enterprise applications, you should understand what these addresses do and why you need to allow them, as well as the tasks you perform to retrieve them.

Prisma Access does not provision these IP addresses until after you complete your Prisma Access configuration and this configuration is commited. After your deployment is complete, can you retrieve these IP addresses using an API. 
The API uses an API key that you obtain from the Prisma Access management UI, either Panorama or Strata Cloud Manager based. 
