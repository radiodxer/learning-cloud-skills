# GCP Basics  <!-- omit in toc -->


# Table of Contents  <!-- omit in toc -->
- [Introduction](#Introduction)
- [The Most Important Thing: Get a GCP Account](#The-Most-Important-Thing-Get-a-GCP-Account)
- [Basic GCP Knowledge](#Basic-GCP-Knowledge)
- [Practical Knowledge: the Portal](#Practical-Knowledge-the-Portal)
- [Practical Knowledge: the CLI](#Practical-Knowledge-the-CLI)
- [Practical Knowledge: Infrastructure as Code](#Practical-Knowledge-Infrastructure-as-Code)
- [Certifications](#Certifications)
- [About Learning in General](#About-Learning-in-General)
- [Final Words](#Final-Words)


# Introduction

This document gives basic instructions how to start building [GCP](https://cloud.google.com/) (Google Cloud Platform) related cloud skills.

NOTE: This document is not a GCP course but provides a recommended roadmap how to start building your GCP skills.

# The Most Important Thing: Get a GCP Account

I cannot emphasize this enough: You cannot learn GCP effectively unless you have a GCP account. You need the account for trying things in the Portal, trying to deploy GCP services etc. Watch the costs, though - always delete all resources after you have tried them.


# Basic GCP Knowledge

First learn some basics regarding GCP: some introduction to GCP, GCP basic services, GCP portal and so on. You should use google search to find appropriate documents using e.g. keywords like: "GCP getting started", "GCP introduction", "GCP fundamentals" etc. Remember to check that the document or course is not older than a couple of years - things move fast in the cloud world.
 
Some recommended sites for learning this part:

- [GCP](https://cloud.google.com/training/)
- [Pluralsight](https://www.pluralsight.com)
- [Coursera](https://www.coursera.org/)

Don't get dwelved into too deep in theoretical learning, though. Learn just the basics so that you understand:

- The basic idea of cloud and how GCP provides cloud services.
- The most important services: virtual private cloud, basic storage and computing services.
- How to use the Portal to find things.

Once you understand the basics just move on to a more practical part.

# Practical Knowledge: the Portal

Once you have a GCP account use the [GCP Console](https://console.cloud.google.com) (I use terms "Console" and "Portal" to mean the same thing in this document) the same time you are reading some GCP documentation or watching some GCP course. Try to create the resources yourself using the portal. It is important that you learn to navigate in the portal and also how to create resources using the portal even though in most cases you are not going to use the portal when creating the resources (more about that later).

# Practical Knowledge: the CLI

Once you know the basics of GCP portal you should learn [GCP Command-line interface - CLI](https://cloud.google.com/sdk/) (called "SDK" in the GCP terminology). GCP CLI is a cross-platform CLI.

So, install CLI and try to create resources, query resources and delete resources using it. The problem with any Portal is that you cannot automate things very well by recording mouse clicks. So, your first step for automation is the CLI (but don't stop there - read the next chapter).

# Practical Knowledge: Infrastructure as Code

If you want to be a real cloud guru you need to learn how to automate cloud infra properly using [Infrastructure as Code](https://en.wikipedia.org/wiki/Infrastructure_as_code).

There are a couple of good candidates for this:

- [GCP Deployment Manager](https://cloud.google.com/deployment-manager/docs/).
- [Terraform](https://www.terraform.io/).

There are other tools as well - feel free to use google to search them. I recommend those two tools since I believe they are most used when creating infra code in GCP.

Which one to learn? Learn both. Deployment Manager is GCP native way to create infra code. You should have at least basic knowledge how to create and maintain resources using Deployment Manager (and Python as Google recommends to use Deployment Manager templates using Python). Google provides a bunch of useful [GCP Samples](https://github.com/GoogleCloudPlatform/deploymentmanager-samples) - choose some and try to deploy them. Examine the infra code and try to make some of your own changes and re-deploy.

I have used both Deployment Manager and Terraform and personally I like Terraform more. So, I recommend to learn at least the basics of Terraform as well. Terraform has one important advantage over cloud native tools - you can use Terraform with any big cloud provider, i.e. learn to use Terraform well and you can use it with AWS, Azure and GCP.

If you are interested about Terraform I strongly recommend to watch some Terraform Introduction, e.g. [Terraform - Getting Started](https://www.pluralsight.com/courses/terraform-getting-started).

Then boldly start using Terraform to create GCP resources. Experiment. Learn. I have created one project specifically for this purpose: [GCP-intro-demo](https://github.com/tieto-pc/gcp-intro-demo). Try to follow instructions in that project and deploy the infrastructure. If you had some issues with the demonstration I'd appreciate if you send me a short email regarding it. 


# Certifications

I strongly recommend you to get [GCP Certified](https://cloud.google.com/certification/). There are a few good reasons:

- You make yourself a goal for your studies.
- The certification works as a validation that you know at least the basics of GCP.
- Your company can use your certifications at least in two ways: a company needs a certain amount of certified specialists to get some premium level of partnership with the cloud provider, and more and more the customers are asking for certified cloud specialists to be named in responses regarding the request for proposal.


# About Learning in General

I realized that this chapter is a bit more general to be a document of its own - this way we can link it to any cloud specific document. So, here it is: [How to Be an Effective Learner?](learning-howto.md).


# Final Words

I hope you the best in your studies to become a cloud guru!