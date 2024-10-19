---
layout: post
title:  "Introducing the Terraform provider for NetScaler SDX"
excerpt: "NetScaler has introduced a new Terraform provider as part of the broader NetScaler Automation Toolkit. With the new provider, you can write infrastructure-as-code templates specific to deployment topologies that use NetScaler SDX, a hardware application delivery controller (ADC), for on-premises application delivery. The new Terraform provider will help IT and automation teams make NetScaler SDX part of automation pipelines."
author: konstantinos
categories: [ Blogs ]
tags: [netscaler, github, terraform, sdx, svm, automation]
image: assets/images/2024-05-30-introducing-terraform-provider-for-netscaler-sdx.jpg
featured: false
hidden: false
comments: false
---

<div style="text-align: center; font-size: small;">Photo by <a href="https://unsplash.com/@sortino?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Joshua Sortino</a> on <a href="https://unsplash.com/photos/worms-eye-view-photography-of-ceiling-LqKhnDzSF-8?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a></div>


&nbsp;  

NetScaler has introduced a new Terraform provider as part of the broader NetScaler Automation Toolkit. With the new provider, you can write infrastructure-as-code templates specific to deployment topologies that use NetScaler SDX, a hardware application delivery controller (ADC), for on-premises application delivery. The new Terraform provider will help IT and automation teams make NetScaler SDX part of automation pipelines. 

NetScaler SDX is a hardware-based ADC that supports multi-tenancy, making it ideal for large enterprises and service providers needing to manage multiple applications or clients from a single device. It allows consolidating of multiple NetScaler instances on a single appliance, providing flexibility and efficiency in managing network traffic. NetScaler SDX is designed to optimize the performance, security, and scalability of applications. 

> Using Terraform to configure NetScaler SDX brings significant advantages, especially in terms of automation, consistency, and scalability. Terraform allows you to define and manage both the configuration of NetScaler SDX and the provisioning of NetScaler instances in the same appliance through code, ensuring that deployments are repeatable and maintainable. This approach reduces the risk of human error, accelerates deployment times, and facilitates version control. 

The new Terraform provider for NetScaler SDX enables you to automate manual operations including but not limited to:

Provisioning and managing NetScaler VPXs (virtualized ADCs) including deploy, start, stop, reboot, and more
Creating and managing admin profiles 
Managing authentication servers including:
TACACS (Terminal Access Controller Access-Control System)
LDAP (Lightweight Directory Access Protocol)
RADIUS Server
Managing other operations including:
System users and groups
Syslog and NTP (Network Time Protocol) servers
SNMP (Simple Network Management Protocol) traps and alarms


## The Terraform provider for NetScaler SDX is available on the Terraform Registry

In response to customer requests, the Terraform provider for NetScaler SDX is now available on the Terraform Registry

<div style="text-align: center; font-size: small;"><img class="featured-image img-fluid" src="/assets/images/netscalersdxregistry.png" alt="terraform registry"></div>

- Terraform Registry is a centralized repository for all Terraform providers. Easily discover, share, and reuse provider configurations.
Providers on the Terraform Registry are versioned, which ensures compatibility between 
- Terraform configurations and provider features. Get the specific provider version and control when and how provider updates are applied.
Terraform providers for NetScaler come with comprehensive documentation and examples. Having a single place for documentation makes it easier for you to understand how to use a provider, configure its resources, and troubleshoot issues.
- Terraform providers for NetScaler are validated by both HashiCorp and NetScaler before being published on the Terraform Registry. This ensures that we meet quality standards, follow best practices, and ensure that no malicious code is contained in our providers.
- All Terraform providers for NetScaler integrate seamlessly with other Terraform features and services, such as Terraform Cloud and Terraform Enterprise.

The Terraform provider for NetScaler SDX simplifies infrastructure management, helps promote best practices, ensures compatibility and security, and fosters community collaboration.

The Terraform provider for NetScaler SDX is also available on GitHub.

## Benefits of using the Terraform provider for NetScaler SDX 

> The Terraform provider for NetScaler SDX provides infrastructure as code to manage your ADCs via NetScaler SDX. Using the Terraform provider, you can provision, start, stop, and reboot NetScaler VPXs (virtualized ADCs) on NetScaler SDX. Configuring a multi-tenant appliance via infrastructure as code through the Terraform provider for NetScaler SDX offers several important advantages:

- Ensuring that your NetScaler ADCs  are configured consistently every time they are deployed or updated makes it much easier to manage the entire lifecycle of ADCs — from initial provisioning to Day 2 operations and decommissioning.
- Streamlining deployment, provisioning, and management tasks saves you time and reduces the potential for human errors that can occur during manual configuration. These operations become easier and more manageable.
- Following DevOps practices allows traceability, accountability, and rolling back of changes when needed. With the use of version control systems, you can track changes, review history, and collaborate with team members. 
- Complying with security policies, standards, and best practices becomes easier with the use of golden templates. Terraform will automatically configure your NetScaler appliances in a secure and compliant manner, which is crucial for regulatory requirements and auditing purposes.
- Creating new environments becomes straightforward by documenting and reproducing existing verified configurations in different environments (such as development, testing, and production). 

<div style="font-size: small;">* This blog was originally published at <a target="_blank" href="https://www.netscaler.com/blog/application-modernization/introducing-the-terraform-provider-for-netscaler-sdx/">NetScaler Blogs</a></div>

&nbsp;  
