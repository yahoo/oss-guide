---
layout: default
title: Approval
parent: Publishing a New Open Source Project
nav_order: 2
---

# Publishing Your Project: Step 2. Getting Approval

The Corporate Open Source Program Office (OSPO) is here to help engineers at our company prepare code for external publication, promote projects, and build open source communities. Our process is designed to set your project up for success, and to comply with relevant company policies. In Step 1, we show you how to [prepare your project](../publishing/prepare.md) to request OSPO approval. This page highlights the questions we will review with you to secure an approval for your publication request.

## Prepare Your Project Information

Include the answers to the following questions into a JIRA ticket assigned to the OSPO.

 1. Provide a repo link for the project you want to publish. 
 1. Where exactly do you want to publish the code? (e.g. github.com/?).
 1. Provide us (or link to) open source dependencies (and their licenses).
 1. What is the business value to the company for publishing this code? (related: Why did you write this code in the first place? At that time, did you plan that you'll be publishing it as an open source project?)
 1. Was all the code in this project authored by an employee? If not, please elaborate.
 1. Does your manager and project architect agree this project should be published?
 1. Have you completed a tech council review of the project (and its intent to be published)? See the Review Queue worksheet on our intranet for details about the review process.
 1. Where is this code used in production? (If this code is not in production, why not?)
 1. Has your team allocated time to support this code once it's published?
 1. Have you prepared the code according to the process detailed on the [Publish](../publishing/publish.md) page?
 1. Do you need any apps or webhooks enabled for the repo, such as Travis CI?
 1. Have you prepared a communications plan (e.g. blog post, podcast, meetup presentation) announcing this project? 
 1. Have you filed any patents related to the code you want to publish?
 1. Have you or the paranoids performed a security scan or review of your repo? If relevant, see the internal security help desk to request a Security Review.

## Review and Discussion 

Depending on the nature of your project and the responses to the questions above, we'll discuss any issues we find with your code publication. First we'll want to understand why you seek to publish this code and what you seek to gain from it. We seek to publish projects that add distinct value to the open source community, that solve problems that have not been solved before, that address needs that other people will also have, and that will attract positive attention to our engineering work. We avoid publishing projects that we don't actually use in production (if we can't convince our co-workers to use this code, why would we convince people who don't work with us all the time to use this code?). We avoid publishing code that solves a problem that has already been solved by an active open source community. We'd rather contribute to an existing effort if possible. 

We want to make sure that relevant architects and tech council members are aware of open source publications before they are published. They often have valuable insight to contribute that is better to include into the process before we publish code. It's not easy to redact code once published, so let's take time to make sure we published properly. We're not looking for perfect code (after all, we're going to invite people to give us bug fixes and suggestions). We're looking to make sure we don't regret the publication. We're also looking to avoid creating projects that never get any uptake or attention. 

Some projects are very straightforward and we'll approve them quickly. Our diligence is not intended to be a barrier, but a service. We want to help you ensure that you have everything ready for launching your new project. 

### Process

Once you have OSPO approval, proceed to [release](../publishing/release.md) your project. You can go back and review the [prepare your request](../publishing/prepare.md) step, or return to the [Publishing Overview](../publishing/publish.md).

