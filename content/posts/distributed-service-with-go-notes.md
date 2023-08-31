---
title: "\"Distributed Service With Go\" Notes"
date: 2023-08-31T16:27:18+07:00
draft: false
---


### What is a graceful shutdown and how to handle ungraceful shutdowns

* Graceful shutdown occurs when a service finishes its ongoing tasks, performs its processes to ensure there's no data los, and prepares for a restart.

* If the service crashes or its hardware fails, then a ungraceful shutdown will occur.

* To handle ungraceful shutdowns, perform sanity check when the system restart and rebuild the data from uncorrupted sources.  

<br>

**Distributed Service with Go** - *Travis Jeffery*

