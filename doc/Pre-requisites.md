#### [prev](./welcome.md) | [home](./welcome.md)  | [next](./take-aways.md)

# Getting started

As you transition to a cloud environment, it is quite easy to lose control of your deployment. CEOs / CIOs etc, according to several surveys, still have concerns about their visibility in to their cloud deployments.

That's where Defender for Cloud, and the built in Azure Defender come in.

## What is Defender for Cloud?

This is probably the most important thing to address. Azure Defender for Cloud is broken up in to two pieces. Piece one is Azure Security Center. Everyone gets Security Center. 

Defender for Cloud is what we refer to as a "Cloud Workload Posture Management" tool. It allows you to view the security state of your cloud resources including servers, storage, SQL, networks, applications, and workloads that are running in Azure.

Taken from [Microsoft Docs](https://docs.microsoft.com/en-us/azure/security-center/security-center-introduction) Defender for Cloud addresses three main challenges:

* **Rapidly changing workloads** – It's both a strength and a challenge of the cloud. On the one hand, end users are empowered to do more. On the other, how do you make sure that the ever-changing services people are using and creating are up to your security standards and follow security best practices?

* **Increasingly sophisticated attacks** - Wherever you run your workloads, the attacks keep getting more sophisticated. You have to secure your public cloud workloads, which are, in effect, an Internet facing workload that can leave you even more vulnerable if you don't follow security best practices.

* **Security skills are in short supply** - The number of security alerts and alerting systems far outnumbers the number of administrators with the necessary background and experience to make sure your environments are protected. Staying up-to-date with the latest attacks is a constant challenge, making it impossible to stay in place while the world of security is an ever-changing front.

The biggest benefit of Azure Defender for Cloud is ['Secure Score'](https://docs.microsoft.com/en-us/azure/security-center/secure-score-security-controls#security-controls-and-their-recommendations). Secure score is intended to help you understand your current situation and effectively and efficiently improve your security. It continually assesses your resources for security issues and then aggregates those into a single score so that you can see your current security posture. The higher the score, the lower your identified risk level. This is controlled through a policy known as [Azure Security Benchmark](https://docs.microsoft.com/en-us/security/benchmark/azure/baselines/security-center-security-baseline?toc=/azure/security-center/TOC.json) which has been built from our recommended best practices and influenced by the Azure Center for Internet Security Benchmark.

## What is Azure Defender?

Defender, in this regard, is a "Cloud Workload Protection" platform. This is the second piece of 'Defender for Cloud'. 

What does that mean? This means that Defender and it's associated features are advanced tools designed to protect your resources. It has integrated threat protection with Microsoft Defender for Endpoint (Servers) and advanced cloud protection capabilities like Just In Time administration and Adaptive Application control. It gives you a unified place to manage several different security capabilities and provides the ability to span hybrid cloud workloads. It also gives you the capability to assess your workloads against regulatory compliance frameworks.

## What is Azure Policy?

Azure Policy is a tool that allows you to enforce standards and assess compliance at scale. Think of it as Business Rules that you define and then Azure Policy compares the properties of those resources against your business rules to give you an all up view of your overall state.

#### [prev](./welcome.md) | [home](./welcome.md)  | [next](./take-aways.md)
