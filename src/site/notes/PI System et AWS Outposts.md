---
{"Source":"#","dg-publish":true,"permalink":"/blog-articles/data/pi-system-et-aws-outposts/","dgPassFrontmatter":true}
---

Hybrid architectures are often where the tension between OT and IT roles becomes most visible. OT teams are focused on reliability, deterministic performance, and compliance with industrial standards, while IT teams prioritize scalability, integration, and cost efficiency. When time series data is involved—whether from sensors, industrial assets, or enterprise systems—the architecture must bridge both worlds without creating silos.

That’s where AWS Outposts is interesting. It essentially extends AWS infrastructure and services into on‑premises environments, but with the same APIs, tools, and management plane as the cloud. This consistency is what reduces the “extra effort” you mentioned—teams don’t have to re‑engineer pipelines or re‑train staff for different environments. For time series workloads, this means:

Data locality: Outposts allows sensitive or latency‑critical time series data (like industrial sensor streams) to stay on‑premises while still being processed with AWS services.

Unified tooling: Whether you’re using Amazon Timestream, Kinesis, or SageMaker, the same APIs and SDKs apply across cloud and Outposts.

Hybrid flexibility: You can design pipelines where preprocessing happens locally (e.g., filtering or anomaly detection at the edge) and aggregation or advanced analytics happen in the cloud.

Governance and compliance: Outposts helps organizations meet regulatory requirements by keeping data in specific geographies or facilities, while still benefiting from cloud‑native services.

![](https://i.imgur.com/qs7y1np.png)

