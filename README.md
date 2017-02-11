---
title: SCS Commerce
---

## Intro

This project is an example implementation addressing some of principles behind the SCS architecture and front-end integration. This project provides different service implementations (merely stubs without actual persistence implementation) that integrate in different scenarios appropriate for each specific problem domain.

The service landscapes which aims to build an easy and simple to use ecommerce system involves a couple of systems like [ordering](https://github.com/scs-commerce/order), [product listing](https://github.com/scs-commerce/product-list)  and a [landing page](https://github.com/scs-commerce/landing-page) which reintegrates the different domains.

Accompanying to the service repositories, a config repository is available, that contains a configuration for a running nginx web server, that serves as application server as well as caching proxy.

##  Information Architecture

To have a little structure about how we want to recombine certain information, we should think about categorizing our different information types. By splitting our system into several pieces we may end up with a few scenarios of how to share or combine content of our systems back again.
