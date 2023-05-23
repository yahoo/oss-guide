---
layout: default
title: Copyright and Open Source
parent: Resources to Address Common Questions
nav_order: 2
---

> You are here for one of two reasons. You either want to understand more about the concept of _copyrights and how it relates to open source_ or you want to know what to put in the header of your code before you publish it. If you are here for the latter, skip [to the practical content](../resources/copyright.html#what-should-you-put-in-your-code) below.

# An Overview of Concepts

**Copyright** is a collection of rights protected by the government that applies to original works of authorship fixed in any tangible medium of expression. These rights ensure the copyright owner can decide who can copy the work. Yet this gets much more complicated.

What if there was no copyright protection? You author a work (i.e. write a novel, compose a song, create an app), and someone wants to use it without your permission. Perhaps the sovereign emperor of the land likes your novel and decides to publish it for you, (maybe without including your name or paying you). Perhaps someone who hacks into your computer decides to share an app you were planning on selling with the world (maybe before you were ready) and make money from it themselves. Technically you still have your property -- it was not stolen in the way a car is stolen. Your rights were infringed. Your agency was taken away. Copyright is the set of laws that protect your rights in these situations.

### What Does Copyright Protect?

Copyright laws are complicated. It's best to seek legal advice when it comes to details. This is not legal advice. With that said, you can find information online that helps explain copyright protection as it pertains to your jurisdiction. This [page](https://www.law.cornell.edu/uscode/text/17/106) lists rights protected by US copyright laws. For example, someone infringes your copyright if they copy your work to use it, modify it to make a derivative work, and/or distribute it, or the derived work without your consent. 

### What Does Copyright _Not_ Protect?

That's more complicated to address. There are a few carve-outs to note: Copyright does not protect ideas, processes, or concepts. You now see that source code, being protected by copyright, is viewed more as a literary work than a procedure. Copyright does not protect works that are trivial or too small for protection. e.g. No court will protect my claim that I authored the three word phrase "Roses are Red." Moreover, copyright protection excludes a category of infringement known as _fair use_ where someone copies a small part of your work for use we consider socially acceptable (e.g. including an excerpt in a book review). 

### Copyright and Open Source

When developers want to share their code and get others to use it, modify it, and distribute it, they should make explicit that they are doing this by intent. Why? By default if you say nothing, anyone taking your code is infringing your copyright. You should tell them it's okay to use and under what conditions. You do that in a [license](license.md). In a commercial transaction, someone pays you for license rights. In an open source project, you simply declare the license and now everyone will know they can use, modify, and redistribute your code under the license terms you specified.

### Open Source as a Legal Construct

Open source means different things to different people. From a legal perspective, open source refers to work that is shared under a license that complies with the [open source definition](https://opensource.org/osd) as managed by the [Open Source Initiative](https://opensource.org/). The open source definition specifies what makes an open source license open. Similarly, the [Free Software Foundation](https://www.fsf.org/) manages the [free software definition](https://www.gnu.org/philosophy/free-sw.html) which specifies the "four freedoms" that are sought by the Free Software movement.  

Note: There is overlap between _free software_ and _open source_, hence the acronym FOSS (or F/LOSS: adding _libre_ as a reminder that _free_ in this context refers to freedoms, not to the absence of cost). There are differences between the two definitions that they remain distinct. 

# The Pragmatics

## What Should You Put in Your Code
First read the section [Prepare your Publication](publishing/prepare.html#add-copyright-license-headers-to-your-code) page in this guide. Note: this guidance is for code we write at work. We never remove someone else's copyright statement. We only add our copyright statements to code we write. Let's cover four cases: 

1. Existing code that you are not modifying
1. Existing code that you are modifying
1. New code that we are publishing
1. New code that we are not planning to publish 

### Existing code that you are not modifying
If you've published open source code at one of the Yahoo legacy brands, your code will contain a copyright declaration that looks like: `Copyright 2014, Yahoo Inc.` or `Copyright 2014, Aol Inc.` etc.

Even though we are now `Yahoo`, you do not need to change the copyright notice text on code that was already published. The code previously published was marked correctly at the time. We don't have to change anything about that -- in fact it would be incorrect to change it. Copyright statements are not a freshness date, they are more like a timestamp.

### Existing code that you are modifying
When modifying one of our existing open source projects, you don't need to alter the copyright header. You _can_ remove the year since we no longer display years on the copyright line. Don't add a date range (e.g. 2012-2017). You _can_ update the copyright entity name from "Oath Inc." to "Yahoo Inc." if you prefer, but you don't have to.  If the copyright entity is "Verizon", "Verizon Media", or any other name belonging to Verizon, please update the entity name to one appropriate to Yahoo Inc.

### New code that we are publishing
_Yahoo Inc._ is the name we now use on the copyright header of new projects we publish. When you add a new file to an existing open source project or publish a new project, you'll add a copyright header to it. New code should have the following text block above to the top of each source code file that was written by employees (and not computer generated).

```
Copyright Yahoo Inc.
Licensed under the terms of the <SPDX license name> license. See LICENSE file in project root for terms.
```

### New code that we are not publishing
We do not require internal code to include a copyright statement. But it's a good idea to have one since internal code can become published external code (on purpose or by accident). Having an accurate copyright statement helps. It's good practice to add a header when creating new files. Also, some IDEs automatically put one in, so please configure it to use the right one. 

The header should contain a copyright statement (`Copyright Yahoo Inc.`) followed by the statement that indicates this is proprietary code (`All rights reserved.`). In the event we open source that code at a future date, we will then replace the `All rights reserved.` text with a license indicator that the code is licensed under an open source license (as shown above).

## Using your name on the copyright header
Company code should not list the engineer's name in the copyright notice. The engineer is the _author_ of the code, but code written for work is assigned to the company. Your code should only list your name as the copyright holder if you processed a copyright assignment with the OSPO and legal or if we have established an exceptional situation where this makes sense to do. Otherwise the code copyright should declare `Yahoo Inc.` as the copyright holder. It does not matter if code is published on a personal repo, as the copyright is an attribute of the code, not the repo.
