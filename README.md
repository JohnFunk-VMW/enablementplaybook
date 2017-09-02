# Enablement Playbook
## Customer Success Story Videos
These videos are a great place to start your journey to learning Pivotal Cloud Foundry becasue they help you understand what real-life customers are doing with PCF.

#### Ford Motor Company’s Transition from Auto-Motive to Auto-Mobility
Great story of tranformation.  A must see video for anyone working with Ford  
https://www.youtube.com/watch?v=ryQ7s8q8YWw&t=1232s

#### Comcast Cloud Foundry Journey
Great discussion of what Comcast has achieved using Pivotl Cloud Foundry  
https://www.youtube.com/watch?v=pfqSsjwCOqA&list=PLAdzTan_eSPRoRJGArqipaN_r5K74o31H&index=9

#### What Does It Take to Run Cloud Foundry at Enterprise Scale? - Verizon
This is a great customer story from one of our larger customers.  
https://www.youtube.com/watch?v=xhpFVFq-J8M&list=PLAdzTan_eSPRoRJGArqipaN_r5K74o31H&index=16

#### Zero to 12 million - T-Mobile
This is a good talk that describes what T-Mobile provides for their application development teams with PCF.  
https://www.youtube.com/watch?v=xgNRM7Fri_s

#### Extreme Ops: Platform Operations at The Home Depot
A good discussion of devops automation with PCF at a major retailer
https://www.youtube.com/watch?v=GvtRiFSb5us&list=PLAdzTan_eSPRoRJGArqipaN_r5K74o31H&index=12

#### Cloud Native and Automation at Garmin
A good story of ops and app dev lessons learned from a mature customer  
https://www.youtube.com/watch?v=zDL44Cp78QE 

### For the techies
#### No Rocket Scientist Required - Developing +14,000 Message p/second IOT Systems
A great discussion of scaling up a 14,000 message per second system IoT system  
https://www.youtube.com/watch?v=dzdytNrMafM&list=PLAdzTan_eSPRoRJGArqipaN_r5K74o31H&index=17

### But wait there's more....
For a compleate list of our customer stories from CF Summit 2017 visit  
https://www.youtube.com/playlist?list=PLAdzTan_eSPRoRJGArqipaN_r5K74o31H

## Technical Material to get Started
For your first hands on tast of working with Pivotal Cloud Foundry try our 15 minute online tutorial at:
https://pivotal.io/platform/pcf-tutorials/getting-started-with-pivotal-cloud-foundry/introduction

Once you are ready for more sign-up for the Pivotal Partner Portal at: http://partners.pivotal.io
It has lots of great material including:
- Free Developer Self Study Classes on PCF and Spring Boot
- Technical material like reference architectures etc.
- an FAQ that's great for helping with proposals
- Sales Plays and Collateral such as .ppt slides

Here is a short video that shows you how to setup your free account on the Pivotal Partner Portal.  
https://youtu.be/xQdGs2BYZDY


## Environments you can use for hands-on Development work with Pivotal Cloud Foundry
Cognizant team members have 4 main alternatives for environments to develop applicaitons on Pivotal Cloud Foundry.  The table below sumarized those options.

| |PCF Dev installed on your laptop| Pivotal Web Services | Cognizant Sandbox | Deploy your own PCF to AWS/GCP/Azure|
| --- | --- | --- |--- | --- |
| Start today | √ | √ | | |
| Cost | Zero | 1st Month Free / ~$10-$20 per month per AI| Zero | $100 - $150 per month in cloud charges |
| Operator / Administrator experience | | | | √ |

Here is a more complete discussion of the varios options
### PCF Dev
PCF Dev provides a PCF developer experience on a developer’s local machine.  It is free to download from https://pivotal.io/pcf-dev and you can start pushing apps right away using your local machine.
This is one of the fastest ways for developers to get started.
#### Advantages:
*	Start today
*	No cost solution
*	Supports common services including: Spring Cloud Services, MySQL, Rabbit, Redis
#### Disadvantages:
*	Limited to local machine
*	No Administrator / Operator experience available.  This is really a stripped-down, single VM Cloud Foundry for developers.


###  Pivotal Web Services
Pivotal Web Services is Pivotal’s hosted Cloud Foundry environment where pay for the time they use.  It is a great way to get started becaue you start with $87 of credit, which is roughly 60 days of service.  After the free credit is consumed a small applicaton instances cost ~$10-$20 per month.

#### Advantages:
*	Start today
*	Low cost solution
*	Centralized billing - one org with multiple spaces results in centralized billing
*	Lots of services
#### Disadvantages:
*	Does not currently support Spring Cloud Services or Spring Cloud Data Flow (planned for Q42016)
*	Not the same services that a customer’s PCF may have.
*	No Administrator / Operator experience - it’s a shared service that doesn’t have admin capabilities.

### Cognizant Sanbox Environment
Cognizant is in the process of setting up a sandbox environment for developers to use as a sandbox.  The system is expected to be available in October 2017.  Please watch this page for updates.

### Deploy your own PCF to AWS/GCP/Azure
It is possible to deploy your own full installaiton of PCF into one of the Cloud Providers such a AWS, GCP, or Azure for non-commercial, non-revenue generating activities.  Your project team will be responsible for the cost of the cloud infrastructure which typically costs about $100 - $150 per day.  If you are interested in this option please contact Lee Loughnane lee.loughnane@cognizant.com for more details.
#### Advantages:

*	Supports everything customers use: Spring Cloud Services, MySQL, Rabbit, Redis 
*	Provides Administrator / Operation experience
*	Flexible configuration - can scale up / scale down based on your needs.
*	No Permanent costs like dedicated hardware
#### Disadvantages:
*	Estimated cost:  $100 - $150 per day in Cloud Provider charges.
*  	Setup requires full installation of PCF (average first time install takes a experienced Linux admin ~3 days)
