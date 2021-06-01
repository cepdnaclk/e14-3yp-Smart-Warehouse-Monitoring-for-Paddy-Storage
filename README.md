---
layout: home
permalink: index.html
repository-name: e14-3yp-Smart-Warehouse-Monitoring-for-Paddy-Storage
title: Smart Warehouse Monitoring for Paddy Storage
---


# Smart Warehouse Monitoring for Paddy Storage

---

## Team
-  E/14/336, SUCHINTHANA A.P.N., [e14336@eng.pdn.ac.lk](mailto:e14336@eng.pdn.ac.lk)
-  E/14/011, AGALAKUMBURA S.T., [e14011@eng.pdn.ac.lk](mailto:e14011@eng.pdn.ac.lk)m)

## Table of Contents
1. [Introduction](#introduction)
2. [Solution Architecture](#solution-architecture )
3. [Links](#links)

---

## Introduction

Networked embedded systems have become  quite important nowadays, especially for monitoring and control of distance and dislocated objects. This concept is applied in many fields in today as it increases the accuracy rather than controlling manually.

Therefore we thought to implement a embedded system to monitor and control physical quantities of a rice paddy storage. Controlling such conditions precisely will ensure the best quality. This will helpful to the businessmen who having number of such stores in many locations as it is hard to control them manually. So by using this system they can operate it easily and being in any location.

This system can be used in storage by changing the desired physical quantities.

Features
Monitoring and controlling physical quantities
Automatically controlling physical quantities up to given preset value
Maintaining a inventory system
Project Complexity
v  Embedded system to

Ø  Sense the physical quantities

Ø  Control the physical quantities

Ø  Transfer data

v  Web interface to monitor and control manually.

Each store have their own node and they are remotely operated.


## Solution Architecture
·       ♦ CO321 – The desired quantities are measured using sensors and the values are transmitted through a micro-controller to the server and the monitoring system(on pre-defined time interval/ user request). Those conditions are automatically controlled up to preset value. Other than that quantities can be controlled manually.

·       ♦ CO324 – Data from sensors and controllers are sent to a centralized server using GSM module as a SMS. Since there are many nodes, network traffic get high. It is concerned during design process to avoid drawbacks.

·        ♦CO325 – The feedback data and control data is sent as encrypted to ensure the security. Otherwise any unauthorized parties can change the message(data) unethically. This can occur a huge loss. Therefore ensuring the security is must to have a good market value  to our system.

## Hardware and Software Designs

Detailed designs with many sub-sections


## Links

- <a href = "https://github.com/cepdnaclk/e14-3yp-Smart-Warehouse-Monitoring-for-Paddy-Storage" target = "_blank"> Project Repository </a>
- <a href = "https://cepdnaclk.github.io/e14-3yp-Smart-Warehouse-Monitoring-for-Paddy-Storage/" target = "_blank">Project Page</a>
- <a href = "http://www.ce.pdn.ac.lk/" target = "_blank">Department of Computer Engineering</a>
- <a href = "https://eng.pdn.ac.lk/" target = "_blank">University of Peradeniya</a>



[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
