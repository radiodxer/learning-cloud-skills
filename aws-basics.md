# AWS Basics  <!-- omit in toc -->


# Table of Contents  <!-- omit in toc -->
- [Introduction](#introduction)
- [The Most Important Thing: Get an AWS Account](#the-most-important-thing-get-an-aws-account)
- [Basic AWS Knowledge](#basic-aws-knowledge)
- [Practical Knowledge: the Portal](#practical-knowledge-the-portal)
- [Practical Knowledge: the CLI](#practical-knowledge-the-cli)
- [Practical Knowledge: Infrastructure as Code](#practical-knowledge-infrastructure-as-code)
- [Certifications](#certifications)
- [About Learning in General](#about-learning-in-general)
- [Final Words](#final-words)


# Introduction

This document gives basic instructions how to start building [AWS](https://aws.amazon.com/) related cloud skills.

NOTE: This document is not an AWS course but provides a recommended roadmap how to start building your AWS skills.

# The Most Important Thing: Get an AWS Account

I cannot emphasize this enough: You cannot learn AWS effectively unless you have an AWS account. You need the account for trying things in the Portal, trying to deploy AWS services etc. Watch the costs, though - always delete all resources after you have tried them.

# Basic AWS Knowledge

First learn some basics regarding AWS: some introduction to AWS, AWS basic services, AWS portal and so on. You should use google search to find appropriate documents using e.g. keywords like: "AWS getting started", "AWS introduction", "AWS fundamentals" etc. Remember to check that the document or course is not older than a couple of years - things move fast in the cloud world.
 
Some recommended sites for learning this part:

- [AWS](https://docs.aws.amazon.com/)
- [Pluralsight](https://www.pluralsight.com)
- [edX](https://www.edx.org/school/aws)

Don't get dwelved into too deep in theoretical learning, though. Learn just the basics so that you understand:

- The basic idea of cloud and how AWS provides cloud services.
- The most important services: virtual private cloud, basic storage and computing services.
- How to use the Portal to find things.

Once you understand the basics just move on to a more practical part.

# Practical Knowledge: the Portal

Once you have an AWS account use the [AWS Portal](https://aws.amazon.com/) the same time you are reading some AWS documentation or watching some AWS course. Try to create the resources yourself using the portal. It is important that you learn to navigate in the portal and also how to create resources using the portal even though in most cases you are not going to use the portal when creating the resources (more about that later).

# Practical Knowledge: the CLI

Once you know the basics of AWS portal you should learn [AWS Command-line interface - CLI](https://aws.amazon.com/cli/). AWS CLI is a cross-platform CLI - you can use it the same way in Linux and Windows.

So, install AWS CLI and try to create resources, query resources and delete resources using it. The problem with any Portal is that you cannot automate things very well by recording mouse clicks. So, your first step for automation is the CLI (but don't stop there - read the next chapter).


# Practical Knowledge: Infrastructure as Code

If you want to be a real cloud guru you need to learn how to automate cloud infra properly using [Infrastructure as Code](https://en.wikipedia.org/wiki/Infrastructure_as_code).

There are a couple of good candidates for this:

- [AWS CloudFormation](https://aws.amazon.com/cloudformation/).
- [Terraform](https://www.terraform.io/).

There are other tools as well - feel free to use google to search them. I recommend those two tools since I believe they are most used when creating infra code in AWS.

Which one to learn? Learn both. CloudFormation is AWS native way to create infra code. You should have at least basic knowledge how to create and maintain resources using CloudFormation. AWS provides a bunch of useful [AWS CloudFormation Templates](https://aws.amazon.com/cloudformation/aws-cloudformation-templates/) - choose some and try to deploy them. Examine the infra code and try to make some of your own changes and re-deploy.

I have used both CloudFormation and Terraform and personally I like Terraform more. So, I recommend to learn at least the basics of Terraform as well. Terraform has one important advantage over cloud native tools - you can use Terraform with any big cloud provider, i.e. learn to use Terraform well and you can use it with AWS, AWS and GCP.

If you are interested about Terraform I strongly recommend to watch some Terraform Introduction, e.g. [Terraform - Getting Started](https://www.pluralsight.com/courses/terraform-getting-started).

Then boldly start using Terraform to create AWS resources. Experiment. Learn. I have created one project specifically for this purpose: [aws-intro-demo
](https://github.com/tieto-pc/aws-intro-demo). Try to follow instructions in that project and deploy the infrastructure. If you had some issues with the demonstration I'd appreciate if you send me a short email regarding it. 


# Certifications

I strongly recommend you to get [AWS Certified](https://aws.amazon.com/certification/). There are a few good reasons:

- You make yourself a goal for your studies.
- The certification works as a validation that you know at least the basics of AWS.
- Your company can use your certifications at least in two ways: a company needs a certain amount of certified specialists to get some premium level of partnership with the cloud provider, and more and more the customers are asking for certified cloud specialists to be named in responses regarding the request for proposal.


# About Learning in General

I realized that this chapter is a bit more general to be a document of its own - this way we can link it to any cloud specific document. So, here it is: [How to Be an Effective Learner?](learning-howto.md).


# Final Words

I hope you the best in your studies to become a cloud guru!
