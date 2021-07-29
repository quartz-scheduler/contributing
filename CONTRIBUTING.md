
# Contributing to Terracotta Projects

_We're happy to have you participate in our community with your contributions!_

## Process

Terracotta projects are owned by Software AG.  Please follow the simple Software AG contribution process documented here: https://github.com/SoftwareAG/contributing/blob/main/CONTRIBUTING.md

We strongly recommend that you pay special attention to the "Note on Privacy" on that page and review the Contributor's License Agreement (linked from that page) in full.

In brief, the process is as simple as:

* Fork the code repository
* Commit your changes with the _-s_ option to agree to the CLA and "sign over" copyright ownership
* Create a Pull Request (PR) from your fork to the original project, on the appropriate branch
* Await feedback on your contribution (which will typically come in the form of comments on your PR)

Please also review the following sections that have additional important information.

## Community Guidelines

### Code of Conduct

Before participating in our community with our code, doc, or forum contributions, please review our Community [Code of Conduct](CODE_OF_CONDUCT.md).

### Coding Standards

* Rule #1: do not gratuitously reformat all the the code in existing files.  If you're changing an existing file, make your code changes match the formatting that is already in that file.
* Use spaces, not Tabs, follow common Java formatting rules, your contribution may be initially rejected if it's a mess.
* Explanatory comments are friendly to other developers, and to your future self!

---

# Acting As a Project Publisher aka Maintainer aka Committer

Some members of the project have a role beyond that of a contributor.  These members are known as _Publishers_, and their role is similar to that of people with the role "Committer" or "Maintainer" on other projects.

Publishers review PRs from other contributors, and have the rights to merge those PRs into the project.

Publishers rights, duties, and responsibilities include:
* Reviewing and Merging Pull Requests
  - Ensure that the PR has a signed-off contributor license agreement ([CLA]( https://github.com/SoftwareAG/contributing/blob/main/CONTRIBUTING.md))
  - Ensure coding guidelines and community conduct guidelines are not violated
  - Review for functional correctness and possible performance impact
  - Review for possible security vulnerabilities or malicious intent
  - Check for any introduction of new third-pary library dependencies (see below)
  - Ensure all automated checks (build/test, etc.) have passed
  - Give kind and detailed feedback to the contributor
  - Addional pre-merge rules:
    - Contributions that introduce new features require discussion and vote from at least two additional project Admins/Publishers
    - Contributions that affect backward compatibility require discussion and vote from at least two additional project Admins/Publishers
    - Contributions that introduce 3rd party libraries require discussion and vote from at least two additional project Admins/Publishers
    - Contributions that otherwise necessitate a Major or Minor version bump require discussion and vote from at least two additional project Admins/Publishers
* Actively seek input and opinions from other project Publishers and contributors when reviewing contributions that have significant impact
* Fostering and protecting a healthy project community culture





