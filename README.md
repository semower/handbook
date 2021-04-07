# HOT Humanitarian Data Handbook

## What is this and why?
This repository is an experiment in using a [Git](https://en.wikipedia.org/wiki/Git) repository&mdash;for the moment on [GitHub](https://github.com)&mdash;as an open-by-default tool for the [Humanitarian OpenStreetMap Team (HOT)](https://hotosm.org) Humanitarian Data team.

It's intended to provide a single starting point for information, explanations, and resources needed to understand and manage our projects. 

__"Open by default"__ means everything here is open to _the entire world_ unless there is a specific reason to restrict access (normally personally identifiable, sensitive, or private information). It is intended to be shared and collaboratively edited by anyone in or outside of the host organization.

Why not a wiki, or Google Docs? Mostly on the theory that the fork-and-pull-request workflow of Git strikes a good balance between openness (anyone can fork and/or submit a pull request) and manageability (no one has to accept pull requests, and they're very transparent and reversible).

We've taken some inspiration from [GitLabs' handbook](https://about.gitlab.com/handbook/handbook-usage/); that company has taken a remarkably open approach to their internal workings, in part in response to some of the same challenges. 

## How does it work?
It's basically a Git repo full of [Markdown](https://en.wikipedia.org/wiki/Markdown) documents (like the one you're reading right now) that explain projects and processes, and contain links to relevant resources. For a reader, it's not much different from a wiki; the difference lies in how edits are proposed, merged, tracked, and managed. [Here](https://about.gitlab.com/handbook/handbook-usage/#wiki-handbooks-dont-scale) is a discussion of the advantages of a Git repo over a Wiki.

### How can I use it?
You need some familiarity with the basics of:
- Git: cloning, committing, forking/branching, creating pull requests, and merging.
- Markdown: Creating text with styling, links, and embedded images.

[Here are some learning resources for these tools](Resources/learning_resources.md).

#### Getting started by editing a page
- Click around the links available from this very page! Again, it looks and works like a Wiki; it's the editing that is different.
- Get an account on GitHub (free to sign up).
- Clone this repository. Open it up in your file manager on your computer; you'll note that the folder structure mirrors the link structure (you can figure out where any document in the repo is by examining the URL of the link to it).
- Pick a document you want to modify.
- Fork the repo.
- Make your changes to the page (Markdown document) you want to improve.
- Submit a pull request with explanation of your changes. Once it's accepted, congratulations: you are now a co-creator of the handbook.
  - Later you may be given commit privileges to the handbook, meaning you can be one of the people authorized to commit to the main branch of repo, and therefore accept (merge) pull requests (note that it's often considered a best practice to make a pull request and get someone else to merge it to main, even if you are technically able to directly commit changes to main unilaterally).

#### Getting started by creating a project
- Clone this repository. Open it up in your file manager on your computer; you'll note that the folder structure mirrors the link structure (you can figure out where any document in the repo is by examining the URL of the link to it).
- Fork the repo.
- Create a new textfile with a name like my_project.md (.md is the Markdown file extension).
- Glance at the [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) to remind yourself how to create nicely formatted text with headers, links, etc. Write an explanation of your project.
- Add a short high-level explanation of the project's main focus and goal(s). If a detailed publicly-accessible document already exists elsewhere, add a link to it.
- Try to add links to everything someone trying to manage the project would need. For example, the original project proposal and budget.
  - These may be private documents (the budget probably is). No problem; as long as the permissions _on the documents themselves_ are correctly set, the link won't help anyone who doesn't already have permission.
  - Try to add a section mentioning key people and their roles. For example, who is the donor/client point of contact? Who is the field team leader? Who is the HQ lead?
    - If this information should not be public, the easiest thing may be simply to put it in a Google Doc shared only with those authorized to see or edit it, and put a link to that doc in the Markdown. This way everyone will know where the document is (helpful for those who should have access to it but may not remember where it's saved; now they have a link labelled something like ```List of key stakeholders```) but only the authorized can actually read or edit it.
- 



## Humanitarian Data team

This is the division of HOT, under the Director of Humanitarian Data, that is generally responsible for in-person data collection activities undertaken by HOT itself, as opposed to by communities in the larger HOT and humanitarian mapping community.

HOT has a lot of projects on the go that require people to be familiar with some context, people, resources, and documents.

There a great many documents and resources we refer to for our daily work. HOT uses Google Shared Drive for a lot of document storage, but this is far from the only place where critical information may be stored. In some cases documents may be listed that actually live on local machines or hard drives, and are therefore not linked (but at least discoverable for colleagues that may want them and can then ask us for them).

## Current Projects

### Open Cities Africa Bamako, Mali

Details of the project [here](Projects/OCA_Bamako.md)

### Missing Maps DRC and Uganda, Grand Challenges Canada

Details of the project [here](Projects/Missing_Maps_DRC_Uganda_GCC.md)

### FieldReady Uganda, Iraq, Kenya, Bangladesh

Details of the project [here](Projects/FieldReady.md)

## Historical Projects


## Proposals

### UNHCR Kakuma and Kalobeyi Camp Mapping

UNHRC and Microsoft are interested in mapping Kakuma and Kalobeyei Refugee Camps in Kenya for 2021. [Proposal here](https://drive.google.com/file/d/1KiQT5NNsjx1ixfsa5B0wmh-OFoLYgmU4/view?usp=sharing)

# Working Groups
[working groups](Projects/working_groups.md)



# Licence
Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
