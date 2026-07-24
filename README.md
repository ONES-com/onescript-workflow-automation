# ONEScript Workflow Automation

ONEScript is the scripting layer for ONES. It helps administrators, power users, and developers automate and extend ONES workflows beyond what no-code rules can express.

Use this repository to download ONEScript packages, find the official documentation, and share feedback while ONEScript is in early preview.

## What You Can Automate with ONEScript

Use ONEScript when no-code automation is not enough for your workflow logic.

- Update fields, comments, and related data based on work item changes
- Enforce workflow rules before or after users make changes
- Run scheduled jobs and data queries across ONES
- Connect ONES with external systems through REST endpoints
- Migrate Jira ScriptRunner, JMWE, or Power Scripts automation logic to ONES
- Draft scripts with an AI assistant, then validate and test them in ONEScript
- Search issues semantically, send ONES email notifications, and build scheduled follow-up automations

## Download ONEScript

Download the latest ONEScript package from [Releases](https://github.com/ONES-com/onescript-workflow-automation/releases).

For the shortest path, use the release links:

- [Latest release](https://github.com/ONES-com/onescript-workflow-automation/releases/latest)
- ONEScript v1.1.0 on-premises package: [`ONEScript-1.1.0-on-prem.opk`](https://github.com/ONES-com/onescript-workflow-automation/releases/download/v1.1.0/ONEScript-1.1.0-on-prem.opk)
- [ONEScript v1.1.0 release notes](https://github.com/ONES-com/onescript-workflow-automation/releases/tag/v1.1.0)

Install the package through Configuration Center > App management > Uploaded apps. GitHub may also show auto-generated source archives; to install ONEScript, download the `.opk` package.

## What's New in v1.1.0

ONEScript v1.1.0 consolidates the improvements since v1.0.4 into a Private / On-Premises release.

- Adds `issue.search(...)` semantic issue queries with `select` field projection for event, timer, and console triggers
- Adds `api.notify(...)` email notifications through the official ONES notification channel
- Supports scheduled semantic queries, such as timer-based overdue-issue follow-ups
- Adds `issue.hierarchy()`, hierarchy and date guards, `newValue`, and `all` / `any` / `none` status predicates
- Moves the ONEScript workbench into the system sidebar and gates access through the ONEScript Workbench Access permission
- Improves full-screen mode, log and output viewers, execution-pulse display, and zh-CN / ja / en localization

## Upgrade Notes

After upgrading to v1.1.0:

- Grant workbench access in the app's Permission tab before members open ONEScript.
- Open ONEScript from the left sidebar instead of the plugin configuration tab.
- Review `taskPreAction` scripts: `issue.*` now reads the pre-action state, so incoming values should use `.newValue` or `changedTo(...)`.

## Start Here

- [Get started](https://docs.ones.com/onescript/get-started)
- [Install ONEScript](https://docs.ones.com/onescript/get-started#install-onescript)
- [Write and manage scripts](https://docs.ones.com/onescript/guides)
- [Reference](https://docs.ones.com/onescript/reference)
- [Migrate Jira scripts to ONES](https://docs.ones.com/onescript/migration)
- [Cookbook and resources](https://docs.ones.com/onescript/resources)
- [Changelog](./changelog)

## Availability

ONEScript v1.1.0 is available for Private / On-Premises deployments. SaaS support is coming soon.

ONEScript is in early preview and intended for evaluation and testing.

## Feedback

Share use cases, Jira migration questions, and ideas in [Discussions](https://github.com/ONES-com/onescript-workflow-automation/discussions).

Report reproducible issues, installation problems, documentation fixes, and package-related requests in [Issues](https://github.com/ONES-com/onescript-workflow-automation/issues).

## Useful Links

- [ONEScript documentation](https://docs.ones.com/onescript)
- [ONEScript introduction](https://ones.com/features/scripting)
- [ONES Developer docs](https://docs.ones.com/developer/guide/getting-started/)
- [ONES.com](https://ones.com/)
