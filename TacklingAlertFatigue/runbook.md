# Runbook Template

##Table of Contents
A Table of Contents with links to main sections

## General
A quick description of the services.  1 to 2 sentences max.  Why does this service matter?  What is it's core functionality?  What Features does it provide users?

## Dashboards
Links to the Dashboards for this service

## Alerts
Links to the Alerts for this service

For Every Alert there should be a corresponding section in alphabetical order
### Alert Title
Alert Description:  Why do we have this alert?  What does it mean?  What is typically the cause of this alert?

#### Impact to Customers:
How does this situation impact our customers?  If the customers are not being impacted, this is a good indicator that the alert can be deleted.

#### Remediation Steps:
Checklist manifesto style steps for how to resolve this alert.  A person who has never worked on our stack should be able to follow these steps and remediate the incident.  If it cannot be remediated, include escalation steps here.
 1. Do this
 2. Check this graph
 3. Do this thing 
 4. Do this other thing
 5. Verify service has recovered
 
## Contact Info
Team contact info.  Potentially contact info for who to escalate to.  What services do we have dependencies on?  How do we escalate to them?  Define this information here.  

## Latest Deployments
We do Production Change Management Deployments via Jira, we included a link of all the latest changes here.  Recent commits, CI log etc... is incredibly helpful in understanding what code is deployed to the system, what recent changes were made.

## Clusters
Information on where this service is deployed, and how to access those machines.

## Deployment
How do you deploy this services.  Favor Checklist manifesto style lists here as well. 
 1. Do this thing
 2. Do this other thing
 3. Finally do this thing 
 
### Canary Deploy
Instructions on how to do a Canary Deployment
 1. Do this canary thing
 2. another canary task
 
### Rollback Deploy
Instructions on how to Rollback a Deploy. 
 1. Get the rollback build here
 2. Do this thing
 3. Do this other thing.  



