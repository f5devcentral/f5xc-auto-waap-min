# f5xc-auto-waap-min

Minimalistic demo to show:
    - automated application enrolling with a default policy
    - automated update to existing web applications

## Components

- Origin Pool
- App Firewall
- HTTP Load Balancer

### Origin Pool 
This targets an existing URL.

### App Firewall
WAAP policy where config can be manipulated.

### HTTP Load Balancer
LB exposed to the internet. Object where WAAP is applied and bot policy is configured.

## Deploy
GitOps using Terraform Cloud. Commit to ``main`` and changes will be deployed to the F5xc tenant.
