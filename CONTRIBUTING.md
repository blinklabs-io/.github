# Welcome to the Blink Labs contributing guide <!-- omit in toc -->

Thank you for investing your time in contributing to our project!

Read our [Code of Conduct](./CODE_OF_CONDUCT.md) to keep our community
approachable and respectable.

In this guide you will get an overview of the contribution workflow from
opening an issue, creating a PR, reviewing, and merging the PR.

## Getting started

To get an overview of the project, read the [README](README.md). Here are some
resources to help you get started with open source contributions:

- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

Blink Labs repositories use Conventional Commits for all commits. This defines
a standard format for commit messages across repositories and projects.

- [CODEOWNERS](CODEOWNERS)

Blink Labs repositories use CODEOWNERS files to provide information on who
should review a contribution. For repositories with regular outside
contributors, they will be listed within this file in the repository or
repositories which they maintain.

- [Developer Certificate of Origin](https://developercertificate.org/)

All contributions must comply with the Developer Certificate of Origin (DCO). This certifies that you have the right to submit the work and that it is your own or properly licensed.

To sign off your commits, use `git commit -s` or `git commit --signoff`.

Our CI will enforce DCO compliance.

- Licensing

Blink Labs projects are primarily licensed under the Apache License 2.0. However, some repositories or components within the organization may use MIT or CC-BY-SA 4.0 licenses. Please check the specific project's LICENSE file for the applicable license.

All contributions must be compatible with the project's license and will be licensed under the same terms.

- Communication and Collaboration

To engage with the Blink Labs community, join our [Discord server](https://discord.gg/5fPRZnX4qW) for real-time discussions and support. Follow us on [X (formerly Twitter)](https://twitter.com/blinklabs_io) for updates and announcements. Connect with us on [LinkedIn](https://linkedin.com/company/blink-labs-io) for professional networking. Read our blog on [Medium](https://medium.com/@blinklabs_io) and watch tutorials on [YouTube](https://youtube.com/@blinklabs_io). For direct inquiries, email us at [support@blinklabs.io](mailto:support@blinklabs.io).

- [Security Policy](./SECURITY.md)

<br>

## Types of Contributions

Contributions to open source come in many forms. You can contribute to Blink
Labs projects in several ways, including but not limited to:

- **Code Contributions**: Submit pull requests with bug fixes, new features, improvements, or refactoring.
- **Documentation**: Improve existing documentation, write tutorials, translate content, or update READMEs and guides.
- **Issue Reporting and Triage**: Report bugs, suggest features, or help organize and prioritize existing issues.
- **Community Support**: Answer questions in discussions, forums, or chat channels; mentor new contributors.
- **Design and UX**: Contribute to user interface designs, graphics, or user experience enhancements.
- **Testing and QA**: Write or improve tests, report test failures, or assist with quality assurance.
- **Translations**: Help localize the project into other languages.
- **Other**: Any other contributions that benefit the project and community, such as marketing, outreach, or event organization.

### Issues

#### Create a new issue

If you spot a problem with a project, search if an issue already exists. If a
related issue doesn't exist, you can open a new issue in the repository.

#### Solve an issue

Scan through our existing issues to find one that interests you. You can narrow
down the search using `labels` as filters. As a general rule, we don’t assign
issues to anyone. If you find an issue to work on, you are welcome to open a PR
with a fix.

### Pull Request

When you're finished with the changes, create a pull request, also known as a
PR.
- Don't forget to
[link PR to issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)
if you are solving one.
- Enable the checkbox to
[allow maintainer edits](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/allowing-changes-to-a-pull-request-branch-created-from-a-fork)
so the branch can be updated for a merge.
Once you submit your PR, a Docs team member will review your proposal. We may
ask questions or request additional information.
- We may ask for changes to be made before a PR can be merged, either using
[suggested changes](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/incorporating-feedback-in-your-pull-request)
or pull request comments. You can apply suggested changes directly through the
UI. You can make any other changes in your fork, then commit them to your
branch.
