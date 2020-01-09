---
layout: default
title: What is a Contributor License Agreement?
parent: Resources to Address Common Questions
nav_order: 4
---

**A Contributor License Agreement (CLA)** is a legal document that defines the terms under which a license is granted by a contributor to an open source project. It is used to protect a project from future legal issues. For example: a contributor to an open source project might claim their code was never intended as, or authorized to be used as a contribution. This could be a form of trolling (injecting code then suing the project for copyright or patent infringement), or a clawback (a company asserts the contribution made by an employee was unauthorised). Although these behaviors are unexpected and rare, some have happened to open source projects. One way to mitigate these risks is to have every contributor sign a CLA. This clarifies that the contribution was authorized, and protects the project from some legal challenges.

### Do all open source projects have CLAs?

No. In practice, managing CLAs is cumbersome and creates about as many problems as it solves. Most open source projects operate assuming the above risks are sufficiently obscure that they won’t come up. Projects run by individuals rarely have a CLA. Large open source projects supported by tech companies or open source foundations tend to use CLAs to protect contributions. 
 
### Are there different types of CLAs?

Yes. Typical CLAs have the contributor assert they have the right to make the contribution (that they are not contributing someone else’s code without permission, or that they have legal authority to contribute their company’s code), then they specify the terms of the contribution (which often, but not always match the project license). The most common CLA text is based on the [Apache Software Foundation’s CLA](https://apache.org/licenses/contributor-agreements.html) (with a name replacement). Some entities create their own custom-CLA text with additional terms. Our experience with these custom text CLAs is they usually result in CLAs with restrictions that we are not willing to accept. 

There are alternatives to CLAs. These include the [Copyright Assignment Agreement (CAA)](https://www.fsf.org/bulletin/2014/spring/copyright-assignment-at-the-fsf) and the [Developer’s Certificate of Origin (DCO)](https://developercertificate.org/). CAA’s have the contributor assign the copyrights to the project (or to a Foundation), thus no longer being the copyright holder of the contribution. It is used by some projects to ensure the project has ownership of all the code. The DCO v1.1 pledges similar terms to a CLA, but is a declaration or pledge, not a license or legal agreement.

### Who signs the CLA?

The CLA is an agreement between the legal owner of the code being contributed and the legal owner of the open source project. When employed software developers write code for for work, their code is likely considered work-for-hire, and owned by the company who employs them. Thus the CLAs have to be signed by an authorized representative of the company. When employees contribute to projects that require a CLA to be signed, the engineer must get approval from the OSPO and be authorized to sign a CLA. If you are uncertain about the copyright status of the work (e.g. this is code you “wrote on the side”), please contact the OSPO and we’ll help resolve the uncertainty with you. 

Many organizations follow the Apache model and ask for two CLA documents to be signed. The ICLA is for the individual contributor and the CCLA is for the company contributor. Some organizations ask you to sign one, others ask that you sign both.  Before signing anything, ask the OSPO by opening a Jira ticket.

