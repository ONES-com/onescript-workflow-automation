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
- Validate workflow transitions against registered, estimated, and remaining work

## Download ONEScript

Download the latest ONEScript package from [Releases](https://github.com/ONES-com/onescript-workflow-automation/releases).

For the shortest path, use the release links:

- [Latest release](https://github.com/ONES-com/onescript-workflow-automation/releases/latest)
- ONEScript v1.2.0 on-premises package: [`ONEScript-1.2.0-on-prem.opk`](https://github.com/ONES-com/onescript-workflow-automation/releases/download/v1.2.0/ONEScript-1.2.0-on-prem.opk)
- [ONEScript v1.2.0 release notes](https://github.com/ONES-com/onescript-workflow-automation/releases/tag/v1.2.0)

Install the package through Configuration Center > App management > Uploaded apps. GitHub may also show auto-generated source archives; to install ONEScript, download the `.opk` package.

## What's New in v1.2.0

ONEScript v1.2.0 includes bug fixes and general reliability improvements.

Recent v1.1 releases also added status transitions, workspace reliability updates, scripted field improvements, Cursor-based issue search, OAuth Endpoint Caller updates, and complete worklog support. See the [Changelog](./changelog) for version-specific details.

## Install Notes

Before installing ONEScript v1.2.0:

- Review the [v1.2.0 compatibility requirements](./changelog/v1.2.0.md#compatibility). The package installation floor does not guarantee support for every feature.
- Download the `.opk` package from GitHub Releases.
- Upload, install, and enable ONEScript from Configuration Center > App management > Uploaded apps.

## Start Here

- [Get started](https://docs.ones.com/onescript/get-started)
- [Install ONEScript](https://docs.ones.com/onescript/get-started#install-onescript)
- [Write and manage scripts](https://docs.ones.com/onescript/guides)
- [Reference](https://docs.ones.com/onescript/reference)
- [Migrate Jira scripts to ONES](https://docs.ones.com/onescript/migration)
- [Cookbook and resources](https://docs.ones.com/onescript/resources)
- [Changelog](./changelog)

## Availability

ONEScript v1.2.0 is available for Private / On-Premises deployments. SaaS support is coming soon.

ONEScript is in early preview and intended for evaluation and testing.

## Feedback

Share use cases, Jira migration questions, and ideas in [Discussions](https://github.com/ONES-com/onescript-workflow-automation/discussions).

Report reproducible issues, installation problems, documentation fixes, and package-related requests in [Issues](https://github.com/ONES-com/onescript-workflow-automation/issues).

## Useful Links

- [ONEScript documentation](https://docs.ones.com/onescript)
- [ONEScript introduction](https://ones.com/features/scripting)
- [ONES Developer docs](https://docs.ones.com/developer/guide/getting-started/)
- [ONES.com](https://ones.com/)
