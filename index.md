The following are a list of blogs, books and projects I developed in the past few years. 

# Blogs

-  [New Google Cloud Tau VM Benchmarks](https://blog.doit-intl.com/new-google-cloud-tau-vm-benchmarks-8900103cbe6)

# Books

- [Architecting Multi Cloud SaaS Solutions](https://www.manning.com/bundles/cross-cloud-access-to-SaaS-application)

# Codelabs

- [GKE Marketplace Integration](https://mktplace.cloud/codelabs/gke-mp-codelab/index.html)

# Customer Projects

## RedisLabs - GKE Marketplace Integration

Redis Enterprise Edition is available on GKE Marketplace. I developed the GKE integration for them. You can find the code [here](https://github.com/RedisLabs/gkemarketplace)

## Amazon MQ Disaster Recovery Architecture

Customers using Amazon MQ frequently ask for a cross region DR. This [solution](https://github.com/sam-andaluri/BrokerSync) provides a way to copy messages from primary region to DR region and keep the messages in-sync between regions.

## Amazon MQ CloudWatch Dashboard

Amazon CloudWatch provides a rudimentary service dashboard and widgets for building custom dashboards. However, the default dashboards are difficult to read and interpret, especially if you have multiple brokers. This [solution](https://github.com/sam-andaluri/mqdashboard) provides enriched dashboard where users can see the brokers (primary/standby), queues and topics and drill down to queue and topic level charts.

## Cross Region/Cross Account Dashboard Architecture

Many enterprise customers in AWS use multiple accounts to segregate their workloads (by project/environment). Quite often, this could results in 10s or 100s of accounts. This [solution](https://github.com/sam-andaluri/dashboard-poc) provides an architecture that helps customers to leverage [Amazon CloudWatch Cross Region/Cross Account dashboard functionality](https://aws.amazon.com/about-aws/whats-new/2019/11/amazon-cloudwatch-launches-cross-account-cross-region-dashboards/) along with auto-generated CloudWatch dashboards. The account level quotas and personal health events are also integrated into this solution. 

## Amazon MQ Enterprise Integration Patterns

Inspired by Gregor Hohpe's seminal work on [Enterprise Integration Patterns](https://www.enterpriseintegrationpatterns.com/gregor.html), developed this [project](https://github.com/aws-samples/amazon-mq-enterprise-integration-patterns) for demonstrating how to use Apache Camel with AWS messaging services. I presented this project in a reInvent 2019 Builder Session. 

## Amazon MQ Workshop

While I worked as a Specialist SA for Messaging services in AWS, made major contributions to developing an enablement [workshop](https://amazon-mq-intro.workshop.aws). This was presented in reInvent 2019 as a workshop. The code for the workshop including the samples is [here](https://github.com/aws-samples/amazon-mq-workshop). 

# Citizen Science projects

## Classifying Cloud types using cloud vision APIs

NASA runs a citizen science project named [Globe](https://observer.globe.gov). This project consists of collecting data on Cloud and Land cover classification and mosquito habitats. My children participate in the cloud cover program. The solution for this born out of question from my 13 year old daughter: If a computer vision model can identify a cat or dog, can it identify a cloud type by its shape?. To answer that question, together we set out on a journey to see how well the different cloud provider vision algorithms can identify the cloud cover. This led down a path to learn machine learning and computer vision. The following are complete solutions including a human-in-the-loop workflow for each of the three major cloud providers.
