# Azure Basics  <!-- omit in toc -->


# Table of Contents  <!-- omit in toc -->
- [Introduction](#introduction)
- [The Most Important Thing: Get an Azure Subscription](#the-most-important-thing-get-an-azure-subscription)
- [Basic Azure Knowledge](#basic-azure-knowledge)
- [Practical Knowledge: the Portal](#practical-knowledge-the-portal)
- [Practical Knowledge: the CLI](#practical-knowledge-the-cli)
- [Practical Knowledge: Infrastructure as Code](#practical-knowledge-infrastructure-as-code)
- [Certifications](#certifications)
- [About Learning in General](#about-learning-in-general)
- [Final Words](#final-words)


# Introduction

This document gives basic instructions how to start building [Azure](https://azure.microsoft.com/) related cloud skills.

NOTE: This document is not an Azure course but provides a recommended roadmap how to start building your Azure skills.

# The Most Important Thing: Get an Azure Subscription

I cannot emphasize this enough: You cannot learn Azure effectively unless you have an Azure subscription. You need the subscription for trying things in the Portal, trying to deploy Azure services etc. Watch the costs, though - always delete all resources after you have tried them.


# Basic Azure Knowledge

First learn some basics regarding Azure: some introduction to Azure, Azure basic services, Azure portal and so on. You should use google search to find appropriate documents using e.g. keywords like: "Azure getting started", "Azure introduction", "Azure fundamentals" etc. Remember to check that the document or course is not older than a couple of years - things move fast in the cloud world.
 
Some recommended sites for learning this part:

- [Microsoft](https://docs.microsoft.com/en-us/learn/azure/)
- [Pluralsight](https://www.pluralsight.com)
- [edX](https://www.edx.org/learn/azure)

Don't get dwelved into too deep in theoretical learning, though. Learn just the basics so that you understand:

- The basic idea of cloud and how Azure provides cloud services.
- The most important services: virtual networks, basic storage and computing services.
- How to use the Portal to find things.

Once you understand the basics just move on to a more practical part.

# Practical Knowledge: the Portal

Once you have an Azure subscription use the [Azure Portal](https://portal.azure.com) the same time you are reading some Azure documentation or watching some Azure course. Try to create the resources yourself using the portal. It is important that you learn to navigate in the portal and also how to create resources using the portal even though in most cases you are not going to use the portal when creating the resources (more about that later).

# Practical Knowledge: the CLI

Once you know the basics of Azure portal you should learn [Azure Command-line interface - CLI](https://docs.microsoft.com/en-us/cli/azure/?view=azure-cli-latest). Azure CLI is a cross-platform CLI and I as a Linux user prefer using it over Powershell. But I must admit that there is one problem with the Azure CLI - too often the case with Azure is that many examples are provided only using the Powershell. Therefore I strongly suggest you to learn [Azure Powershell](https://docs.microsoft.com/en-us/powershell/azure/overview?view=azps-1.3.0) as well (especially if you are a Windows guy). Luckily you can get the Azure powershell for Linux as well.

So, install CLI or Azure Powershell and try to create resources, query resources and delete resources using it. The problem with any Portal is that you cannot automate things very well by recording mouse clicks. So, your first step for automation is the CLI (but don't stop there - read the next chapter).


# Practical Knowledge: Infrastructure as Code

If you want to be a real cloud guru you need to learn how to automate cloud infra properly using [Infrastructure as Code](https://en.wikipedia.org/wiki/Infrastructure_as_code).

There are a couple of good candidates for this:

- [Azure Resource Manager templates - ARM](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-authoring-templates).
- [Terraform](https://www.terraform.io/).

There are other tools as well - feel free to use google to search them. I recommend those two tools since I believe they are most used when creating infra code in Azure.

Which one to learn? Learn both. ARM is Azure native way to create infra code. You should have at least basic knowledge how to create and maintain resources using ARM templates. Microsoft provides a bunch of useful [Azure Quickstart Templates](https://github.com/Azure/azure-quickstart-templates) - choose some and try to deploy it. Then examine the infra code and try to make some of your own changes and re-deploy.

I have used both ARM and Terraform and personally I like Terraform more. So, I recommend to learn at least the basics of Terraform as well. Terraform has one important advantage over cloud native tools - you can use Terraform with any big cloud provider, i.e. learn to use Terraform well and you can use it with Azure, AWS and GCP.

If you are interested about Terraform I strongly recommend to watch some Terraform Introduction, e.g. [Terraform - Getting Started](https://www.pluralsight.com/courses/terraform-getting-started).

Then boldly start using Terraform to create Azure resources. Experiment. Learn. I have created one project specifically for this purpose: [azure-intro-demo
](https://github.com/tieto-pc/azure-intro-demo). Try to follow instructions in that project and deploy the infrastructure. If you had some issues with the demonstration I'd appreciate if you send me a short email regarding it. 


# Certifications

I strongly recommend you to get [Azure Certified](https://www.microsoft.com/en-us/learning/azure-certification.aspx). There are a few good reasons:

- You make yourself a goal for your studies.
- The certification works as a validation that you know at least the basics of Azure.
- Your company can use your certifications at least in two ways: a company needs a certain amount of certified specialist to get some premium level of partnership with the cloud provider, and more and more the customers are asking for certified cloud specialists to be named in responses regarding the request for proposal.


# About Learning in General

I realized that this chapter is a bit more general to be a document of its own - this way we can link it to any cloud specific document. So, here it is: [How to Be an Effective Learner?](learning-howto.md).


# Final Words

I hope you the best in your studies to become a cloud guru!