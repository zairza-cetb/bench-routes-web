---
title: Bench Routes Collector
weight: 16
---

Collector collects the metrics needed for performing advanced operations in the regular monitoring and benchmarking of the VM instance.

## Overview	
Bench-routes monitors the VM targets and collects the metrics externally. Information like ping, jitter, flood ping, req-res monitors are good to have since these define the overall state of the instance. However, information related to the internal conditions like the core usage, http requests, memory, processes behaviour are important to monitor. With the introduction of universal tsdb, this is now possible. Collector aims to collect internal metrics of VM instances, which can be accessed over http, thus helping in carrying out advance calculations.

## Approach
Bench-routes-collector is designed to be deployed on the VM instance which is to be monitored by bench-routes. When the collector is deployed, it will auto-start during the system boot and being monitoring the processes running in the instance. The data from monitoring the processes would be saved as time-series.

