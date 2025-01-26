---
title: 'Home Lab Setup'
description: 'A short introduction of my current and growing home lab setup.'
summary: "A short introduction of my current and growing home lab setup."
date: '2025-01-26'
aliases:
  - home-lab-setup
author: 'Peter Summa'

#featureImage: 'homelab-setup-sw.jpeg' # Top image on post.
# featureImageAlt: 'Description of image' # Alternative text for featured image.
# featureImageCap: 'This is the featured image.' # Caption (optional).
thumbnail: 'homelab-setup-sw.jpeg' # Image in lists of posts.
shareImage: 'homelab-setup-sw.jpeg' # For SEO and social media snippets.

tags:
  - homelab
---
# My Current Lab Setup

When it comes to building my home lab, my main goal is to keep things simple, low-cost, and low-overhead. It’s a place where I can experiment with new technologies, test out virtual environments, and try out different configurations—without draining my wallet or disrupting the rest of the household. Here’s a breakdown of my current setup and how I’ve optimized it for efficiency and independence.

![Homelab Network](homelab-network-v1.png)

The primary goal of this setup is to create an isolated environment where everything can be tested without risk to the outside network. To achieve this, all traffic within the homelab is routed through a virtual instance of **OpnSense**. 

Access to the lab is strictly controlled; I connect exclusively via **RDP** to a Linux **jumphost**. This ensures that the homelab remains fully isolated from external systems and networks.

In a future post, I will dive deeper into the configuration of **OpnSense** and the internal network setup.

## The Hardware

My lab is built around **two Intel NUCs**, each equipped with **64GB of RAM**. These compact machines provide enough horsepower to run a variety of workloads, but they’re small enough to keep everything running quietly and with minimal energy consumption. 

But the best part? The lab is **completely independent from our home network**, so if something breaks or if I’m running some resource-heavy workloads, **Netflix and the rest of the household’s devices still work without interruption**. It's the perfect balance between experimenting with new tech and maintaining a smooth home environment.


![Homelab Setup](homelab-setup-sw.jpeg)
## Room for Growth

While my lab setup is functional for now, there’s always room for improvement. There’s still plenty of capacity for growth, and new hardware is always welcome—whether it's adding more storage, integrating additional virtual machines, or even expanding to more powerful components like additional NUCs or networking gear. But like with any hobby or project, **everything in due time**. I’m not in a rush to make the lab bigger or more complex; I’m more focused on optimizing what I have and gradually expanding as needed.

## Why This Setup Works for Me

This lab setup strikes the perfect balance between cost and functionality. The **Intel NUCs** are compact and efficient, and they’re flexible enough to run a variety of virtualized environments without creating too much overhead. Plus, the fact that the lab is completely isolated from the rest of the home network means that I can take risks, experiment, and tinker without worrying about affecting our daily activities.

In the future, I’m excited to keep building this lab. Whether it’s adding automation, testing cloud solutions, there’s always room to improve and learn. For now, though, I’m happy with this setup and looking forward to where it can take me next.

---

I created a page where I track the current status of my homelab with network diagrams, pictures and BOMs.

[Setup]({{< ref "/setup" >}} "Homelab Setup")