# Glossary

## CI/CD

In software engineering, [CI/CD or CICD](https://en.wikipedia.org/wiki/CI/CD) generally refers to the combined practices of continuous integration and either continuous delivery or continuous deployment. CI/CD bridges the gaps between development and operation activities and teams by enforcing automation in building, testing and deployment of applications. Modern day DevOps practices involve continuous development, continuous testing, continuous integration, continuous deployment and continuous monitoring of software applications throughout its development life cycle. The CI/CD practice or CI/CD pipeline forms the backbone of modern day DevOps operations.

## Code of Conduct

This may be included in the body of README or in separate files for other providers of the project type. These are generally sensible. If the same Code exists in another Packet owned project, it can be assumed to be approved. 

## Contributors Guide

Contributing notes may be included in README.md or in a separate CONTRIBUTING.md.  Expectations around licensing, copyright, and what to expect when contributing to this project should be covered. Tips on what linters and tests are run should be provided so that users can perform these locally. These may differ from project to project, even among common programming languages, based on the ecosystem of the project.

## Developer Certificate of Origin

[Developer Certificate of Origin](https://github.com/apps/dco) provides basic accountability for the code being submitted to the project.

## End of Life Badge

![](https://img.shields.io/badge/Stability-EndOfLife-black.svg)

## End of Life Statement

This repository is [End of Life](https://github.com/packethost/standards/blob/master/end-of-life-statement.md) meaning that this software is no longer supported nor maintained by Packet or its community.

## Experimental Badge

![](https://img.shields.io/badge/Stability-Experimental-red.svg)

## Experimental Statement

This repository is [Experimental](https://github.com/packethost/standards/blob/master/experimental-statement.md) meaning that it's based on untested ideas or techniques and not yet established or finalized or involves a radically new and innovative style! This means that support is best effort (at best!) and we strongly encourage you to NOT use this in production.

## Getting Started Tutorial

May be included in the README.md and needs to include:
* Requirements: If a project requires API tokens, link to the token creation instructions. In general, cut out the need for users to seek supplementary information seeking without repeating instructions. Make sure to indicate the widest tested range of versions for required software and libraries.
* Installation Instructions: Make sure to provide instructions for Mac, Linux, Windows when available. Try to cover both sides in split ecosystems: Python2/Python3, Helm2/Helm3, Bundler/Gem, for example.
* Usage: Cover the most basic usage and common use-cases. Refer to the documentation for more details. If the project is new and no formal documentation exists, all options should be presented. Once documentation exists, to avoid duplication, replace detailed usage sections with references to the documentation.

## LICENSE

Every OSS project should include an approved OSS license. Observe instructions in the license file about copyright notices. When forking, honor (do not strip) copyright notices. The licenses may stipulate when and how additional copyrights should be applied.  Copyright notices should be assigned to “Packet, an Equinix Company”, not the individuals working on the project.

## Maintained Badge

![](https://img.shields.io/badge/Stability-Maintained-green.svg)

## Maintained Statement

This repository is [Maintained](https://github.com/packethost/standards/blob/master/maintained-statement.md) meaning that this software is supported by Packet and its community - available to use in production environments.

## Maintainer

An organization owner can promote any member of the organization to team [maintainer](https://docs.github.com/en/github/setting-up-and-managing-organizations-and-teams/giving-team-maintainer-permissions-to-an-organization-member) for a team, giving them a subset of privileges available to organization owners.

## Manifest File

Used most commonly in Java, the manifest is a special file that can contain information about the files packaged in a JAR file. By tailoring this "meta" information that the manifest contains, you enable the manifest file to serve a variety of purposes. Other programming languages have similar manifest files, but even if you're project is a markdown or documentation project, you can use the manifest file to store the appropriate set of categories, keywords, and tags. Consider including “packet”, “bare metal”, “on-premise”, “hybrid-cloud”, and “cloud”. Build from there. Project descriptions and overviews should be taken advantage of as well. Logos are a common feature, make sure our projects are including branding approved logos made to fit the project’s visual requirements and theme.

## Owner

An repository owner is the last line of defense if no maintainer has responded to an issue or pull request after a certain amount of time. This person follows up with the relevant maintainers of a repository to move forward on a feature or bug.  

## OWNERS.md

This file defines governance and should be used to identify the maintainers of the project (people before organizations) and how the direction of the project is controlled. A project that has been given to the community should have clear governance otherwise the project risks favoring the original contributors and being perceived as such. Packet projects should have at least two owners.

## README.md

Readme files pertain to the contents of a directory or the scope of a repository. They should not be used as a substitute for end-user documentation or end-user guides.  Some end-users will experience the application without ever seeing the README file contained within the repository, others will contribute to an application without the need for guidance on performing routine or complex tasks.  It is therefore important to make documentation available for the correct audience and transition users to more advanced or more approachable content.README.md files should strive to include the following sections:

* Badges: Stability, Code quality, build status, docker pull count badges increase confidence in our projects. Social linking badges to Slack, Twitter, or others increase our reach.
* Images: Make our projects stand out with custom Packet artwork for the project. When this is not available, include an appropriate (and authorized) set of relevant logos. Following the summary, a screencast will tell a thousand words (per video frame).
* Summary: Begin with a one or two-sentence overview, separated by white space, before expanding on the project details. README files are scraped by many tools and they will act on this hint.
* Requirements: If a project requires API tokens, link to the token creation instructions. In general, cut out the need for users to seek supplementary information seeking without repeating instructions. Make sure to indicate the widest tested range of versions for required software and libraries.
* Installation Instructions: Make sure to provide instructions for Mac, Linux, Windows when available. Try to cover both sides in split ecosystems: Python2/Python3, Helm2/Helm3, Bundler/Gem, for example.
* Usage: Cover the most basic usage and common use-cases. Refer to the documentation for more details. If the project is new and no formal documentation exists, all options should be presented. Once documentation exists, to avoid duplication, replace detailed usage sections with references to the documentation.
* Support expectations: Is this an experimental or maintained project.  Include our standard definition and terms for the given state.
* Limitations: Is ARM supported? What Packet features or service flags are required? Are these features available in all regions? The following features are not available in all facilities, for example storage, global ipv4, backend transfer.

## Rebrand: Packet to Equinix Metal

Packet was acquired by Equinix in March. To help make our vision for global, interconnected bare metal a reality, we've rebranded Packet as Equinix Metal™ and introduced new locations and features. Login, sign up, and say hello at metal.equinix.com. Example rebrands:

* Packet --> Equinix Metal
* support@packethost.com --> support@equinixmetal.com
* https://slack.packet.com/ --> https://slack.equinixmetal.com/
* Freenode IRC #packethost --> Freenode IRC #equinixmetal
* packet.com --> metal.equinix.com
* https://app.packet.net/ --> https://console.equinix.com/

## RELEASE.md

Release knowledge is often lost when not recorded properly. A RELEASE.md could be used to record this information - consider automation like [release-drafter/release-drafter](https://github.com/release-drafter/release-drafter). How is the software built for distribution? How many channels, architectures, artifacts are there? How and where are tags applied? Are tags referenced and tracked in multiple places - Git, docs, config files, Docker images? What commands are needed to run the release? What responsibilities do humans have and what responsibilities do robots have? What changelogs or documentation should be updated on release?

## SUPPORT.md

[SUPPORT.md](https://help.github.com/en/github/building-a-strong-community/adding-support-resources-to-your-project) files will appear when users create issues on projects.  Support between OSS projects should not vary wildly. Some projects will be community supported and we should offer links to the appropriate email address, forum, or slack channel, while others may actually be supported by Packet support.
