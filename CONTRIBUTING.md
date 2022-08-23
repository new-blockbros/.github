# Contributing to New Block Bros

Thank you for your time to contribute the New Block Bros project!

Please read and obey rules described below before your contribution.

## Link with Trello board

In [Trello board](https://trello.com/b/nE04Jlfa/new-block-bros-roadmap), pick up a task you want to work on.

Then, move the card to `🚧 In progress` section and assign your account to that card.

Once you create a branch and PR in GitHub, please link those from Trello card.

After the PR is merged, please move the card to `✅ Completed` section.

## Branch names

To make CD work correctly, a branch name may only contain lowercase alphabet letters ([a-z]), digits ([0-9]), hyphens (-) and underscores (\_).

It must begin and end with a letter or digit.

If you mistakenly open a PR with a invalid branch name, please rename your branch to a valid name and reopen a PR.

## Format codes

Please format your codes with Prettier to make them look consistent.

You can apply Prettier by either of the following:

- Configure Prettier in your code editor to format on save (Recommended)
- Run `npx prettier -w .` in `web` directory

Please run `go fmt` in `client` directory to format Go files.

## Open pull requests

Always open pull requests.

**DO NOT push your changes directly to the `main` branch.**

Opening pull requests or push codes to a non-default branch triggers CI / CD workflows.

Please request more than one reviewer.

Please re-request review and **wait for approval** once you push new changes.

**Please make sure that all CI / CD checks have passed and changes are approved by more than one reviewer** before merging your branch into `main`.

## Separate concerns

**DO NOT mix different kind of changes into one commit / pull request.**

Please make sure that one commit / PR does only one "what you want to do".

## Follow the Go convention

When you write Go, please follow the Go convention like [Effective Go](https://go.dev/doc/effective_go).

## How to join us

If you are interested in joining us as a developer, please contact us at [our Discord server](https://discord.gg/tG4uaJxvSN).
