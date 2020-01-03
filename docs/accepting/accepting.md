--
layout: default
title: Accepting Contributions
has_children: False
nav_order: 6
---

# Accepting Contributions to Open Source Projects

The Verizon Media Open Source Program Office (OSPO) provides services to help engineers at Verizon Media prepare code for external publication, promote projects, and build open source communities. If you are interested in open source collaboration, we are here to help. To get an overview of our program, visit the [OSPO Welcome Page](http://yo/ospo) intranet page, chat with us on our internal Slack channel (#opensource), or send an email to ospo@.

This page highlights the levels of support we provide to the open source projects we publish. 

### Step Zero: Planning for Success

You are here because you have published a project and people want to contribute to it. This is "business as usual" for open source, but once in a while you will run into something that gives you pause. When that happens, pause and ask the OSPO for help.

## Most Open Source Projects

When publishing a project, we include a [Contributing.md file](../publishing/publishing-template/Contributing.md) which informs people at large how we want them to work with us. Most of the time you'll want people to start with an issue. This allows people to discuss if we need a code fix at all. GitHub issues also invite other people to weigh in on the code -- since they might be working on the same issue in parallel. That said, as people become very comfortable with the flow of the project, often contributors jump right into issuing a pull request.

We allow our projects to self-govern and determine how much they insist on formality. 

## Set Clear Expectations

Our primary rule when it comes to the contribution process is to be very clear with the community. For example, you might not want contributions to the project. That's OK as long as you say so. Some projects are published with the intent to be available to read (maybe associated with a research paper), but not grow. Some projects might have been active and are no longer. We have a [version of the Contributing.md file](../publishing/publishing-template/contributing-static.md) you can modify and use for those projects. 

## Contributor Interactions

Open source projects often find themselves in debate about features and fixes. Some members might want to add features that other say create instability or impact performance. Sometimes people want to add a dependency that others don't want to have. This is normal and expected. However we insist that contributors interact professionally within the context of our projects. We ask people to disagree without being disagreeable (or worse).

Our projects will contain a [Code of Conduct](../publishing/publishing-template/Code-of-Conduct.md) that articulates what we expect and how we address situations that might come up. We don't want project members to address conduct issues in the project itself. Please loop in the OSPO. These matters unwravel quickly and are often best addressed by people outside of the day-to day project.

In addition, we ask our projects to be very welcoming to newcomers. Please add issues that newcomers can address as a way to get initiated into a project. Please be receptive to 'newbie' questions and respond in an informative and helpful tone. We are all new to every project once. 

## Contribution Licenses

Some open source projects require contributors to sign a [Contributor License Agreement](../resources/what-is-cla.md), also known as a CLA. In fact some open source projects require a copyright assignment agreement (which is like a CLA, but requires the contributor to _assign_ the copyrights to the project, rather than simply _license_ them to the project). Most open source projects, however, operate under the `inbound=outbound` rule that suggests the contributions to a project are licensed in the very same way the project itself is licensed. 

A project maintainer might get asked by a potential contributor to clarify if they need to sign a CLA to contribute to our projects. The answer is `no`. We used to require a CLA on our projects but over time we realized that they create as many problems as they solve. Now, we simply require that when a contributor issues a pull request, they do so with the declaration text we insert into the [pull request template](../publishing/publishing-template/PULL_REQUEST_TEMPLATE.md). 

If a contributor is unwilling to confirm they `have the authority necessary to make this contribution on behalf of its copyright owner.` then we don't want their contribution. Moreover, if the contributor indicates their contribution is being made without consent of the copyright owner, we certainly don't want their contribution. (Note: the author of this guide has been on a project where this happened.) CLAs exist to protect projects from the rare and unlikely situation that code is being contributed without permission. When this happens, it is usually due to an employee contributing their company's code to a project without permission from their company. We'd rather help the contributor get permission. Loop in the OSPO and we'll help if we can.

## GitHub permissions

When we create your project, we'll set up a permissions team in GitHub and add the GitHub IDs of all employees on the project into our GitHub org. Project maintainers may request that non-employees have commit privileges on projects. We'll add them as external collaborators. This way all members of our GitHub org are current employees, but non-employees can participate as full-fledged project participants. When people leave the company, we'll remove them from the org. We may convert them to an external collaborator, or remove them from the project -- that's up to the project maintainers to tell us.

## Measuring Contributions 

The OSPO manages a dashboard that tracks contributions across some of our open source projects. We recommend projects should set out initially to get between 10% to 30% of their contributions to be from external (i.e. non-employee) contributors. Over time, we'd hope (for many projects) this grows. As projects approach 50% of their contributions from external sources, we should discuss if we should have a foundation manage the project. Note, there's no hard and fast rule about this. But we do know the edge-cases: If none of the contributions are from non-employees, we're simply coding in public and need to evaluate why we're not getting endgagement. If all the contributions are from non-employees, we're simply hosting someone else's project. 
