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
- ![Mobile Push](https://raw.githubusercontent.com/cimitrasoftware/AWS-Certified-Cloud-Practitioner-Notes/main/images/sns_iphone.png)

  


