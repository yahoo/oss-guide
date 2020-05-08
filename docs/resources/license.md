---
layout: default
title: What is an Open Source License?
parent: Resources to Address Common Questions
nav_order: 3
---

**An Open Source License** is a legal document that defines the terms under which permission is granted by a rights holder to the recipient. Open source licenses [listed here](https://opensource.org/licenses) allow software to be used, modified, and shared by anyone for any purpose with very few restrictions. 

### Do All Open Source Projects Have Licenses?

Yes. If a project lacks a license we can't consider it to be open source. The rights held by the code-owner might not be licensed, thus using the code may be an infringement. Some people publish code and assume this implies a license. Some projects add the name of a license inside a configuration file. One might argue this _implies_ a license. But there's [legal precedent](https://h2o.law.harvard.edu/cases/4070#r[7]) to suggest that courts wish to see copyright agreements clarified in writing ("Section 204's writing requirement [for transfer of copyright] is not unduly burdensome"). We seek to avoid ambiguity and assumptions. If you don't see an expressed license associated with the code, we can't assume it is open source. 

For this reason we put a license in the root of all of our code projects and add a license header in all code files. This makes it clear to others. When it comes to [using code](https://verizonmedia.github.io/oss-guide/docs/using/using.html#the-open-source-license), we like to see an explicit license (and will ask the project to make it clear if it was not already clear).

### How Do We Pick Which License To Use?

By default we use the Apache License 2.0 since it is permissive (allowing people to use the code with very few restrictions) and handles patents in a way we think is clear and fair. It is also widely used and understood. We also use the New BSD and MIT licenses, usually in cases where the community norm is to use those licenses (e.g. Node.JS modules are nearly all licensed MIT, so we'll use that too). Our intent is to be clear, grant permissions, and fit in with the community we're operating in.

There are times we are required to, or it is ideal to, license code under other licenses. For example, if we are extending code licensed under the GPL license, we'll license our derivative work under GPL in compliance with the terms of the license. In those cases, please see [our GPLCC declaration](https://developer.yahoo.com/opensource/docs/GPL-Cooperation-Commitment.html) assuring that if someone violates the terms of our GPL licensed code, we'll extent to them an opportunity to cure and reinstate their license.  

### Are All Open Source Licenses Alike?

All open source licenses grant rights that comply with the [open source definition](https://opensource.org/osd). But they differ in important ways from each other. We generally categorize licenses as being _permissive_ or _restrictive_. The former are relatively easy to comply with, the latter could impose more complications under many circumstances. There will be instances where we will or will not _use_ code based on the license. There will be instances where we will or will not _contribute to a project_ based on the license. Situational details matter such that we'll say yes in some cases, no in others. Our role as an OSPO is in part to help educate our engineers about these issues, but ultimately to determine a proper course of action for a given situation. Our consistent message to engineers: *please ask whenever you see something that you are not 100% sure about. We will help inform and decide what makes the most sense in a given situation.*

### Are Any Licenses _Not_ Open Source?

Yes. The most common are commercial licenses that grant limited permissions in return for money. But there are others that offer openness and freedoms, but are still not technically _open source_.
* Source-Available licenses are neither commercial nor open source. They operate similarly to open source in that they offer many rights and comply with much of the open source definition, but they are designed with some restrictions (e.g. limiting who can use the code or for what purposes). 
* There is a new category of license that is perhaps a subcategory of _Source-Available_ but worth nothing. These are collectively being called [Ethical Source Licenses](https://ethicalsource.dev/licenses/) and include the [The Hippocratic License 2.1](https://firstdonoharm.dev/).
* Freeware licenses are used for applications that are free to use (i.e. no cost), but you can't see or modify the source code.
* The [Unlicense](https://unlicense.org/) is not actually a license, but a declaration of Public Domain status. 
* Mock licenses are written to mock the idea of open source licenses. These are uncommon and in most cases do not comply with OSD. Moreover, they are typically poorly drafted from a legal perspective. [Beerware](https://fedoraproject.org/wiki/Licensing/Beerware) is a relatively old example. [WTFPL](http://www.wtfpl.net/) comes up once in a while, shocking a unsuspecting reviewer with a curse word. The [Chicken Dance License](https://github.com/supertunaman/cdl) captures this category well.

As with any license questions (especially those not approved by OSI), please ask the OSPO for guidance about the license terms and how it impacts your use of or contributions to the project. We will address each question in context of the specific use case.

### What About a Licence for Content?

Open _source_ licenses are designed to be used for _source_ code. Other content, such as images, documentation, or data sets are often better licensed using _content_ licenses. Some examples:
* The [Creative Commons Licenses](https://creativecommons.org/licenses/) provide a set of options that allow a copyright holder to share content under terms that are _similar_ to terms found in open source licenses.  
* Some data sharing projects leverage the [Open Database License](https://opendatacommons.org/licenses/odbl/index.html) or other licenses that are drafted to address the specific concerns related to data. 
* Some fonts are licensed under an open font license such as the [SIL Open Font License 1.1](https://opensource.org/licenses/OFL-1.1).

Note: some open content licenses do not comply with the open source definition. For example the [Creative Commons non-commerical](https://creativecommons.org/licenses/by-nc/4.0/) licenses restrict the _Fields of Endeavor_ clause in the OSD. Thus technically we do not call this _open source_ since it is neither _source_ and it falls shy of the formal definition of _open_ with respect to open source.

### Still Confused About "Free" and "Open"

Here are a few thoughts to help you out as you read about this elsewhere:

* Often companies think of intellectual property as something they don't want to share. Whereas many software engineers see value in sharing their code with peers. There are two levels of concerns (at least). One is letting someone else see what might be a secret. The other is giving up some control over an asset. The license discussions will help clarify things. Open source licensing is not an wanton abandonment of rights, it's a method of managing trust. 
* The term `free` is best understood as emancipation, not cost. Think of the phrase `the code is free` to mean it has freedom and can be used without constraints of the owner, not that it lacks cost. Substitute `slave` for `code` in the above phrase if that helps. Open source does not attempt to prevent people from making money, but it does change the way a company could make money. This is often misunderstood. 
* The term `open` means more than _visible_, it means _unrestrained_. Often an entity may be willing to make some code visible, but still seeks to restrain what others can do with that code (e.g. you can see my code, but you can't use it in a way that might cause me to lose money.) Those cases cause confusion when people use the term `open` but really mean something more restricted.
