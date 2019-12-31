---
layout: default
title: Copyright and Open Source
parent: Resources to Address Common Questions
nav_order: 2
---

> You are here for one of two reasons. You either want to understand more about the concept of _copyrights and how it relates to open source_ or you want to know what to put in the header of your code before you publish it. If you are here for the latter, skip [to the practical content](../copyright.md#what-should-you-put-in-your-code) below.

**Copyright** is a collection of rights protected by the goverment that applies to original works of authorship fixed in any tangible medium of expression. These rights ensure the copyright owner can decide who can copy the work. Yet this gets much more complicated.

Consider a world without copyright protection. You author a work (i.e. write a novel, compose a song, create an app), and someone wants to use it without your permission. Perhaps the sovereign emperor of the land likes your novel and decides to publish it for you, (maybe without including your name or paying you). Perhaps someone who hacks into your computer decides to share an app you were planning on selling with the world (maybe before you were ready) and make money from it themselves. Now, techincally you still have the work -- it was not stolen in the way a car or wallet is stolen. Your rights were infringed. Your agency was taken away from your work. Copyright is the set of laws that protect you in these situations.

### What Does Copyright Protect?

Copyright laws are rather complicated. It's best to seek legal advice when it comes to details. This is not legal advice. With that said, you can find information online that helps explain copyright protection as it pertains to your jurisdiction. For example this [page](https://www.law.cornell.edu/uscode/text/17/106) lists rights protected by US copyright laws. For example, someone infringes your copyright if they copy your work to use it, modify it to make a derivative work, and/or distribute it, or the derived work without your consent. 

### What Does Copyright _Not_ Protect?

That's more complicated to address. There are a few carve-outs to note: Copyright does not protect ideas, processes, or concepts. You now see that source code, being protected by copyright, is viewed more as a literary work than a procedure. Copyright does not protect works that are trivial or too small for protection. e.g. No court will protect my claim that I authored the three word phrase "Roses are Red." Moreover, copyright protection excludes a category of infringment known as "fair use" where someone copies a small part of your work for use we consider socially acceptable (e.g. including an excerpt in a book review). 

### Copyright and Open Source

When developers want to share their code and get others to use it, modify it, and distribute it, they should make explicit that they are doing this by intent. Why? By default if you say nothging, anyone taking your code is infringing your copyright. You should tell them it's okay to use and under what conditions. You do that in a [license](../license.md). In a commercial transaction, someone pays you for license rights. In an open source project, you simply declare the license and now everyone will know they can use, modify, and redistribute your code under the license terms you specified. 

### Open Source as a Legal Construct

Open source means different things to different people. From a legal perspective, open source refers to work that is shared under a license that complies with the [open source definition](https://opensource.org/osd) as managed by the [Open Source Initiative](https://opensource.org/). The open source definition specifies what makes an open source license open. Simiarly, the [Free Software Foundation](https://www.fsf.org/) manages the [free software definition](https://www.gnu.org/philosophy/free-sw.html) which specifies the "four freedoms" that are sought by the Free Software movement.  

There is considerable overlap between free software and open source, hence the merged acronym FOSS (or F/LOSS: adding _libre_ to remind people that the term _free_ in this context refers to freedoms, not to the absense of cost). There are sufficient differences between the two definitions that they will remain uncombined. 

## What Should You Put in Your Code

You already read the section [Prepare your Publication](publishing/prepare.html#add-copyright-license-headers-to-your-code) page in this guide, but you have more questions. Note: this guidance is for code we write. We never remove someone else's copyright statement. We only add our copyright statements to code we write.

Let's cover four cases: 

1. Existing code that you are not modifying
1. Existing code that you are modifying
1. New code that we are publishing
1. New code that we are not planning to publish 

#### Existing code that you are not modifying
If you've published open source code at one of the Verizon Media legacy brands, your code will contain a copyright declaration that looks like:

> Copyright 2014, Yahoo Inc.

or
> Copyright 2014, Aol Inc.

Even though we are now called `Verizon Media`, you do not need to change the copyright on code that was already published. The code previously published was marked correctly as published by the entity that existed at the time. It's factually correct to say that in 2014, a project was published that had Aol's or Yahoo's copyright on it. We don't have to change anything about that -- in fact it would be incorrect to change it. Copyrights statements are not a freshness date, they are a timestamp.

#### Existing code that you are modifying
When modifying an existing open source project, don't alter the copyright header. But you can update the year if your modifications are significant. Don't add a date range (e.g. 2012-2017). The publication date starts a virtual clock for when the copyright expires (in many decades from now). So updating the year has an effect that most of us will not live to see. The final date is the only one that counts. So you don't have to change the date, but you can. However, if you change the date to the current year, you should change the copyright name to our current company name (`Verizon Media` which is also `Oath Inc.`).

#### New code that we are publishing
Please note: `Oath Inc.` is still the name for Verizon Media and the proper copyright holder for code published in 2019. This will likely change to Verizon or Verizon Media. But it's okay if we're not 100% exact since [US copyright law](https://www.law.cornell.edu/uscode/text/17/401) allows the copyright holder to use 
> `the name of the owner of copyright in the work, or an abbreviation by which the name can be recognized, or a generally known alternative designation of the owner.` 

_Verizon Media_ is our `generally known alternative designation`.

When you add a new file to an existing open source project or publish a new project, you'll add a copyright header to it. We now all work for Verizon Media (or one of its subsidiaries), so new code should be published declaring:

> Copyright 2019, Verizon Media,
> Licensed under the terms of the <`SPDX name for the project license`> license . See LICENSE file in project root for terms.

Add the text block above to the top of each source code file that was written by employees and is not computer generated.

#### New code that we are not publishing

We do not require internal code to include a copyright statement. But it's a very good idea to have one since internal code sometimes becomes published external code (on purpose or by accident). Having an accurate copyright statement helps. It's a good practice to add a header when creating new files. Also, some IDEs automatically put one in, so please configure it to put the right one in. 

The header should contain a copyright statement (`Copyright 2019, Verizon Media`) followed by the statement that indicates this is proprietary code (`All rights reserved.`). In the event we open source that code at a future date, we will then replace the `All rights reserved.` text with a license indicator that the code is licensed under an open source license (as shown above).

#### Additional Information
Internal code should not list the engineer's name as the copyright holder. The engineer is the _author_ of the code, but code written for work is assigned to the company. A person's name is the appropriate copyright holder on code written by people who are self-employed or who publish code not assigned to the company (it was determined to be outside the parameters of the assignment) or who have processed a copyright assignment with their company where the company re-assigns the code back to the employee. External code should only list your name as the copyright holder if you processed a copyright assignment. Otherwise the code copyright should declare `Verizon Media` as the copyright holder. It does not matter if code is published on a personal repo, as the copyright is an attribute of the code, not the repo.


