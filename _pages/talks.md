---
layout: archive
title: "My Dissertation Topic"
permalink: /talks/
author_profile: true
---

Actively used software applications must be changed continuously to ensure their utility, correctness, and performance. To perform these changes, programmers spend a considerable amount of time and effort pinpointing the exact locations in the code to modify, a particularly hard task for distributed applications. In distributed applications, server/middleware misconfigurations and network volatility often cause performance and correctness problems. My dissertation research puts forward a novel approach to facilitating the evolutionary modifications of distributed applications that introduces *a novel automated refactoring* --- **Client Insourcing**. 
This refactoring transforms a distributed application into its semantically equivalent centralized variant, in which 
the remote parts are glued together and communicate with each other by means of regular function calls, eliminating any middleware, server, and network related problems from the list of potential problem causes. Programmers then can use the resulting centralized variant to facilitate debugging, security enhancements, and fault-tolerance adaptations.

