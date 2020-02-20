---
title: Installation
weight: 15
---

The following steps here are to setup bench-routes in your local environemnt to perform a full fledged analysis of your routes. We use **make** for building and executing our program.


# Quickstart
- Updating the dependencies: `make update`
- Executing the application (assuming all dependencies are installed): `make run`
- Building the application for the current OS: `make build`
- Testing Golang code: `make test`
- Complete testing include building for all OSs out there: `make test_complete`
- Cleaning up the residual files: `make clean`
- *(optional)* Check linting (assuming golangci-lint is installed): `make lint`