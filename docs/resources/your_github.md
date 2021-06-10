---
layout: default
title: Your GitHub Profile
parent: Resources to Address Common Questions
nav_order: 6
---

GitHub.com is a third party site we use to publish open source projects. Your GitHub.com account is your personal property that you might have created before joining the company and will continue to use after you leave. It's much like your Facebook, LinkedIn, Twitter, or any other social media account. Your personal use of personal social media is addressed in compnay's Employee Code of Conduct and other internal publications about external activities, communications, and intellectual property. There, you'll find the reasonable balance of concerns and resources to address questions. 

## GitHub Accounts

In the case of open source, things are slightly more complicated since on the one hand, your GitHub account is yours, on the other hand, your participation in our open source projects (the ones we host and the ones we ask you to contribute to) are part of your employment. All engineers have an account on our _internal_ GitHub Enterprise instance managed by our CIO team. Your account is provisioned and deprovisioned when you start and leave the company. You can't use that account for public open source work. Moreover, [GitHub's Terms of Service](https://help.github.com/en/github/site-policy/github-terms-of-service#b-account-terms) only allow you to have one free account, thus we do not want you to create a shadow disposable account for your work. Using a single account ensures your contributions are connected to you after you leave the company.

To participate in work-related open source projects:
1. Use your personal GitHub.com account. Create one if you don't have one. 
1. Register your user name (the whole URL) in your intranet profile (there's an `Edit Profile` button on the bottom of your profile page and a section for your GitHub ID).
1. [Add your company email address to your account](https://github.com/settings/emails). Please use this email address to make work-related commits. Why? because some projects track contributions by company and we'd like to celebrate the work you are doing. If you are reluctant to associate your work address with your personal account, please contact the OSPO to discuss a work-around.
1. [Activate two-factor authentication on your account](https://github.com/settings/security). This is a good security practice in general, and is required for all users who are given access to company orgs. **Make sure you save the recovery codes for your two-factor authentication**, we will not be able to help you if you lose your security device and get locked out of your account.
1. [Add an SSH key](https://github.com/settings/keys) to your account to make it easier to access GitHub.com from the command line.

In addition, we suggest you add additional profile information to your account:
1. **Your name** makes it easier for us to identify you.
1. **Our company** (We) helps us promote our tech brand by showing who our open source contributors are.
1. **An avatar**, either your real picture or something other than the default. 

We recognize that some people prefer not to use their name, image, or other information in public websites. We are here to help you succeed with open source and will help work around your preferences to find something that makes sense. 

A reminder: Do not post company code in your personal GitHub account without getting the code approved for publication first.

## GitHub Organizations

Company open source projects are released on GitHub.com and are published in a [compnay organization managed by the OSPO](../resources/resources-external.md). Do not publish any content to an organization you created without first consulting the OSPO. If you need to claim an organization name for a project we're about to publish, feel free to do so, but consult with the OSPO before publishing anything to it. 

It may be appropriate to publish code to your personal account. e.g. your code (not related to work).
1. Purely personal projects that have nothing to do with your job. (We'll help you determine if this is the case.)
1. Sample code for a talk at an event not related to the copmany.
1. Unofficial, experimental, or sample code.

Any code referenced from our documentation or blog post belongs in a [managed company organization](../resources/resources-external.md). If you're unsure whether a project should be published in a copmany organization or under your personal account, ask us.

If you are an company organization owner, please complete the organization profile properly.
1. **Profile**: All company organizations are required to have a profile picture with a brand logo, if you need help identifying the proper logo to use, or need to create a new logo for your project, contact the OSPO for help.  
1. **Member Privileges**: Disable the option to allow organization members to create repositories. Set Base Permissions to the lowest possible permission level to avoid giving members more access than is required. You can always create teams to give people more permissions to specific repos. Disable the option to allow members to change repository visibilities for this organization. Disable the option to delete or transfer repositories for this organization.
1. **Security**: Enable the option to require two-factor authentication for everyone in the organization.

### GitHub App Policy

Developer teams benefit from using certain GitHub Apps to improve their workflow and code quality. Certain apps, like Travis CI, are already installed on all of our GitHub organizations because they are widely used and require very basic permissions that don't pose much risk. However, some apps require certain permissions that create potential security risks. For this reason, we make sure apps don't request more permissions than we're willing to accept. If you have questions about the security concerns of granting certain permissions to GitHub Apps, contact the Paranoids.

#### How to Install a new GitHub App

1. Have the developer team go through the normal sign up process for the GitHub App. This will generate an email to the organization owners that someone is requesting to install an app.
1. This email will include a link to review the permissions the app is requesting. Contact Paranoids if you have questions about certain permissions that apps request.

The following lists provide examples of permissions that pose varying levels of risk.

1. Apps that request read-access to public information in repositories for code, issues, pull requests, commit status, etc. are accepted by default.
1. We consider apps that request read-access to non-public information on public repositories, such as webhooks and membership metadata, or that request write-access to comments, pull requests, and issues to be low-risk and usually acceptable.
1. Apps that request: Write-access to code repositories, Read/write access to private repositories, and Write access to non-public information like webhooks, membership, and emails to be moderate-risk and need to be reviewed by the Paranoids.
1. Apps that request: Admin control over repositories, Owner control over organization, or Read/write access to GPG keys are high-risk and need to be reviewed by the Paranoids. 

## GitHub Repos
**Request a Repo.** Request a new repository by contacting the OSPO (or opening a JIRA ticket on our queue). We stage code in a private repo, and expect these are going to be made public once approved. If you need a private repo for a long term project, please reach out to the OSPO to discuss. Note: [GitHub Pages](https://help.github.com/en/github/working-with-github-pages/about-github-pages#project-pages-sites) are always visible to the public, even if the repo is private. If you're staging code for release, run [Jekyll](https://jekyllrb.com/) to preview them locally.

**Archive a Repo.** Open source projects don't remain active forever. We archive repositories when they are no longer being worked on. The archive feature makes the repository read-only and prevents changes to the code, Issues, PR's, the wiki, and more. See our [Support Tier page](../promoting/support.md#tier-4-archived-projects) to review when repos are archived. In those cases, we ask maintainers to add a line at the top of the README to indicate that the project is no longer being maintained. 

There are two ways to archive a project: 1. using [GitHub's archive feature](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/about-archiving-repositories) or 2. moving it to an archive organization we created to reduce clutter in our organizations. Please ask the OSPO for help if you'd like us to archive a project.
