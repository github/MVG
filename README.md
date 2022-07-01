# Minimum Viable Governance

## What is Minimum Viable Governance?

Minimum Viable Governance (MVG) - currently in beta - is a repository-based approach for putting lightweight governance into free and open source projects that are run in version control systems. It provides an overall two-tier organizational governance structure for a set of free and open source projects. At the top level (called an "organization" on GitHub), there is a technical steering committee to make decisions about the overall direction and coordination between all the organization's projects. Underneath that top level are the individual projects, with lightweight, consensus-based governance.

There are two folders. The first, org-docs, provides top-level organizational governance and policies for a technical steering committee (TSC). The second folder, project-docs, provides a template for individual project governance, subject to the policies and oversight of the larger organization.

Minimum Viable Governance is meant as a way to quickly stand up collaborations that can grow with your organization and projects. If your organization grows to the point where a corporate home becomes necessary, typically when your organization begins holding money, MVG is designed to make that transition easy.

## Why would we want to use this?

Minimum Viable Governance allows you to start an organization and sub-projects with simple governance in place at the outset - including legal terms, licensing and trademark issues, and due process. Having this governance in place early helps avoid disputes among participants down the road.

## How do we use this?

1. Review the documents and determine if this is right for you.
2. Describe the organization's mission in Section 1 of the [CHARTER.md](org-docs/CHARTER.md) file.
3. Put the org-docs in a repository for the organization's governance and have each initial TSC member "sign" the [STEERING-COMMITTEE.md](org-docs/STEERING-COMMITTEE.md) file by adding their name and organizational affiliation (if applicable) to the file.
4. For each project that will be under your organization's governance, create a repository under the organization and have each initial maintainer "sign" the [MAINTAINERS.md](project-docs/MAINTAINERS.md) file by adding their name and affiliation (if applicable) to the file.
5. [Choose a license](https://choosealicense.com/) or fill out the copyright information in the MIT [LICENSE.md](project-docs/LICENSE.md) file for each project.
6. Get to work.

## Contributing

Hi there! We're thrilled that you'd like to contribute to this project. Your help is essential for keeping it great.

Contributions to this project are [released](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license) to the public under the [project's open source license](LICENSE).

Please note that this project is released with a [Contributor Code of Conduct](https://raw.githubusercontent.com/EthicalSource/contributor_covenant/release/content/version/2/0/code_of_conduct.md) (CoC). By participating in this project you agree to abide by its terms. Violations of the CoC should be reported to: opensource@github.com. To avoid confusion with MVG artifacts, we did not place the CoC in the repo.

### Submitting a pull request

1. [Fork](https://github.com/github/MVG/fork) and clone the repository
2. Create a new branch: `git checkout -b my-branch-name`
3. Make your change
4. Push to your fork and [submit a pull request](https://github.com/github/MVG/compare)
5. Pat yourself on the back and wait for your pull request to be reviewed and merged.
