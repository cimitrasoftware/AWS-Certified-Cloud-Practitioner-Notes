**AWS Shared Responsibility**
- This is the idea that AWS and customers have responsibilities for systems in the AWS Cloud 
- Responsibilities are based on the management level of the offering from AWS
- - Unmanaged
  - Partially Managed
  - Fully Managed

**SDK** *Amazon SDK*
This is a separate installation from the Amazon CLI. The SDK is typically installed as a client specific to the platform and the IDE that will be used


**SQS** *Amazon SQS*

Simple Que Service
- A service that allows **ProcessA** to put messages into a message queue that can be picked up by **ProcessB**
- **ProcessB** would be "subscribed" to messages created by **ProcessB**
- **ProcessB** could then choose messages that have been ingested and acted upon

**SNS** *Amazon SNS*

Simple Notification Service

This is an immediate notification process. Messages sent via SNS might be
- Email
- SMS (Text)
- Mobile Push: Notifications pushed directly to the mobile device, not through an SMS message
![Mobile Push](https://raw.githubusercontent.com/cimitrasoftware/AWS-Certified-Cloud-Practitioner-Notes/main/images/sns_iphone.png)

  





