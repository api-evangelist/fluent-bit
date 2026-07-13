---
title: "Common Architecture Patterns with Fluentd and Fluent Bit"
url: "https://fluentbit.io/blog/2020/12/03/common-architecture-patterns-with-fluentd-and-fluent-bit/"
date: "2020-12-03"
author: ""
feed_url: "https://fluentbit.io/blog/index.xml"
---
Thousands of organizations use Fluent Bit and Fluentd to collect, process, and ship their data from Kubernetes, cloud infrastructure, network devices, and other sources. These organizations may uniquely deploy Fluent Bit and Fluentd; however, many users share common architecture patterns. In this blog, we will talk about 3 of the most common architectures that users leverage when deploying Fluent Bit and Fluentd: Forwarder’s and Aggregators Side car / Agent deployment Network device aggregator Forwarder and Aggregator One of the more common patterns for Fluent Bit and Fluentd is deploying in what is known as the forwarder/aggregator pattern.
