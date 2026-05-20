---
title: Blog 3
date: 2026-02-14
author: Chanel Christy Pei
summary: This blog is about how users interact with service providers through structured profiles and messaging.
tags:
  - platform features
  - user interaction
  - service design
---
Building on the earlier functional requirements around trust, safety, and service discovery, I began to further develop how users would actually interact with individual service providers once they enter the platform. At this stage, I was focusing more on the detailed structure of service information and how communication between users and providers would occur in a practical and efficient way. 

So a key requirement is the service listing and provider profiles. Each business or provider should have a structured profile including their services, availability, location or service area, pricing range, examples of previous work, and uploaded photos of their services or products. These businesses or providers can also upload regular listing posts to market themselves, and this content would appear on the user’s search page. 

This directly supports user needs for clarity and informed decision-making, allowing users to compare providers quickly before contacting them. The priority here is transparency of information so users can reduce uncertainty before booking. A constraint is that some small providers may not have formal pricing structures or portfolios, meaning the system must remain flexible and accessible for both professional businesses and smaller providers. From a feasibility standpoint, this is highly achievable because it is essentially a structured profile page with optional fields, similar to existing marketplace platforms. 

Beyond how information is displayed, another important aspect of the system is how users communicate and finalise service decisions. This is why we decided to implement a messaging system that would allow users to directly contact service providers for questions, negotiation, and booking without needing to exchange personal phone numbers. Initially, we considered implementing a simple booking feature. However, we realised that many services operate differently depending on the complexity of the request. For example, some providers may only be able to estimate pricing after understanding the specific issue, such as a plumbing problem or repair request. Messaging also allows users to share additional details, photos, or explanations before confirming a booking, making communication more flexible and practical for both sides. 

The design flow would be :
```
search/filter -> view listing -> contact provider
```

From a user needs perspective, messaging supports clarity, negotiation, and convenience without requiring external communication tools (e.g. personal phone number). The priority is reducing friction between discovery and booking. A constraint is that real-time messaging systems require more technical complexity (notifications, message storage, response handling), so a simplified version such as a basic inbox or request-based messaging system may be more feasible for this project. 
