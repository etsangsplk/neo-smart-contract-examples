# Contributing to `neo-smart-contract-examples`

1. [Getting Involved](#getting-involved)
1. [Questions and Discussion](#questions-and-discussion)
1. [Core Style Guide](#core-style-guide)
1. [Pull Request Process](#pull-request-process)
1. [Code of Conduct](#code-of-conduct)

## Getting Involved

We're always looking for help adding examples, identifying bugs and improving documentation. Anything passing our guidelines will be considered.

When contributing to this repository, please first discuss the change you wish to make via issue, email, or any other method with the owners of this repository before making a change.

## Questions and Discussion

Please start by search the issue tracker as your issue may have already been discussed or fixed. If it is something that is not yet discussed, please file a new issue in the issue tracker.

You may also use the [official community chat](https://discord.gg/R8v48YA) and join the software discussion on its developer channel.

## Core Style Guide

This project is current under rapid developments a general guidelines are:

### Coding in General

* Strictly no `tab` characters.
* Do not commit `.avm` file.

### Python Specific

* Please follow the same comment format as seem in existing example.
* Although not reinforced, you are recommended to follow [PEP 8] style guide.
* Although not reinforced, you are recommended to lint your code through `pydocstyle`.
* To reduce developers learning curve, [PEP 484 Type Hints](https://www.python.org/dev/peps/pep-0484/) are not to be used in example contracts.
* Usage of [PEP 484 Type Hints](https://www.python.org/dev/peps/pep-0484/) is allowed in use case contracts.
* Each example contract must be in exactly 1 code file. This is not reinforced for use case contracts.

### C# Specific

* TBA

## Translation

* Use English documentation as the source of truth.
* TBA

## Pull Request Process

1. Update the `README.md` with details of changes to the interface, this includes new environment variables, exposed ports, useful file locations and container parameters.
1. Pull requests are made against feature branches and the `master` branch.
1. You may merge the Pull Request in once you have the sign-off of a developer on the project.

## Code of Conduct

### Our Pledge

In the interest of fostering an open and welcoming environment, we as contributors and maintainers pledge to making participation in our project and our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment include:

* Using welcoming and inclusive language
* Being respectful of differing viewpoints and experiences
* Gracefully accepting constructive criticism
* Focusing on what is best for the community
* Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

* The use of sexualized language or imagery and unwelcome sexual attention or advances
* Trolling, insulting/derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or electronic address, without explicit permission
* Other conduct which could reasonably be considered inappropriate in a professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or reject comments, commits, code, wiki edits, issues, and other contributions that are not aligned to this Code of Conduct, or to ban temporarily or permanently any contributor for other behaviors that they deem inappropriate, threatening, offensive, or harmful.

### Scope

This Code of Conduct applies both within project spaces and in public spaces when an individual is representing the project or its community. Examples of representing a project or community include using an official project e-mail address, posting via an official social media account, or acting as an appointed representative at an online or offline event. Representation of a project may be further defined and clarified by project maintainers.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting the project team at [INSERT EMAIL ADDRESS]. All complaints will be reviewed and investigated and will result in a response that is deemed necessary and appropriate to the circumstances. The project team is obligated to maintain confidentiality with regard to the reporter of an incident. Further details of specific enforcement policies may be posted separately.

Project maintainers who do not follow or enforce the Code of Conduct in good faith may face temporary or permanent repercussions as determined by other members of the project's leadership.

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage], version 1.4,
available at [http://contributor-covenant.org/version/1/4][version]

[homepage]: http://contributor-covenant.org
[version]: http://contributor-covenant.org/version/1/4/
