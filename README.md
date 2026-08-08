# Default community health files

GitHub serves the files here to any repository on this account that does not ship its own copy.

`.github/ISSUE_TEMPLATE/` holds three issue forms:

- `bug_report.yml` for something that already behaves differently from what a person expected.
- `feature.yml` for a new capability, written as a user story.
- `task.yml` for technical work with no direct user story, such as an upgrade or a migration.

Do not edit them here. The source of truth is `github/ISSUE_TEMPLATE/` in the
`opinionated-configs` repository. Run its `doctor.sh` to see whether this copy is current, and to
get the command that republishes it.

A repository opts out by adding its own `.github/ISSUE_TEMPLATE/` folder. One file in that folder
replaces this whole template set for that repository.
