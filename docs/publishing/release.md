---
layout: default
title: Release
parent: Publishing a New Open Source Project
nav_order: 3
---

# Publishing your Project: Step 3. Release and Publicize

The Verizon Media Open Source Program Office (OSPO) is here to help engineers at Verizon Media prepare code for external publication, promote projects, and build open source communities. Our process is designed to set your project up for success, and to comply with relevant company policies. In Step 2 we outlined the Open Source project publication [approval](../publishing/approval.md) process. This page highlights the process for releasing and publicizing your project.

## Publication Process

1. The OSPO reviews projects during our open office hours (Monday mornings at 9:00 AM Pacific time). If the OSPO receives your project after 9:00 AM on Monday, we will review it the following Monday.
1. If we approve your project for publication, we schedule your launch (typically on Tuesday at 11:00 AM Pacific time). 
1. If you'd like to schedule for a different day or time, indicate your preferred day and time in the ticket.
1. At the designated time, we'll change the repo settings to public.
1. After about two weeks, we'll review project settings and reduce admin permissions to write permissions for project committers. If you need admin rights, contact the OSPO.

## Promotion Process

We will publish your blog post announcing the new project at the time specified by our communications plan. Some projects seek to soft-launch and be public for a few weeks before we blog about it. Other projects schedule their blog post and publication to be synchronized with a conference presentation or other relevant launch event. As long as we have a reviewed and approved communications plan in place, we can accomodate your needs.

You may opt to set up a project website, documentation pages, or community group (e.g. using GoogleGroups, Gitter, Slack, etc.). We can provide you with our [Awesome Project website template](https://yo/open-source-website) on our intrate, which you can use to create your community site, but we expect that you and the community you develop will maintain the site. Note: before launching a community website, designing a project logo, or registering a project domain name, please work with the OSPO on a communications plan so that we can get the proper approval and registrations in place first.

## First Quarter

During the first three month after publication, we expect the project team to be active in promoting and supporting their new open source project. Projects that "dump and run" tarnish our reputation and make the engineers on the team look like they only published code to add a bullet to a resume, but not to grow an open source community. New projects can generate a lot of positive buzz on social media communities, but this will only sustain if the project team is visible and active. 

During the first three months, we'll help you promote your project with a blog post, invite you to talk about it on our podcast, and review your presentation for a relevant meetup or conference. After that, we'll make ourselves available to you for consultation about growing your community. If we have the resources and your project is on our tier 1 support list, we'll continue to support your community management needs.

## Ongoing Support from the OSPO

In rare situations you may encounter a problem in your open source community that requires the OSPO to step in and help. Occasionally a community member may behave outside the bounds of our conduct code. A question may come up that requires our legal, PR, or security team to step in before we address it. In these and similar cases, please contact the OSPO right away so we can help. Also, we'll notify you if we get a security alert from GitHub or a Bug Bounty report related to your project. We expect that you will attend to these alerts quickly.

## Accepting Contributions

After you have published your project, it's time to start accepting contributions from external contributors.
- Specify the types of contributions you want to accept (bug fixes, new features, improvements, etc.) in the [Contributing.md](../publishing/publishing-template/Contributing.md) file.
- Create a [PULL_REQUEST_TEMPLATE.md](../publishing/publishing-template/PULL_REQUEST_TEMPLATE.md) file to prompt contributors to provide the required information. Use our example template as a starting point.
- If you use our PULL_REQUEST_TEMPLATE, contributors do not have to sign a CLA with us. The template contains what is, in effect, a DCO. 
- To encourage positive community interactions, we recommend you follow the [Issue Triage](../resources/issue-triage.md) guidelines.

When projects first launch we expect all the contributors and committers on the project are Verizon Media employees. We believe one measure of success is how many contributors are not employees. We encourage you to see and support external contributors to our projects. Contact the OSPO to grant committer access. We will include Verizon Media employees in the GitHub org and will specify non-employees as external collaborators. 

## Project Hospice 

All projects eventually come to their end and we want to make that process as gentle and dignified for the community involved as we can. By practice, we typically keep open source projects on GitHub and mark them as Archived. This allows community members to view and fork the code while we've made it clear that we are not investing effort in the project anymore. We will move a project to archive state if we no longer have an employee who maintains the project or if the maintainers tell us they have abandoned the project. Projects with security alerts that remain open for a month will be archived.

### Process

This concludes the three step [prepare](../publishing/prepare.md), [approve](../publishing/approve.md), and release process. You can return to the [Publishing Overview](../publishing/publish.md), or review additional [resources](../resources/resources.md) in this guide.
