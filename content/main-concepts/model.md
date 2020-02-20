---
title: Model of Bench Routes
weight: 10
---

Please see the Data Flow for a better understanding of the propagation of data from the above modules:

- **docs:** This directory would contain all the related documents to the project. It will also support the project documentation for general users.
examples: This would contain use-case examples of benchroutes. This may also include native CLI examples if we plan to have a cli version as well.
- **scripts:** All shell and bash scripts related to setting up, building, execution or testing would be present in this directory. This would ease the development process.
- **src:** This is the main directory that contains the development code. Majority of the development process would take place here.
- **lib:** This directory will be responsible for the core implementation of ideas in golang. 
service: Or in other words, server. This directory would contain all server related stuff like routes, controllers, etc.which would run as a daemon.
