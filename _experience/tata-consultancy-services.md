## PLM Related Tasks (ENOVIA)

## Multi-tenant Medical Device Complaints Handling Platform

### Overview

The pharmaceutical client where previously they had an on-premises monolith web application in Java to handle medical device complaints from users. Medical devices include pacemakers, ultrasound machines, CT scanners, MRI machines, etc. They wanted to move to the cloud, primarily AWS, and build a reliable, scalable, and maintainable system. The key features targeted were authorization, data access, tenant isolation, metrics, billing, logging, etc.

### Purpose / the why?



### Background / the what?

Medical Device Complaints Handling (MDCH) is a regulatory requirement that helps mitigate risk. It is a reactive, not a proactive process. Any medical industry like pharmaceutical, biotech, etc. must follow certain protocols, handling complaints effectively being one of them. A complaint is different from feedback. The former expresses dissatisfaction, is mostly negative and expects a response or resolution. Whereas, the latter is more general, can be either positive or negative, and may not always seek resolution.

#### Sources of complaints:
- **Emails:** Complaints received through customer service or company email addresses.
- **Phone Calls:** Issues reported via call centers or customer support lines.
- **Social Media:** Complaints are made on social media platforms like LinkedIn, Facebook, Instagram, and others.
- **Live Chat:** Issues communicated through website live chat.
- **Feedback Forms:** Complaints are submitted through online or physical feedback forms.
- **Text Messages/SMS:** Customer grievances are sent via text messaging service or SMS (Short Message Service).
- **Company Website:** Complaints are submitted through contact forms or portals on the website.
- **Direct Mail:** Written complaints sent through postal mail.
- **Online Review Platforms:** Negative reviews or complaints are posted on review platforms like G2 Crowd, Trustpilot, Capterra, Google Reviews, and others.
- **In-Person:** Direct complaints made at the company’s physical locations.

#### Types of complaints:
- **Incident-driven:** requires immediate action. Examples include device malfunctions, adverse reactions, equipment failures, issues leading to inaccurate readings, etc.
- **Review-driven:** post-market surveillance (PMS). Sources include incident reports, trend reports, technical literature, distributors’ and importers’ feedback, and customer online reviews.

#### Process for MDCH:

Phase 1. Receiving the customer complaint
2. Registering the complaint
3. Reporting medical device complaints (if applicable)
4. Investigating the complaint
5. Closing the complaint

###### Phase 1

Customer complaint comes in

###### Phase 2

Required minimum details about the complaint are logged

###### Phase 3

Is it a reportable event?
If yes,
  submit Medical Review Report (MDR) and end.

###### Phase 4

Is investigation required?
If yes,
  is CAPA required?
  If yes, 
    Take required action.
Else, 
  Document Justification.

###### Phase 5

Complete the documentation and close complaint.

### Technical approach / the how?

Components:
- Front-End:
  - S3
  - CloudFront
  - Route 53
- Back-End:
  - On-Prem VPC (for secure data)
  - EC2 + RDS
  - Lambda + DynamoDB (later to MongoDB)
- Authentication:
  - API Gateway
  - Cognito



## Semantic Document Search Engine

## Service Ticket Resolution Chatbot

## Transition RPA Tools to OSS
