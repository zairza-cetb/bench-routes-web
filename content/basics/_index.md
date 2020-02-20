+++
title = "Basics"
date = 2020-02-20T01:52:40+05:30
weight = 5
chapter = true
pre = "<b>I. </b>"
+++

### Chapter I

# Intoduction

Monitoring has been tough and with the increase in the routes used in any sophisticated project, the performance and metrics of an application are seriously affected. 
With an increase in server computational models, the probability of a complete request-response cycle without any throws is nowhere close to 1. 
bench-routes acts as a routes-benchmarking, monitoring, and route-network analysis tool. It monitors the routes of the application and analyses the network pipe between the server-client.

# Goals

- Benchmark route
- Load-handling of application on the individual route.
- Test various possibilities of data in params (Permutate params), like sending an empty param to see how the server response behaves.
- Analyse network performance of the hosted application irrespectively of containerization
- Network ping
- Jitter analysis
- Packet loss
- Log error handling capability of the application
- Maintain a check on server-route output and alert on changes above the threshold
- Graphical view using ElectronJS
