---
layout: default
title: Publishing a New Open Source Project
nav_order: 2
has_children: true
---

# Publish a New Open Source Project

The Verizon Media Open Source Program Office (OSPO) provides services to help engineers at Verizon Media prepare code for external publication, promote projects, and build open source communities. If you are interested in open source collaboration, we are here to help. To get an overview of our program, vist the [OSPO Welcome Page](http://yo/ospo) intranet page, chat with us on our internal Slack channel (#opensource), or send an email to ospo@.

This page highlights the steps you'll take when it comes to publishing company code as an open source project. We require you to follow this process to help prevent overdisclosure of information that could result in problems related to copyright, patent, trademark, or information we need to protect. As you plan your publication, remember that you must complete the review process and obtain OSPO approval before you publish any code externally.

### Step Zero: Planning for Success

Publishing a project is just the start of an open source project's life. Be sure to allocate developer resources to prepare and maintain the projects you publish. If you are not prepared to maintain an open source project, to promote it, respond to the community, or fix security alerts, we're not prepared to go though the steps of publishing the project. We don't want to pubish dead projects, so if you are not prepared for the long game, let's talk about why you want to publish code you don't want to support. 

Also before publishing a new project, let's find out if we could contribute your project (or parts thereof) to an existing open source project. It is usually better to contribute to an existing project that to create a brand new one. So let's really make sure this is what we, and the open source community needs. If we are invested and the community is very receptive, then let's proceed with this overview on how to launch a new project.

## [Step 1:](../publishing/prepare.md) Prepare Your Request

1. Propose a name for your project. We'll explain why some names won't work.
1. Add a [copyright notice](../resources/copyright.md) to the top of each source code file written by a Verizon Media employee. 
1. Prepare the repository for publication based on our [repository standard](../publishing/publishing-template/Spec-READ-AND-DELETE.html).
1. Create an open source branch (or separate repository) on an internal GitHub Enterprise instance and grant us read access so we can review your code.
1. Tell us where you want your project be hosted once you publish it. See the list of [Verizon Media managed external resources](../resources/resources-external.md).
1. Collect the list of employees who will need write access to the project once it's published
1. Visit the [Open Source Program Office](https://yo/opso) page on our intranet and create a JIRA ticket to initiate the review request.

## [Step 2:](../publishing/approval.md) Get Approvals

The OSPO handles most open source project approval steps for you. You can find the details on the [Approvals](../publishing/approval.md) page of this guide. Keep in mind there may be other approvals you should have in hand before coming to us, and these depend on the nature of the project you seek to publish. 

1. Make sure your manager has approved your plan to publish this project before you request a publication review. We have a step in the review process where we ask about other people at the company who may need to endorse this publication too.
1. If your project contains a novel idea that might be eligible for a patent, review the [patent submission process](https://yo/patent) on the intranet. Please complete the patent process before we publish the code. 
1. There are certain cases where you will complete information related to export control. Please review the [export control guide](https://yo/export) on the intranet to determine if your publication needs to go though this process.
1. If your project contains data (presumably scrubbed, anonymized, etc.), please review the [Global Privacy](https://yo/privacy) policies on the intranet and get their approval for publishing data sets.

## [Step 3:](../publishing/release.md) Release and Publicize                  

1. We'll create the external repository for your project and invites the internal team to the repo. We'll keep the repo private and we (or you) will configure the relevant settings, webhooks, etc.
1. You push the code to the new repository. Make sure you have a description, topics, and website link (if applicable) on the project.
1. You create a communications plan to promote your project in the external communication channels. We're here to help you promote your project by reviewing your blog posts, podcasts, or other presentation materials.
1. Once we're staged, we'll perform a final review and then turn the external repo from private to public.
1. Based on the comms plan, we'll publicize your project and encourage collaborations and contributions.


### Process

We're here for the details:

1. [Prepare Your Code](../publishing/prepare.md)
1. [Get Approval](../publishing/approval.md)
1. [Release and Publicize](../publishing/release.md)
  
We encourage you to check out other [resources](../resources/resources.md) for additional helpful information.

