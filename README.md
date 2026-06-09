# Metadata-Driven-Paid-Media-Audience-Activation-Pipeline


## 📊 Metadata-Driven Paid Media Audience Activation Pipeline

This repository documents a **metadata-driven data engineering pipeline** designed to power large-scale **paid media audience segmentation and activation** across multiple advertising platforms.

The pipeline ingests audience segment data from upstream sources, processes and models it in **Microsoft Fabric**, and activates audiences via **HighTouch** using **CDC-based incremental syncs**. By syncing only new, updated, deleted, and failed records, the system ensures efficient data delivery, reduced API load, and reliable downstream activation.

A key focus of this pipeline is **operational reliability and scalability**. It includes built-in data quality checks, rejection handling with automated retries, and a centralized monitoring and alerting framework that consolidates sync failures, warnings, and recoveries into a single actionable view. The architecture is fully metadata-driven, enabling consistent onboarding, governance, and monitoring across hundreds of audience syncs without manual intervention.

This solution supports multiple paid media destinations (such as Meta, Google, TikTok, Snapchat, Reddit, and others) and is designed to meet enterprise requirements for **performance, fault tolerance, observability, and compliance**.



### 🔑 Key Capabilities

* Metadata-driven audience onboarding and sync configuration
* CDC-based incremental data processing
* Self-healing retries and rejection handling
* Centralized monitoring and alerting
* Scalable, enterprise-ready paid media activation

  <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/f1f461bb-f9f1-475c-a51a-590c3cb0b2f8" />

