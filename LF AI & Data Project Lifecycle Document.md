![5pz0bca3](https://github.com/user-attachments/assets/7a1f9969-c5c5-4bd1-9534-7394b35d4335)

# LF AI & Data Foundation Project Lifecycle Document

## Table of Contents

* [1 - Introduction](#1---introduction)
* [2 - Sandbox Stage Requirements](#2---sandbox-stage-requirements)
  * [Tasks to be performed by the project’s team requesting incubation status](#tasks-to-be-performed-by-the-projects-team-requesting-incubation-status)
* [3 - Incubation Stage Requirements](#3---incubation-stage-requirements)
* [4 - Graduation Stage Requirements](#4---graduation-stage-requirements)
* [5 - Benefits Associated with Each Lifecycle Stage](#5---benefits-associated-with-each-lifecycle-stage)
  * [Support Programs - Sandbox Stage Projects](#support-programs---sandbox-stage-projects)
  * [Support Programs - Incubation Stage Projects](#support-programs---incubation-stage-projects)
  * [Support Programs - Graduation Stage Projects](#support-programs---graduation-stage-projects)
* [6 - Emeritus Stage Projects](#6---emeritus-stage-projects)
* [7 - Process of Archiving a Project](#7---process-of-archiving-a-project)
* [8 - Annual Review](#8---annual-review)
* [9 - Maintaining and Approving this Document](#9---maintaining-and-approving-this-document)
* [10 - Feedback](#10---feedback)

_Approved and in effect as of June 1st, 2023_

---

## 1 - Introduction

The document explains the four stages of LF AI & Data project hosting (Sandbox, Incubation, Graduation and Emeritus), the requirements for each stage, the benefits, and how to transition from one stage to the next.

The following figure illustrates the various incubation stages, TAC sponsor requirements, and the required voting for a project to be accepted into the foundation and promoted across the incubation stages.

![xum5y022](https://github.com/user-attachments/assets/d46ad123-57f2-4735-b54c-514eb88713ec)

Please note that if a project’s request to transition to a higher level stage is not approved, the project is eligible to re-apply after six months of the first request.

---

## 2 - Sandbox Stage Requirements

To be accepted into the Sandbox stage, a project must meet the following requirements:

> 1. Fit the scope and mission of LF AI & Data
> 2. Have a sponsor who is an existing LF AI & Data member. Alternatively, a new organization would join LF AI & Data and sponsor the project’s incubation application.
> 3. Have an open and documented technical governance. The Linux Foundation team can help set this up as part of the onboarding process.
> 4. Have an OSI-approved license.
> 5. The project's founders adopt an open governance model documented in a Technical Charter for the project, and execute the Project Contribution Agreement transferring the project’s assets to the Linux Foundation.

### Tasks to be performed by the project’s team requesting incubation status

> 1. Submit a Project Contribution Proposal via a GitHub pull request to <https://github.com/lfai/proposing-projects/tree/master/proposals>.
> 2. Move the project’s code into its own GitHub organization and not under its founder’s organization.
> 3. Enable two-factor authentication for all members of the project’s GitHub org.
> 4. Install the [GitHub DCO app](https://github.com/apps/dco) on all repos.
> 5. Add @thelinuxfoundation as a co-owner of the GitHub org.
> 6. Achieve and maintain an [OpenSSF Best Practices Badge Program](https://bestpractices.coreinfrastructure.org/) (Passing).
> 7. Identify who on the project will handle security issues (could be a team).
> 8. LF AI & Data will set up a mailing list to receive and discuss security vulnerability reporting.
> 9. Have the following files in GitHub:

* `LICENSE.md` at the root of the repository specifying the terms and conditions for using, distributing, and modifying the software. In addition, you should provide information on the license of any third-party code included in the project.
* `README.md` welcomes new community members to the project and explains why the project is useful and how to get started.
* `CONTRIBUTING.md` explains how to contribute to the project. The file explains the types of contributions needed and how the development process works.
* `CODEOWNERS` to define individuals or teams responsible for code in a repository; document current project owners and emeritus committers.
* `CODE_OF_CONDUCT.md` sets the ground rules for participants’ behavior and helps facilitate a friendly, welcoming environment. By default, projects should leverage the [Linux Foundation Code of Conduct](https://lfprojects.org/policies/code-of-conduct/) unless an alternate Code of Conduct is approved prior.
* `RELEASE.md` provides documentation on the release methodology, cadence, criteria, etc.
* `GOVERNANCE.md` documents the project’s technical governance.
* `SUPPORT.md` lets users and developers know how to get help with the project.
* `SECURITY.md` informs users and developers on how to report security issues and vulnerabilities.
* \[Optional but highly recommended\] Include a Software Package Data Exchange (SPDX) short-form identifier in a comment at the top headers of each source code file.

After achieving a majority TAC vote, a project will be welcomed into the Sandbox stage.

---

## 3 - Incubation Stage Requirements

To be accepted into the Incubation stage, a project must meet all the requirements of the Sandbox stage plus:

> 1. Have at least three organizations actively contributing to the project.
> 2. Have a defined Technical Steering Committee (TSC) with a chairperson identified, with open and transparent communication.
> 3. Have reached a minimum of 500 stars on GitHub.
> 4. Have achieved and maintained an [OpenSSF Best Practices Badge Program](https://bestpractices.coreinfrastructure.org/) (Silver).

After achieving a majority TAC vote, a project will be welcomed into the Incubation stage.

---

## 4 - Graduation Stage Requirements

To be accepted into the Graduation stage, a project must meet the Incubation stage requirements plus:

> 1. Have a healthy number of code contributions from at least five organizations.
> 2. Have reached a minimum of 1000 stars on GitHub.
> 3. Have achieved and maintained an [OpenSSF Best Practices Badge Program](https://bestpractices.coreinfrastructure.org/) (Gold).
> 4. Have demonstrated a substantial ongoing flow of commits and merged contributions for the past 12 months\*.
> 5. Have completed at least one collaboration with another LF AI & Data hosted project.

Since some of these criteria can vary depending on a project's type, scope, and size, the TAC has final judgment over the activity level adequate to meet these criteria.

To graduate, the project must receive the affirmative vote of the TAC and the Governing Board.

When a project graduates, it will be eligible to have a technical lead appointed to represent the project on the LF AI & Data Technical Advisory Council. The project is expected to nominate a lead to the TAC who can attend and participate in the bi-weekly TAC calls.

---

## 5 - Benefits Associated with Each Lifecycle Stage

### Support Programs - Sandbox Stage Projects

Sandbox stage projects are eligible to receive the following benefits:

* Neutral hosting of the project’s trademark and assets by LF AI & Data.
* Appointment of a TAC member as a project sponsor and provide recommendations regarding governance best practices.
* LF AI & Data blog post or similar announcing the project's hosting in the Foundation (quarterly announcements).
* Right to refer to the project as an “[LF AI & Data Sandbox Project](https://github.com/lfai/artwork/tree/main/lfaidata-assets/lfaidata-project-badge),” with the right, subject to applicable trademark usage guidelines, to display the LF AI & Data logo on the project’s code repository.
* An initial and regularly scheduled license scan of the project’s codebase with results reported to the project’s mailing list.
* Ongoing source code security scans and reports.
* Infrastructure support includes mailing lists, wiki space, slack channel, etc.
* Marketing, communication, and PR support are limited to significant announcements.
* Access to the [LFX](https://lfx.linuxfoundation.org/) platform.
* Support of the Foundation staff who are eager to help with the project.

### Support Programs - Incubation Stage Projects

Incubation stage projects are eligible to receive all the benefits of the Sandbox stage projects plus:

* Right to refer to the project as an “[LF AI & Data Incubation Project](https://github.com/lfai/artwork/tree/main/lfaidata-assets/lfaidata-project-badge),” with the right, subject to applicable trademark usage guidelines, to display the LF AI & Data logo on the project’s code repository.
* Creative and artwork support covering website, logo, and other required creative work.
* Marketing, communication, and PR support, including project promotion via blog posts, social media, and LF AI & Data website.
* Access to the Bevy platform for community-hosted events.

### Support Programs - Graduation Stage Projects

Graduation stage projects are eligible for all the benefits of Incubation stage projects plus:

* LF AI & Data blog announcement or similar announcing the project graduation, including promotion activities.
* Graduation stage projects may receive support as determined by the Governing Board.
* Right to refer to the project as an “[LF AI & Data Graduation Project](https://github.com/lfai/artwork/tree/main/lfaidata-assets/lfaidata-project-badge),” with the right, subject to applicable trademark usage guidelines, to display the LF AI & Data logo on the project’s code repository.
* Voting seat on the TAC.
* Advanced IT infrastructure support (pending board approval).
* Additional ecosystem development opportunities include training courses, certification development, and conformance programs (pending board approval).

---

## 6 - Emeritus Stage Projects

There are times when projects become inactive for various reasons. There are cases where the TAC may no longer support a project. The project will be transitioned to the Emeritus stage and archived in such cases.

What does archiving for an LF AI & Data project mean?

* LF AI & Data will no longer provide support for the project beyond what’s deemed necessary as part of the archiving process.
* LF AI & Data will list the project online as archived.
* All assets, including trademarks of archived projects, will remain hosted by LF AI & Data and the Linux Foundation.

Process of Archiving a Project

* A proposal must be submitted to the TAC via the regularly scheduled TAC call.
* The proposal will be presented to the TAC and include an explanation supporting archiving of the project.
* The proposal must remain open for at least two weeks of discussion.
* A vote must be finalized with 2/3 approval from the TAC and 2/3 approval from the Governing Board.

---

## 7 - Moving a Project outside LF AI and Data

A project can choose to move outside of LF AI and Data without archiving the project. To do so, the project must provide written notice to the TAC, and such request will be recognized during a future TAC meeting. The TAC will notify the Governing Board as well. No formal vote is required. LF Staff will faciliate this transition.

---

## 8 - Annual Review

The TAC will annually review all LF AI & Data projects. This annual review will include assessing whether projects in Sandbox and Incubation are making adequate progress towards the Graduation stage; and whether projects in the Graduation stage are maintaining positive growth and adoption. Any project may be moved to the Emeritus stage, provided the TAC and the Governing Board approve the transition via a 2/3 affirmative vote.

---

## 9 - Maintaining and Approving this Document

The TAC is responsible for maintaining the Project Lifecycle Document. To update the document, both the TAC and the Governing Board must vote in favor of the proposed changes.

---

## 10 - Feedback

To provide feedback on this document, please email <info@lfaidata.foundation> or subscribe to the [TAC mailing list](https://wiki.lfaidata.foundation/pages/viewpage.action?pageId=7733361&src=contextnavpagetreemode) and email directly to the list.
