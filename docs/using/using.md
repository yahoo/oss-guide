---
layout: default
title: Using Open Source Code
nav_order: 1
has_children: true
---

# Using Open Source Code

The Verizon Media Open Source Program Office (OSPO) provides services to help engineers at Verizon Media succeed with open source. If you are interested to learn more about open source, we are here to help. To get an overview of our program, vist the [OSPO Welcome Page](http://yo/ospo) intranet page, chat with us on our internal Slack channel (#opensource), or send an email to ospo@.

This page highlights issues engineering teams need to know about using open source code in their apps. 

### Step Zero: Planning for Success

Open source code is out there and available for you to use. It's better for you to use existing, widely-adopted open source code rather than reinventing a solution to a problem that’s already been solved. That assumes that the open source project you found is good code. Also, there are legal implications any time you use someone else’s code. 

As an engineer on a project, it’s your responsibility to make sure the code you use solves the intended problem. Be sure to consult with your architect and the tech council to determine if you should use open source code. The Verizon Media Open Source Program Office (OSPO) is here to help you with licensing questions. If you’re not sure about the implications of using open source code, ask the OSPO on slack at #opensource or email ospo@ with any questions.

## The Open Source License

 A **license** gives people permission to copy and use code that someone else wrote and published. There are many different open source licenses, but they all share the common goal: to allow others to use the code. The differences tend to be regarding the obligations people accept when they use the code. 
 
 **Please note**: If you find code without a license, assume you don't have the right to use the code. You can read it for pleasure and education, but you can't use the code. This means: If you want to use someone else's code, we need to make sure you have these rights. If they have not placed a license in their code project, you can always open an issue on the project and ask: "We'd love to use this code in a project of ours and wanted to make sure that you are OK with it. Would you be willing to add an OSI-approved license like the MIT or the Apache License to the project so that we know this is really open source?" This usually works, at least if the project is actively maintained.

When you find code on the internet that you want to use, you should first look for the license file. We typically find one of three types of licenses:

### Permissive Open Source Licenses 

Permissive licenses grant permission to use the code, imposing minimal obligations, and are relatively easy to comply with. The MIT, BSD, and Apache licenses are permissive. We come across many less common, but permissive licenses. Although details in each vary, we consider zLib, ISC, JSON to be permissive and are generally acceptable for almost all uses. Creative Commons Attribution (CC-BY) and SIL Open Font are usually acceptable when applied to content and fonts. Please ask if you see something less common.

We can use code licensed under permissive license. When that code is used in a [mobile app](../launching/mobile.md) or [binary product](../launching/binaries.md) we distribute, follow the product launch guidelines to ensure we have listed the appropriate credits in our product before launch.

### Restrictive Open Source Licenses 

Restrictive licenses grant permission to use the code, but they include terms that give us pause since they could pose additional work for us to comply with. Moreover, depending on how we're using the code, we might find it better for us not to use the open source code. Free Software licenses such a GPLv2, GPLv3, LGPLv2.1, or LGPLv3 impose obligations that may require us to make code available externally. MPL and EPL also contain reciprocal terms that are sometimes problematic. **Note**: problematic does not mean we can't use it at all, it means we need to make sure we are using it correctly. 

We can use code licensed under restrictive licenses, but we avoid including such code in distributed products, unless it is part of the product strategy. We avoid using restrictive licenses in mobile apps or in binary products. When it comes to embedded hardware, it's often the case we have to use restrictive licenses in the product, and will address this as an exceptional situation for Verizon Media. 

Speaking of exceptional situations, please read our guidance on the [AGPL License](../using/agpl.md).

### Source-available licenses

There are many types of licenses that grant permission to use the code, but contain terms that are not compliant with or were not reviewed by the Open Source Initiative (OSI). Some of these licenses are fairly low risk to us, but others are not. For example, CC-0, a declaration of public domain, Beerware, and even WTFPL on code sends the message that we're going to be OK using the code. Whereas other licenses pose interesting considerations and risks because they are designed to restrict certain usages or users. Techincally speaking, these are not Open Source licenses since they do not comply with the OSI definition of Open Source.

Recently, there has been a new batch of "source available" licenses that operate like open source for most people, or that eventually become open source, or that discriminate against some people or businesses. When it comes to anything like this, please ask the OSPO for guidance and advice. 
