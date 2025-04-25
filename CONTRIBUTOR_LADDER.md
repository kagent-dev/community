# Kagent Contributor Ladder

This document describes the set of roles individuals may have within the community, the requirements of each role, and the contributor ladder for someone to grow.

* [Contributor Ladder](#contributor-ladder)
    * [Contributor](#contributor)
    * [Organization Member](#organization-member)
    * [Maintainer](#maintainer)

## Contributor Ladder

This contributor ladder outlines the different contributor roles within the project, along with the responsibilities and privileges that come with them. Community members generally start at the first levels of the "ladder" and advance up it as their involvement in the project grows.  Our project members are happy to help you advance along the contributor ladder.

Each of the contributor roles below is organized into lists of three types of things. "Responsibilities" are things that a contributor is expected to do. "Requirements" are qualifications a person needs to meet to be in that role, and "Privileges" are things contributors on that level are entitled to.

### Contributor

A Contributor contributes directly to the project and adds value to it. Contributions need not be code. People at the Contributor level may be new contributors, or they may only contribute occasionally.

* Responsibilities include:
    * Following the [CNCF CoC](https://github.com/cncf/foundation/blob/main/code-of-conduct.md)
    * Following the project [contributing guide](CONTRIBUTING.md)
* Requirements (one or several of the below):
    * Report issues
    * Show up at meetings, takes notes
    * Answer questions from other community members
    * Submit feedback on issues and PRs
    * Test releases and patches and submit reviews
    * Run or help run events
    * Promote the project in public

### Organization Member

An Organization Member is an established contributor who regularly participates in the project. Organization Members have privileges in the project repositories, and as such are expected to act in the interests of the whole project.

An Organization Member must meet the responsibilities and has the requirements of a Contributor, plus:

* Responsibilities include:
    * Continues to contribute regularly, as demonstrated by having at least 3 GitHub contributions per year, as shown by [devstats](https://devstats.cncf.io/).
* Requirements:
    * Must have successful contributions to the project, including at least one merged PR.
    * Must be member of the [kagent discord](https://slack.cncf.io).
    * Must have [2FA](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa) enabled on your GitHub account.
* Privileges:
    * May be assigned Issues and Reviews.
    * May give commands to CI/CD automation.
    * May label/triage issues.

To apply to become a member of the kagent-dev organization on GitHub, please open a GitHub PR in the community repository that contains the following:
1. Use the [membership request template](.github/PULL_REQUEST_TEMPLATE/apply_to_be_a_member.md).

### Maintainer

Maintainers are very established contributors who are responsible for the entire project. As such, they have the ability to approve PRs against any area of the repository or repositories they maintain, and are expected to participate in making decisions about the strategy and priorities of the project.

A Maintainer must meet the responsibilities and requirements of an Organization Member, plus:

* Responsibilities include:
    * Reviewing at least 3 PRs per year, especially PRs that involve multiple parts of the project
    * Mentoring other contributors
    * Determining strategy and policy for the project
* Requirements
    * Experience as an Organization Member for at least 3 months
    * Has reviewed, or helped review, at least 20 Pull Requests
    * Has at least 20 substantial PRs merged to the codebase
    * Demonstrates a broad knowledge of the project across multiple areas
* Additional privileges:
    * Has GitHub or CI/CD rights to approve pull requests in specific directories
    * Can recommend and review other contributors to become Maintainers
    * Represents the project in public as a Maintainer
    * Has a vote in Maintainer decision-making discussions
    
Any current Maintainer may nominate a current Organization Member to become a new Maintainer in one or more repositories, by opening a PR in the community repository using the [maintainer nomination template](.github/PULL_REQUEST_TEMPLATE/nominate_a_maintainer.md). The following requirements must be met before the PR is merged:
1. Each item in the template checklist must be satisfied.
1. At least 2 current Maintainers from each relevant repository must approve the PR.
1. There must be no objections from other maintainers. This can be achieved by either of the following, whichever occurs first:
    * Leaving the PR open for one week with no objections
    * Asking at the weekly community meeting whether there are any objections

## Inactivity

It is important for contributors to be and stay active to set an example and show commitment to the project. Inactivity is harmful to the project as it may lead to unexpected delays, contributor attrition, and a lost of trust in the project.

* Inactivity is measured by:
    * Periods of no contributions for longer than 12 months
    * Periods of no communication for longer than 6 months
* Consequences of being inactive include:
    * Involuntary removal or demotion
    * Being asked to move to Emeritus status

## Involuntary Removal or Demotion

Involuntary removal/demotion of a contributor happens when responsibilities and requirements aren't being met. This may include repeated patterns of inactivity, extended period of inactivity, a period of failing to meet the requirements of your role, abusing the CI/CD priviedges and/or a violation of the Code of Conduct. This process is important because it protects the community and its deliverables while also opens up opportunities for new contributors to step in.

Involuntary removal or demotion is handled through a vote by a majority of the current Maintainers.

## Stepping Down/Emeritus Process

If and when contributors' commitment levels change, contributors can consider stepping down (moving down the contributor ladder) vs moving to emeritus status (completely stepping away from the project).

Contact the maintainers in our [CNCF slack](https://cloud-native.slack.com/archives/C080D3PJMS4) about changing to Emeritus status, or reducing your contributor level.
