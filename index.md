**Table of contents**

* [Introduction](#introduction)
* [What is Performance Co-Pilot?](#what-is-performance-co-pilot)
* [Abstract of the project](#abstract-of-the-project)
* [GSoD 2021](#gsod-2021)
   * [Deliverable 1 ](#deliverable-1)
   * [Deliverable 2 ](#deliverable-2)
   * [Deliverable 3 ](#deliverable-3)
   * [Deliverable 4 ](#deliverable-4)
   * [Deliverable 5 ](#deliverable-5)
* [Additional Information and Resources](#additional-information-and-resources)
* [EndNote](#endnote)
* [Acknowledgements](#acknowledgements)

### Introduction

As GSoD 2021 has come to an end, this is my project report (final work product) wrapping up all the work done during this journey.

### What is Performance Co-Pilot?

Performance Co-Pilot (PCP) is an open-source distributed system performance analysis toolkit. It efficiently collects metrics from multiple systems and provides a variety of web, graphical and console tools for analysis of live and historical data.

The suite begun production use over 20 years ago primarily in the High Performance Computing arena, however its customizable and lightweight design has proven popular on everything from tiny system-on-a-chip machines through to vast databases and number-crunching super computers. It is included in all Linux distributions and has an active base of users and developers.

### Abstract of the project

The project aims to curate a new series of focussed, task-oriented "How To" guides that will assist new users in engaging immediately, by clearly showing how to solve specific problem scenarios that users encounter frequently. The goals of the project are to assist first-time users to become more productive right away, while also increasing traffic to the more detailed books in the same location (readthedocs.io).

### GSoD 2021

As a part of GSoD 2021, the project had following deliverables:
 
  1. Setup Google Analytics for the PCP documentation and introduce consistency into all Tutorials and Guides across the project, by using a single readthedocs.io landing page for all guides (same location, format, look-and-feel).
  2. Producing succinct step-by-step recipes showing how to perform certain tasks with PCP.
  3. Audit existing documentation for tutorial content to add into the new readthedocs guide format. This involves an assessment of the existing Short Guides and refactoring these into the "How do I..." form.
  4. Canvas the community for additional topics beyond the set above to produce an initial set of high-value guides and provide feedback to developers about potential areas of improvements in the tools to create more satisfying early user experiences.

As a part of GSoD 2021, I completed all the deliverables. Details of my work are as follows:

#### Deliverable 1

During this phase, I kick-started with setting up the Google Analytics for the PCP documentation and make a skeleton in existing documentation for the new chapters of the 'Quick Guides' documentation. This involves creating a new section in the existing index file and making separate files for all the upcoming new chapters. The same consistency was introduced for these new guides (having same location, format, look-and-feel).

So, during Phase 1, I completed the following deliverables: 
 
  * Setup of Google Analytics for the PCP documentation.  
  * Setup of pages for the newer Guide in the existing documentation.  
  

#### Deliverable 2

During this phase, I started writing documentation for the Quick Guides. This involves producing step by step procedure showing how to perform a certain task with PCP. During this phase, I wrote documentation for nine such tasks.

So, during Phase 2, I completed the following deliverables: 
 
  * Wrote documentation for Quick Guides. 
  * Hosted them on readthedocs site.
 
#### Deliverable 3

During this phase, I started with auditing existing documentation for the Short Guides. After that, I started converting them into 'How do I' form. In the end, after the review from the mentor, they were hosted on modern, community readthedocs site.
 
 So, during Phase 3, I completed the following deliverables: 
 
  * Audited existing documentation for the Short Guides.
  * Converted them into 'How Do I' form
  * Hosted them on readthedocs site.

#### Deliverable 4

In this phase, I gave a list for additional topics beyond the set above to produce an initial set of high-value guides and also, provided feedback to developers about potential areas of improvements in the tools to create more satisfying early user experiences.

#### Google Analytics Insights

For the month of November (since the publishing of the documentation), we saw -

* 46% views (out of 1040) of the new Quick Guides documentation
* 27% users (out of 244) have opened the Quick Guides documentation
* 6% (out of 223) are the new users.
* Views per user (1.70) is highest for the new Quick Guides comparatively to the other Guides.

  
### Additional Information and Resources

1. Mentoring Organization - [Performance Co-Pilot](https://pcp.io/)
2. Mentors - [Nathan Scott](https://github.com/natoscott)
3. [Project](https://pcp.io/gsod/2021/ideas.html)
4. [Proposal](https://pcp.io/gsod/2021/proposal.html)
5. Github Repositories - [PCP](https://github.com/performancecopilot/pcp)
6. Merged PRs - [#1469](https://github.com/performancecopilot/pcp/pull/1469), [#1473](https://github.com/performancecopilot/pcp/pull/1473), [#1474](https://github.com/performancecopilot/pcp/pull/1474), [#1484](https://github.com/performancecopilot/pcp/pull/1484), [#26](https://github.com/performancecopilot/pcp-website/pull/26)
7. [Timeline & Deliverables](https://github.com/arzoo14/Google-Season-of-Docs-2021/blob/main/timeline_deliverables.md)  
8. Final Work Product - [PCP](https://pcp.readthedocs.io/en/latest/)
9. [Blogs](https://arzoo14.github.io/gsod-2021/)

### EndNote

With this, the Google Season of Docs has come to an end. This journey has been very exciting, challenging and fun. During this journey, I learnt a lot about the PCP tools. Also, I learnt more new things related to the technical docuentation. I have seen an immense increase in my technical writing skills.

### Acknowledgements

I would like to express my sincere gratitude to my mentors - Nathan Scott, Christian Horn and Apurva Bhide for their constant support and guidance. They were always around and had solutions to any issue that I faced. I have learnt a lot from them and expect to learn a lot more in the future.

I am grateful to Google and Performance Co-Pilot organization for giving me this golden opportunity again this year. 