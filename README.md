# Digital Prison Reporting POC 

[![repo standards badge](https://img.shields.io/badge/dynamic/json?color=blue&style=for-the-badge&logo=github&label=MoJ%20Compliant&query=%24.data%5B%3F%28%40.name%20%3D%3D%20%22template-repository%22%29%5D.status&url=https%3A%2F%2Foperations-engineering-reports.cloud-platform.service.justice.gov.uk%2Fgithub_repositories)](https://operations-engineering-reports.cloud-platform.service.justice.gov.uk/github_repositories#template-repository "Link to report")

CODEOWNER : hmpps-digital-prison-reporting

This repository is for POC only containing:

- The correct LICENSE
- Github Action example
- A .gitignore file
- A CODEOWNERS file
- A dependabot.yml file
- The MoJ Compliant Badge (Public repositories only)

###Details:

- TBC


### Branch Naming 

- Please use wherever possible the JIRA ticket as branch name.

### Commits

- Please reference any relevant JIRA tickets in commit message.

### Pull Request

- Please reference any relevant JIRA tickets in pull request notes.

### Local Development or Execution

- TBC

### Notes

- Modify the Dependabot file to suit the [dependency manager](https://docs.github.com/en/code-security/dependabot/dependabot-version-updates/configuration-options-for-the-dependabot.yml-file#package-ecosystem) you plan to use and for [automated pull requests for package updates](https://docs.github.com/en/code-security/supply-chain-security/keeping-your-dependencies-updated-automatically/enabling-and-disabling-dependabot-version-updates#enabling-dependabot-version-updates). Dependabot is enabled in the settings by default.

- Ensure as many of the [GitHub Standards](https://github.com/ministryofjustice/github-repository-standards) rules are maintained as possibly can.
- Modify the MoJ Compliant Badge url using these [instructions](https://github.com/orgs/ministryofjustice/teams/operations-engineering/discussions). If the repository is internal or private then the badge can removed as it will not work.
- For a private repo with no GitHub Advanced Security license remove the .github/workflows/dependency-review.yml file.

[create a repository]: https://github.com/ministryofjustice/template-repository/generate