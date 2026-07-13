---
title: "Everything you need to know about Kubernetes autoscaling at fleet scale"
url: "https://www.qovery.com/blog/everything-i-wanted-to-know-about-kubernetes-autoscaling"
date: "2026-03-30"
author: "pierre"
feed_url: "https://www.qovery.com/rss.xml"
---
When engineers configure pod autoscaling, they instinctively tie the Horizontal Pod Autoscaler (HPA) to CPU utilization. If the application is actually bound by memory or downstream database connections, the cluster sits idle while incoming requests time out. Diagnosing hundreds of outages reveals a clear pattern: effective elasticity requires scaling on custom application queues, not just default hardware thresholds.
