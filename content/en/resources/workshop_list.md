---
title: Workshop List
linkTitle: Workshop List
weight: 1
description: A list of Observability Workshops.
draft: true
---

|Category|Name&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Description|
|-|-|-|
|Main|[Splunk4Rookies Observability](/en/s4r/)|A user-oriented workshop where you will experience an issue and use Splunk Observability Cloud to troubleshoot and identify the root cause. Good for those wanting to gain an understanding of Splunk Observability in a hands-on environment.|
|Scenario|[Optimize Cloud Monitoring](/en/scenarios/optimize_monitoring/)|The elasticity of cloud architectures means that monitoring artifacts must scale elastically as well, breaking the paradigm of purpose-built monitoring assets. As a result, administrative overhead, visibility gaps, and tech debt skyrocket while MTTR slows. This workshop will explore how to standardize data collection and tages with OTel, reuse content across teams, improve timeliness of alerts, and correlate infrastructure metrics and logs|
|Scenario|[Understand Impact of Changes](/en/scenarios/understand_impact_of_changes/)|Splunk Observability Cloud includes powerful features that dramatically reduce the time required for SREs to isolate issues across services, so they know which team to engage to troubleshoot the issue further, and can provide context to help engineering get a head start on debugging. Unlocking these features requires tags to be included with your application traces. But how do you know which tags are the most valuable and how do you capture them? This workshop will illustrate these concepts.|
|Scenario|[Debug Problems in Microservices](/en/scenarios/debug_problems/)|Service Maps and Traces are extremely valuable in determining what service an issue resides in. And related log data helps provide detail on why issues are occurring in that service. But engineers sometimes need to go even deeper to debug a problem that’s occurring in one of their services. This is where features such as Splunk’s AlwaysOn Profiling and Database Query Performance come in. This workshop will show how to use these capabilities with Splunk Observability Cloud.|
|Scenario|[Optimize End-User Experiences](/en/scenarios/optimize_end_user_experiences)|How can we use Splunk Observability to get insight into end user experience, and proactively test scenarios to improve that experience? Learn how to use synthetics, real user monitoring, dashboards and detectors to improve your visibility of poor end user experiences.|
|Scenario|[Enable Self-Service Observability](/en/scenarios/self_service_observability)|Splunk Observability Cloud includes powerful features that help central platform teams that are responsible for creating consistency, standards and best practices in an organization. This workshop will go through some of the ways to apply standardization in your Observability practice.|
|Ninja|[Splunk IM](/en/other/1-imt/)|Technical Splunk Observability Cloud Infrastructure Monitoring (IM) Workshop|
|Ninja|[Splunk IM](/en/other/2-apm)|Technical Splunk Observability Cloud Application Performance Monitoring (APM) Workshop|
|Ninja|[Splunk RUM](/en/other/9-rum)|Technical Splunk Observability Cloud Real User Monitoring (RUM) Workshop|
|Ninja|[Synthetic Scripting](/en/other/11-synthetics-scripting)|Technical Splunk Observability Cloud Synthetics Workshop|
|Ninja|[Auto-instrumentation with PetClinic (Monolith)](/en/other/3-auto-instrumentation/1-java-monolith/)|A walk-through of the basic steps to configure a Java monolith for Splunk Observability Cloud.|
|Ninja|[NodeJS Auto-instrumentation Configuration](/en/other/3-auto-instrumentation/2-nodejs/)|A walk through of using auto-discovery on a NodeJS application.|
|Ninja|[Auto-instrumentation with PetClinic (Microservices on Kubernetes)](/en/other/3-auto-instrumentation/3-java-microservices-k8s)|A walk-through of the basic steps to configure a Java microservices application on Kubernetes for Splunk Observability Cloud|
|Ninja|[Monitoring Horizontal Pod Autoscaling (HPA) in Kubernetes](/en/other/4-hpa/)|This workshop will equip you with a basic understanding of monitoring Kubernetes using the Splunk OpenTelemetry Collector. During the workshop, you will deploy PHP/Apache and a load generator. You will learn about OpenTelemetry Receivers, Kubernetes Namespaces, ReplicaSets, Kubernetes Horizontal Pod AutoScaling and how to monitor all this using the Splunk Observability Cloud. The main learnings from the workshop will be a better understanding of the Kubernetes Navigator (and Dashboards) in Splunk Observability Cloud as well as seeing Kubernetes metrics, events and Detectors.|
|Ninja|[Making Your Observability Cloud Native With OpenTelemetry](/en/other/5-opentelemetry-collector)|Organizations getting started with OpenTelemetry may begin by sending data directly to an observability backend. While this works well for initial testing, using the OpenTelemetry collector as part of your observability architecture provides numerous benefits and is recommended for any production deployment. In this workshop, we will be focusing on using the OpenTelemetry collector and starting with the fundamentals of configuring the receivers, processors, and exporters ready to use with Splunk Observability Cloud. The journey will take attendees from novices to being able to start adding custom components to help solve for their business observability needs for their distributed platform.<br><br>The workshop uses the OpenTelemetry Collector Contrib version, which helps attendees understand how to configure it for Splunk Observability Cloud.|
|Ninja|[Build a Distributed Trace in Lambda and Kinesis](/en/other/6-lambda-kinesis)|This workshop will equip you with how a distributed trace is constructed for a small serverless application that runs on AWS Lambda, producing and consuming a message via AWS Kinesis. We will see how auto-instrumentation works with manual steps to force a Producer function’s context to be sent to Consumer function via a Record put on a Kinesis stream.|
|Ninja|[Improving MTTR with Custom Tags](/en/other/7-mttr-custom-tags)|Tagging is at the heart of distributed tracing. It helps us understand our business better, and isolate what situations may cause an application to underperform or hit errors. This workshop provides a technique for adding custom tagging through automation.|
|Ninja|[Getting Data In (GDI) with OTel and UF](/en/other/8-gdi)|This getting data in (GDI) workshop will walk through ways to instrument applications for tracing, metrics and logs. It walks through deploying the OTel Collector, OTel instrumentation, and the Universal Forwarder.<br><br>NOTE: Since this workshop was create the OTel TA was created, which makes it even easier to deploy an OTel Collector and a UF together in a single deployment.|
|Ninja|[Splunk OnCall](/en/other/10-oncall)|Module for incorporating On Call with Splunk Observability Cloud|

### Older Workshops

|Category|Name|Description|
|-|-|-|
|Ninja|[Splunk OpenTelemetry Workshop](https://signalfx.github.io/otelworkshop/)|A deep workshop that goes through instrumenting a variety of types of applications.<br><br>Some of the methods have changed since this workshop was last updated, but given the breadth of this workshop it is still listed.|