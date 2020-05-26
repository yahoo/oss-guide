---
layout: default
title: Branding and Open Source
parent: Resources to Address Common Questions
nav_order: 8
---

## Branding and Open Source

How and where does the company name show up in open source projects? The page seeks to clarify the general approach we take toward addressing three aspects of this question. 

There are three places where the company name may show up in an open source project. We’ll discuss what we do in most cases, and how we determine what makes sense.
* **Copyright Declaration:** We will display the company name in the copyright declaration of an open source project. 
* **Project Name:** We will usually not put the company name (or any company name) in the project name. 
* **Code Location:** We will most often publish a project in a company branded GitHub location.

The **copyright declaration** statement will be found in the header of every source code file in projects we publish. It declares that the company is the copyright owner, and it publishes the project. This assertion sometimes gives people pause and is worth explaining. Generally speaking, copyrights are granted to the author of a work once the work is fixed into a medium. In nearly all work-for-hire situations, an employed author executes a copyright assignment to the company thus transferring the copyright to the company. The details of how and where this plays out are specified in the copyright assignment agreement that the employee signs. It is difficult to generalize without pointing to the specific agreement text and how it operates in different jurisdictions (as the laws do differ). 

So what normally goes into the copyright declaration? Either:
* The company name, for code published by the company.
* A person’s name, for personally owned code not assigned to the company.
* An entity name, for code assigned to an entity.

Unless there are special circumstances regarding the ownership of the code, code we publish from the OSPO will have the company name on the copyright declaration.

The **project name** _could_ include a company name, but this is less common and often not advised. If we wanted people to know a project is ours, we _could_ put our name in the project name, either explicitly or implicitly. For example: years ago Yahoo published YUI, the (“Yahoo User Interface”) as a JavaScript framework for people to use on their websites (that had nothing to do with Yahoo’s sites. Current JavaScript frameworks don’t carry a company name in their titles. Frankly it probably turns people away from a project making it seem that the company seeks to control it.

When publishing a project that is specifically associated with a product, you might find a natural name includes a company. This poses trademark and branding concerns. For example, if you published an open source project that manages your Yahoo Fantasy Sports team stats, you might want to call the project “Yahoo Fantasy Sports Team Stat Manager” but then the project presents itself as if it is a Yahoo product. Removing the “Yahoo” from the title, however, makes it appear that it could be used for a different fantasy product. If that’s not the case, consider something like “Stat Manager for Yahoo Fantasy Teams” which conveys a company name in the title. Better yet a more generic name.

We often publish projects on a **company named GitHub organization**. This is both a pragmatic way to direct people to new projects as well as a way to associate positive branding to the company as the project’s publisher and host. Sometimes we find it pragmatic to put a collection of projects into a community branded organization. For example, we published the Panoptes open source project in the Yahoo GitHub account here: https://github.com/yahoo/panoptes and we published the Screwdriver open source project in its own organization here https://github.com/screwdriver-cd. Why? Pragmatics. Panoptes is one repo whereas Screwdriver contains more than 70 repositories.

Considerations when it comes to branding:

* The project copyright is a legal matter. The name on the copyright declaration should be the name of the legal copyright holder. The copyright holder is the publisher of the project and the licensor.
* The project name should explain what the project is about, or at least give it a handy name. This is rarely a good place for a company name. When we publish projects we don’t want to say this is “ours” (belonging to the company exclusively) but that it is the expanded “ours” (used by the community who cares about the code, which includes people not employed by the company publishing the code).
* The location of the code is often a matter of branding and convenience. We publish the code in a location that is easy to convey to others -- usually best to start with the company’s GitHub organization and move it to its own organization if the project gets very complicated and operates independently of the company.

As with all general guidance, the above covers most cases and illustrates our approach to the issue. We ask engineers to raise questions, especially around cases with extraordinary circumstances.
