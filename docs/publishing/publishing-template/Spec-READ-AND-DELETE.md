---
layout: default
title: Publishing Template
nav_order: 4
parent: Publishing a New Open Source Project
has_children: true
---

# Verizon Media Open Source Skeleton Specification

A compliant README must satisfy all the requirements listed below. **Delete this file before publishing project to public repository.**

> This specification provides instructions on how to adapt the [Verizon Media Open Source Skeleton](https://git.<company>.com/Open-Source/Verizon-Media-Open-Source-Skeleton) to a designated project.

**Requirements:**
  - Be a valid Markdown file.
  - Sections must appear in order given below. Optional sections may be omitted.
  - Sections must have the titles listed below, unless otherwise specified.
  - Must not contain broken links.
  - If there are code examples, they should be linted in the same way as the code is linted in the rest of the project.

## Table of Contents

_Note: This ToC is only a navigation guide for this document, don't use it in your own project. See ToC instructions below._

- [Sections](#sections)
  - [Title](#title)
  - [Banner](#banner)
  - [Badges](#badges)
  - [Short Description](#short-description)
  - [Long Description](#long-description)
  - [Table of Contents](#table-of-contents-1)
  - [Security](#security)
  - [Background](#background)
  - [Install](#install)
  - [Usage](#usage)
  - [Extra Sections](#extra-sections)
  - [API](#api)
  - [Maintainers](#maintainers)
  - [Contribute](#contribute)
  - [License](#license)

## Sections

### Title
**Status:** Required.

**Requirements:**
The title must match the repository name; if names don't match, there must be a note in the [Long Description](#long-description) explaining why.

### Banner
**Status:** Optional.

**Requirements:**
- Must not have its own title.
- Must link to local image in current repository.
- Must appear directly after the title.

### Badges
**Status:** Optional.

**Requirements:**
- Must not have its own title.
- Must be newline delimited.

**Suggestions:**
- Use http://shields.io or a similar service to create and host the images.

### Short Description
**Status:** Required.

**Requirements:**
- Must not have its own title.
- Must be less than 120 characters.
- Must start with `> `
- Must be on its own line.
- Must match GitHub's description

### Long Description
**Status:** Optional.

**Requirements:**
- Must not have its own title.
- If any of the folder, repository, or package manager names do not match, there must be a note here as to why. See [Title section](#title).

**Suggestions:**
- If too long, consider moving to the [Background](#background) section.
- Describe the project in broad terms with 1-2 paragraphs.
- **Do not** include detail of the module's routines or methods, lengthy code examples, or other in-depth material, save this for later sections
- Someone who's slightly familiar with the project should be able to refresh their memory without hitting "page down". As your reader continues through the document, they should receive a progressively greater amount of knowledge.


### Table of Contents
**Status:** Required; optional for READMEs shorter than 100 lines.

**Requirements:**
- Must link to all Markdown sections in the file.
- Must start with the next section; do not include the title or Table of Contents headings.
- Must be at least one-depth: must capture all `##` headings.

**Suggestions:**
- May capture third and fourth depth headings. If it is a long ToC, these are optional.

### Background
**Status:** Required (if not included in long description above).

**Requirements:**
Answer the following questions:
- What was your motivation for creating this project?
- How is this project different or better than competitors?
- What scenarios are ideal for this project?
- What external references could help the reader understand the purpose of this project better?

### Install
**Status:** Required by default, optional for [documentation repositories](#definitions).

**Requirements:**
- Basic information about prerequisite knowledge the user should have before installing (with relevant external references).
- Dependency information with external references for where to install them (if not provided in this readme).
- The commands the user will need to run to install and setup the project
- Any configuration options or tips that will help the user with the project.- Code blocks that provide step-by-step instructions on how to install.

**Suggestions:**
- Link to prerequisite sites for programming language.
- Include any system-specific information needed for installation.
- If there is no code in the module - for instance, a document-based module - this section is not required.
- An `Updating` section would be useful for most packages, if there are multiple versions which the user may interface with.

### Usage
**Status:** Required by default, optional for [documentation repositories](#definitions).

**Requirements:**
- Code blocks that illustrate common usage.
- If CLI compatible, code blocks that demonstrate common usage.
- If importable, code blocks that demonstrate both import functionality and usage.

**Subsections:**
- `CLI`. Required if CLI functionality exists.

**Suggestions:**
- Cover basic choices that may affect usage: for instance, if JavaScript, cover promises/callbacks, ES6 here.
- If relevant, point to a file that can be run to use the code
- If there is no code in the module - for instance, a document-based module - this section is not required.

### Security
**Status**: Optional.

**Requirements:**
- Include this if there are any important security implications the user should be aware of.

### Extra Sections
**Status**: Optional.

**Requirements:**
- None.

**Suggestions:**
- This should not be called `Extra Sections`. This is a space for 0 or more sections to be included, each of which must have their have titles.
- This should contain any other sections that are relevant, placed after [Usage](#usage) and before [API](#api).

### API
**Status:** Optional.

**Requirements:**
- Describe exported functions and objects.

**Suggestions:**
- Describe signatures, return types, callbacks, and events.
- Cover types covered where not obvious.
- Describe caveats.
- If using an external API generator (like go-doc, js-doc, or so on), point to an external `API.md` file. This can be the only item in the section, if present.

### Maintainer(s)
**Status**: Optional.

**Requirements:**
- Must be called `Maintainer` or `Maintainers`.
- List maintainer(s) for a repository, along with one way of contacting them (e.g. GitHub link or email).

**Suggestions:**
- This should be a small list of people in charge of the repo. This should not be everyone with access rights, such as an entire organization, but the people who should be pinged and who are in charge of the direction and maintenance of the repository.
- Listing past maintainers is good for attribution, and kind.

### Contribute
**Status**: Required.

**Requirements:**
- State where users can ask questions.
- State whether PRs are accepted.
- List any requirements for contributing; for instance, having a sign-off on commits.

**Suggestions:**
- Link to the contributing or contribute file.
- Be as friendly as possible.
- Link to the GitHub issues.
- Link to a Code of Conduct.
- A subsection for listing contributors is also welcome here.

### License
**Status:** Required.

**Requirements:**
- State license full name or identifier, as listed on the  [SPDX](https://spdx.org/licenses/) license list. 
- State license owner.
- Must be last section.

**Suggestions:**
- Link to longer License file in local repository.
