# Health Files

Health files are automatically created in repository that either belong to you or your organization.

You create them by making a public repository called .github. You can then add many types of default files:

I believe the most relevant ones for Swissgrid are:

### CODE_OF_CONDUCT.md

The following topics could be mentioned in the case of Swissgrid:

- Remind employees of the mission of the company.
- Remind of compliance and security rules that need to be followed.
- Remind of the type of communication that is expected when working in project involving multiple people.

In general, points that are important in an employee handbook can be mentioned here.

### CONTRIBUTING.md

This can be used as a clear reminder of the rules that need to be followed in order to properly contribute to a project.

This can be a place to mention:

- Development environment 
- Style guide for commits and pull requests

### Security.md

This can be used as a place to mention specific security considerations, or a possible reporting path different from the default one.

## Pull request template / issue templates

Templates can be given for PRs and issues, pushing users to give information in a certain way.

## Enforcement

In general, I would place these health-files in two different categories:

- Those for which a default should be used.
- Those for which a custom version is required.

A default version for the first category can be placed in the .github repository.
A github action can then check the individual presence of those in the second category.

I would use an organization-wide rule set which would only allow merging to master if the actions passes.
These files and the workflow can be found in the repository in this organization.

## Communication

Since the change would effectively block new development when implemented, it would likely be needed to make this a multi-step approach, with small adaptions to the script.
For example, a first version could not block merges entirely, but fail and create a GH-issue indicating the need for a change. The second version, implemented after a certain grace period, would fully block non-compliant merges through a organization-wide rule set.

Teams need to enforced well in advance of the upcoming changes.
