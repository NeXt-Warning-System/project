# NeXt Warning System (XWS) Week 9 Update
**Week beginning: 1st February 2021** 

Prepared by: XWS Alpha Team

## What we’ve been up to this week

* Continuing with further rounds of research with internal users – Prototype 2
* Capture Main Findings from the research sessions
* Analyse the outputs from the internal user research sessions and agree main findings
* Elicit user needs from the internal user research sessions
* Create Show N Tell Presentation; User Research
* Continuing to recruit additional external user participants
* Change design focus to external user registration, starting with design research for finding a location
* Focus on new developer onboarding inc. docker environments
* Work on the CI and deployment pipelines
* Implementation of RabbitMQ for event hub / removing the old PG based queues (SKID LOCKED) and topics (LISTEN and NOTIFY)
* Initial work on the producers/enqueuers and consumers/dequeuers for the initial issuing of an alert
* Work on a JS CAPXML library
* Investigation into AWS Pinpoint for the Voice channel to see if it will support our needs

## What we’re planning for next week

* Show N Tell Presentation; sharing findings with the project team
* Correspond to FWS respondents 
* Correspond with Floodline respondents
* Continuing to recruit additional external user participants
* Event Mapping Sessions
* Looking into producing a TWITTER survey
* Design for external users finding a location for their flood warnings
* Investigate information provided to help users understand flood warning terminology
* Preparation for show and tell around RabbitMQ and eventing
* More developer onboarding (Paul Shaw)
* Technical discussions focussed on the contact and area subsystems
* Further microservice (subsystem) decoupling using RabbitMQ

## Blockers, issues or questions

* Quotas for cloud-based Voice channel operators (AWS Pinpont / Twilio) are throttled at 1 call/sec/line ~ 3600 calls/hr/line. These quotas are not at the levels we require. They cannot be increased but other alternatives are being investigated (e.g. increasing the number of lines)

## Biggest risks

* Due to the impact of lockdown 3, homeschooling and caring responsibilities will affect people's capacity to deliver and for people (Citizens and Internal Staff) to have input into the design and delivery of this service
