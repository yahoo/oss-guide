---
layout: default
title: What is an Open Source License?
parent: Resources to Address Common Questions
nav_order: 3
---

**An Open Source License** is a legal document that defines the terms under which permission is granted by a rights holder to recipient. Open source licenses [listed here](https://opensource.org/licenses) allow software to be used, modified, and shared by anyone for any purpose with very few restrictions. 

### Do All Open Source Projects Have Licenses?

Yes. If a project lacks a license we can't consider it to be open source. The rights held by the code-owner were not licensed, thus using the code is an infringement. Some people publish code and assume this implies a license. Some projects add the name of a license inside a configuration file. One might argue this implies a license. But there's [caselaw](https://openjurist.org/817/f2d/72/effects-associates-inc-v-cohen) to suggest that courts expect to see these agreements in writing. So our practice is to avoid ambiguity and assumptions. If you don't see an expressed license associated with the code, we can't assume it is open source. 

For this reason we put a license in the root of all of our code projects and add a license header in all code files. This makes it clear to others. When it comes to [using code](https://verizonmedia.github.io/oss-guide/docs/using/using.html#the-open-source-license), we like to see an explicit license (and will ask the project to make it clear if it was not already clear).

### Are All Open Source Licenses Alike?

All open source licenses grant rights that comply with the [open source definition](https://opensource.org/osd). But they differ in important ways from each other. We generally categorize licenses as being _permissive_ or _restrictive_. The former are relatively easy to comply with, the latter could impose more complications under many circumstances. Details matter, which is why our message to engineers is: *please ask whenever you see something that you are not 100% sure about.*

### Any Licenses Not Open Source?

Yes. The most common: Commercial licenses grant limited permissions in return for money. There's also a collection of licenses that are neither commercial nor open source. They operate similarly to open source in that they offer many rights and comply with much of the open source definition, but they are designed with some restrictions (e.g. limiting who can use the code, or for what purposes), and are thus not open source, but in many cases, readable source. There's also freeware, e.g. applications that are free to use for no cost, but you can't see or modify the source code. And of course, there are mock licenses that mock the idea of needing a license. Rare, and in most cases not really open source. See [Beerware](https://fedoraproject.org/wiki/Licensing/Beerware), [WTFPL](http://www.wtfpl.net/), and [Chicken Dance License](https://github.com/supertunaman/cdl) for examples.

### What About a Licence for Content?

Open _source_ licenses are designed to be used for _source_ code. Other content, such as images, documentation, or data sets might be better licensed using "content" licenses. The [Creative Commons Licenses](https://creativecommons.org/licenses/) provide a set of options that allow a copyright holder to share content under terms that are _similar_ to terms found in open source licenses. But note that some of the Creative Commons licenses do not comply with the open source definition. For example the [non-commerical](https://creativecommons.org/licenses/by-nc/4.0/) licenses restrict the _Fields of Endeavor_ clause in the OSD. Some data sharing projects leverage the [Open Database License](https://opendatacommons.org/licenses/odbl/index.html) or other licenses that are drafted to address the specific concerns related to data. 

### Still Confused About "Free" and "Open"

Open source licensing is not a simple topic. Here are a few thoughts to help you out as you read about this elsewhere:

* Often companies think of intellectual property as something they don't want to share. Whereas software engineers see value in sharing their code with peers. There are two levels of concerns (at least). One is letting someone else see what might be a secret. The other is giving up some control over an asset. These are complicated discussions. The license discussions will help clarify things. Open source licensing is not an wanton abandonment of rights, it's a method of managing trust. 
* The term `free` is best understood as emancipation, not cost. Think of the phrase `the code is free` to mean it has freedom and can be used without constraints of the owner, not that it lacks cost. Substitute `slave` for `code` in the above phrase if that helps. Open source does not attempt to prevent people from making money, but it does change the way a company could make money. This is often misunderstood. 
* The term `open` means more than _visible_, it means _unrestrained_. Often an entity may be willing to make some code visible, but still seeks to restrain what others can do with that code (e.g. you can see my code, but you can't use it in a way that might cause me to lose money.) Those cases cause confusion when people use the term `open` but really mean something more restricted.
