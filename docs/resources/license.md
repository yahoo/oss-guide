---
layout: default
title: What is an Open Source License?
parent: Resources to Address Common Questions
nav_order: 3
---

**An Open Source License** is a legal document that defines the terms under which permission is granted by a rights holder to recipient. Open source licenses [listed here](https://opensource.org/licenses) allow software to be used, modified, and shared by anyone for any purpose with very few restrictions. 

### Do All Open Source Projects Have Licenses?

Yes. If a project lacks a license we can't consider it to be open source. The rights held by the code-owner were not licensed, thus using the code is an infringement. Some people publish code and assume this implies a license. Some projects add the name of a license inside a configuration file. One might argue this implies a license. But there's [caselaw](https://openjurist.org/817/f2d/72/effects-associates-inc-v-cohen) to suggest that courts expect to see these agreements in writing. So our practice is to avoid ambiguity and assumptions. If you don't see a license associated with the code, we can't assume it is open source. 

For this reason we put a license in the root of all of our code projects and add a license header in all code files. This makes it clear to others. When it comes to [using code](https://verizonmedia.github.io/oss-guide/docs/using/using.html#the-open-source-license), we like to see an explicit license (and will ask the project to make it clear if it was not already clear).

### Are All Open Source Licenses Alike?

All open source licenses grant rights and comply with the [open source definition](https://opensource.org/osd). But they differ in important ways from each other. We generally categorize licenses as being _permissive_ or _restrictive_. The former are relatively easy to comply with, the latter could impose more complications under many circumstances. Details matter, which is why our message to engineers is: *please ask whenever you see something that you are not 100% sure about.*

### Any Licenses Not Open Source?

Yes. The most common: Commercial licenses grant limited permissions in return for money. There's also a collection of licenses that are neither commercial nor open source. They operate similarly to open source in that they offer many rights and comply with much of the open source definition, but they are designed with some restrictions (e.g. limiting who can use the code, or for what purposes), and are thus not open source, but in many cases, readable source. There's also freeware, e.g. applications that are free to use for no cost, but you can't see or modify the source code. And of course, there are mock licenses, because... the Internet.
