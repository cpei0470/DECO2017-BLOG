---
title: Blog 4 - Comperative Analysis
date: 2026-02-14
author: Chanel Christy Pei
summary: This blog compares the proposed platform with existing services like Local2Local, leading to my refined design decisions.
tags:
  - system design
  - refinement
---
In this final stage of the design process, I began refining my concept by comparing it with existing platforms and identifying how my idea differs in purpose, structure, and user experience. This helped me move from early functional thinking into more concrete design decisions, particularly around system flow, data structure, and overall platform direction.

Firstly, I analysed a similar platform called Local2Local, which is designed to connect users with mobile service providers for immediate services. The platform allows service seekers to engage active providers, track their arrival through a map feature, and communicate through a messaging system to discuss pricing, timing, and job details. In many ways, it functions as a real-time service marketplace where users can quickly locate and book available providers.

While Local2Local is effective in supporting location-based service access, I identified key differences between their system and my proposed concept. Local2Local primarily focuses on immediate service fulfilment and proximity-based matching, whereas my design is more specifically shaped around Sydney’s after-hours economy. My platform prioritises availability outside standard working hours rather than immediate dispatch. This means time accessibility becomes a core design constraint, not just location.

Through this comparison, I realised that my concept is less about rapid service matching and more about structured discovery within a specific lifestyle context. Unlike Local2Local, my system does not rely heavily on real-time tracking or urgency-based matching. Instead, it focuses on helping users find services that align with their schedules after traditional 9–5 working hours. This distinction helped refine the scope of the platform and prevent it from becoming too similar to existing service marketplace apps.

As a result of this analysis, I made several key design decisions. I decided to simplify the system by removing real-time tracking features (such as distance-to-user indicators, visual navigation, etc), as they were not essential to the core problem I am addressing. This decision was made to prioritise clarity, feasibility, and alignment with user needs rather than replicating features found in existing platforms. 

To better understand and test the interaction flow between users and providers, my teammate and I created mid-fidelity wireframes in Figma. These included multiple key screens such as the search page, listing upload page, messaging interface, and business profile pages. We also created three variations of the search page to support future user testing and compare which layout best supports usability and clarity. At this stage, the wireframes were used to define and communicate our intended interaction design, rather than to formally evaluate it through user testing. 

From this, we began refining the system flow. From the provider perspective, the flow involves creating a service profile, uploading listings, and responding to user messages. From the user perspective, since the BlaBla Corp system already provides login and user profiles, users directly enter the platform and begin with browsing. The user flow includes searching or filtering services on the search page, using the search bar for specific needs, viewing individual listings, opening provider profiles, and then initiating contact through messaging to make a booking or enquiry.

This helped us understand the platform more clearly as a service interaction system rather than a signup-based application, where the main focus is on discovery and communication.