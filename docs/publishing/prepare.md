---
layout: default
title: Prepare Your Request
parent: Publishing a New Open Source Project
nav_order: 1
---

# Publishing your Project: Step 1. Prepare Your Request

The Yahoo Open Source Program Office (OSPO) is here to help engineers at Yahoo prepare code for external publication, promote projects, and build open source communities. Our process is designed to set your project up for success, and to comply with relevant company policies. This page highlights the initial steps you'll take when it comes to publishing company code as an open source project, namely preparing to make your publication request.

## Name Your Project

We suggest thinking about your project name early in the process. Before you select a name read these suggestions to familiarize yourself with common naming issues. Note, we're not going to name your project for you, but we're going to block you from publishing a project with a name that doesn't work. 

- We prefer descriptive names that clearly convey your project's purpose.
- Don't use a name that is protected by trademark. We'll connect you to our Trademark Search Request (TSR) process on the intranet if you are unsure about the protected status of the name you propose.
- Don't use a Yahoo brand name.
- Avoid using a third-party brand name. In certain cases you can use them as descriptors. For example, you can use "Test Libraries for Java" but don't call something "Java Test Libraries."
- Don't use cumbersome names. Name your project as if you expect it to be widely adopted.
- Don't use unclear names. e.g. "Foundation Server" 

## Select the Appropriate License

The OSPO is here to help you license your project. For an overview of open source licenses, check out [What is an open source license](../resources/license.html)? We prefer publishing code under permissive open source licenses such as Apache License 2.0, BSD 3-Clause, or MIT. We publish under other licenses when the specifics of the project warrant their use. Specifically:

- We match the license to the project's needs. We usually consider the Apache 2.0 License as our go to option. When publishing code to certain communities, we may opt to use a license that is more consistent with the rest of the community. e.g. Node.JS projects tend to be licensed under the terms of the MIT license. 
- We may publish sample code under the zLib or MIT-0 licenses because they don't require users to carry attribution forward. This makes sense for sample code that users might include in their apps.
- Some projects contain dependencies that require us to use a GPL license in the code. That's fine too. 

## Add Copyright License Headers to Your Code

All code files must have a properly formatted Copyright and License header. 

- The Copyright header consists of two parts: the word _Copyright_ and the copyright holder who published this work. 
- The License header consists of the phrase _Licensed under the terms of the {NAME} License. See LICENSE.md file in the project root for terms._

More do's and don'ts:
- Use the language-appropriate delimiter for your comment block (e.g. // or /* text */ etc.)
- Don't add a symbol next to the word _Copyright_ (e.g. © or (c)). It's redundant.
- Don't add or update the year of publication. We don't need to include the year of publication. Technically it is intended to start the timer for copyright expiration. Often people see it as a freshness date. It's not needed.
- Don't add "All rights reserved." at the end of the line. The license will un-reserve some of those rights. Use "All rights reserved." for closed source code.
- We're a complicated company, so many groups get stuck on who the copyright holder is for their code. It is Yahoo Inc., Oath Inc. Yahoo, or something else. We'll guide you as to the appropriate choice.
- Under normal circumstances, the copyright holder will be the name of our company, not the name of the developer who first authored the code.

This part can get surprisingly complicated, especially when it comes to code projects with blended code set from different companies. Read more details about [Copyright and License headers](../resources/copyright.html). Please review the information on the [Contribute to Apache Software Foundation projects](../contributing/recordkeeping.html#contribute-to-apache-software-foundation-asf-projects.html) help page for contributions to ASF managed projects. Better yet, talk to us and we'll work with you to get to the right header text.

## Scrub Your Repository

1. Remove all internal dependencies or references in your code and documentation. This includes any references to server names, binaries, databases, or internal communication addresses. Remove references to internal directory conventions. Also remove comments or documentation references to JIRA links, internal code names, and anything else that wouldn't make sense to external developers.
1. Remove embarrassing content. e.g. curse words, references to poor coding practices ("stolen from"), jokes, and anything that would be embarrassing if it were made public.
1. Perform any paranoid-required code review for vulnerabilities in static code or dependencies
1. Remove all embedded credentials, passwords, or other secrets that may be in the code or a configuration file. (Note: we expect secrets to be managed outside of source code, but we ask you to check nonetheless. We'll check too.) 

## Prepare Your Repository

Please refer to the [repository standard](../publishing/publishing-template/Spec-READ-AND-DELETE.html) requirements for repository meta-files. Then push your code to a repository or branch and grant us read access.

### Process
Once you've finished these preparations, it's time to open a JIRA ticket with the OSPO and [get approval](../publishing/approval.html). You can also go back to the [Publishing Overview](../publishing/publish.html) page.
