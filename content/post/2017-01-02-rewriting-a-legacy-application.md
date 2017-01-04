---
title: "Rewriting a legacy application"
date: "2017-01-02"
comments: true
sharing: true
footer: true
categories: [architecture, software]
author: "Ramjee Ganti"
---

We have a legacy enterprise product which we are now rearchitecting. It's reasonably complex product with it's own idiosyncrinacies. If there were an award for entries in [CODESOD](http://thedailywtf.com/series/code-sod), the code in this legacy application would win it a million times. While we are still working on the architecture we set ourseleves a few non negotiables in the re development process.

* Cloud Native
* Automated Deploy
* Testability (Unit Tests, Integration Tests)
* Automated code quality checks
* No direct access to DB except by the service layer
* Ease of maintenance always wins
* Imposed/implied constraints in development process over reliane on developer self discpline
* Common development tool chain for all involved
* Proper naming of variables
* Low Coupling, High Cohesion
* DRY
* Security (not as an afterthought)
* Monitorability
