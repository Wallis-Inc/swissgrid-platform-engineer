# Scanner

The first part can easily be solved with a script that does the following:

- List all repositories from the org.
- Iterate through list and mark those using the action.
- Export the repository name + owner 

The second part can be solved by using action permissions on the organization level.

Depending on how restrictive the organization would like to be, it would be possible to either selectively add actions which are allowed or banned.
In this case, it might be wiser to selectively allow which actions are permitted.

The communication to the users could be done in the following format:

Dear XX,

We are reaching out to you today because of a vulnerability which was recently uncovered in a Github Action used in a repository for which you are a maintainer.

As security is a top priority for us, this action has been removed from the list of allowed actions.

Since we do not know whether this vulnerability will be patched, we recommend you change your workflow using action not-buggy-action/do-not-expose-password instead.

We thank you for your understanding, and remain at your disposal in case of questions.

Your platform team.
