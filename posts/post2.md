---
title: Blog 2
date: 2026-02-14
author: Chanel Christy Pei
summary: Short description ..
tags:
  - tag1
  - tag2
  - tag3
---
As my teammate and I developed our concept further, I began thinking about the core functional requirements. Since BlaBla Corp already manages the profile and login system, I understood that I need to focus on the experience inside the platform itself. This shift moved my attention towards discovery, communication, accessibility, and trust between community members.

One of the most essential functions of the platform is local service discovery. Since users need to be able to quickly find  businesses and independent providers that are available after working hours locally, the system must support location-based browsing, category filtering, and a search bar. The platform uses the user's geographic location to show services within their area and the category filtering helps users to find services quickly based on their needs in categories such as beauty, repairs, and food. However, since these categories might be confusing to some users, they could also use the search bar to narrow down to more specific services by linking the keywords used to the ones mentioned in the businesses/providers listing. The filtering is designed so that users can navigate easily and quickly. 

In terms of user needs, this supports users who are time-poor and need fast decision-making after work hours. The priority here is speed and ease of access rather than deep exploration. A key constraint is that users may be searching in urgent or time-sensitive situations, meaning the system cannot rely on complex navigation or too many steps. From a feasibility perspective, this feature is realistic because it can be implemented through structured database filtering (location + category tags + keyword search), which is standard in web systems.

However, there would still be trust and safety concerns as some of our providers might be located in their own homes or services that involve entering user’s private homes or receiving personal care. This is why another essential function is the trust and verification system. Because the platform may include independent or home-based service providers, users need a way to assess reliability. This could include verification badges, review systems, and moderation processes. Verification of businesses is done through our ‘admins’ and review systems are left by previous customers. 

From a user needs perspective, this feature supports safety, confidence, and trust before committing to a service. This was prioritised because safety is more important than convenience in contexts where users are interacting with real-world providers in potentially private environments. A key constraint is that verification/ranking systems may unintentionally favour more popular providers and reduce visibility for smaller or newer businesses. To address this, I have decided not to implement ranking-based filtering or “verified-only” search restrictions. Instead, all listings would appear equally on the main browsing page. Ratings (out of 5 stars) would be included as an additional informational feature under each business listing, and verification would be displayed as a simple checkmark icon next to the provider’s name.

In terms of feasibility, basic verification (admin approval + review system) is achievable within the scope of a simple web-based platform. However, more advanced verification processes such as licensing checks or identity validation may be limited due to time, technical complexity, and system constraints.

