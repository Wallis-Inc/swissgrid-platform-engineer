# Dependabot

The Github solution to minimize security vulnerabilities is called Dependabot.

You can see it active in this organization.

## Enforcement

Dependabot can be activated for all repositories in an organization, with varying levels of granularity (allow for configuration by repository, only for new repositories etc.)

Ideally, all possible vulnerabilities should be flagged and solved.
Realistically, you need to prioritize which vulnerabilities are addressed first by their possible impact.
Dependabot notifications can be triaged by severity, allowing us to customize the behavior.

Assuming development teams work with Jira, it could be a good idea to integrate the most severe alerts into a Jira queue. This would make it clear that addressing vulnerabilities is part of the regular tasks, and is to some extent counted in the regular workload.

A few things could be done in time to help reduce the amount of vulnerabilities in all repositories.
- PRs introducing a vulnerability of the highest level could/should be blocked.
https://github.com/actions/dependency-review-action

- A public ranking of the amount of vulnerabilities by teams could be done.

## Implementation

Dependabot is currently implemented in this organization. Furthermore, merging a branch to master is deactivated if that introduces a new vulnerability. This can be seen in the repository named "vulnerable-project".

