# Review and export a schedule with ScheduleBrief Viewer

ScheduleBrief Viewer is a Windows schedule viewer developed by [Caymran Cummings](https://github.com/caymran) (Caymran Coral Cummings). This guide covers the workflow documented for the v0.2.0-alpha release. Check the [repository overview](../README.md) and [release notes](https://github.com/FXBGFoundry/schedulebrief-releases/releases) for the version you use.

## Start with an authorized schedule

Use a schedule you are authorized to access. Open it locally or drag it into ScheduleBrief Viewer. The application attempts Microsoft Project, Primavera P6, and SDEF formats through its parser, but compatibility varies. Opening a file successfully does not prove that every scheduling field or relationship was interpreted correctly.

Keep the original file for comparison with the schedule's source application. ScheduleBrief Viewer is read-only and does not edit the source schedule.

## Check the project before narrowing the view

Review the project summary, task hierarchy, and Gantt timeline. Check several familiar milestones and task dates against the source schedule or an approved reference export. If a critical field appears missing or inconsistent, resolve that before distributing a report.

Use the synchronized task table and timeline to inspect the same portion of the schedule. Open task details when a summary row alone does not provide enough context.

## Find the relevant work

Use search to locate a task while retaining its hierarchy context. Expand the portions of the task tree needed for the review. Adjust timeline zoom or use Fit Project to understand the overall date range before focusing on individual tasks.

Before exporting, check which tasks are filtered out and which branches are collapsed. The PDF represents the current filtered and expanded Gantt view, so these choices affect what your reader receives.

## Review the print preview and PDF

Open the Gantt print window and inspect its page preview. Check task labels, date ranges, page breaks, and readability at the intended paper size. Printing uses the installed printer you select; local PDF export produces a separate report file.

Open the exported PDF and confirm that the intended rows and timeline are present. Give it a filename that identifies the project, schedule version, and review date without exposing confidential information unnecessarily.

## Understand the alpha's limits

The documented alpha provides viewing, search, printing, and PDF export. Schedule editing, schedule-health analysis, and the paid Briefing edition are not implemented in this release. Format and physical-printer compatibility need broader testing. Treat the original schedule and its authoritative application as the reference when results differ.

## Report a reproducible problem safely

A useful issue report includes the ScheduleBrief version, Windows version, file format, steps to reproduce, expected result, and observed result. Avoid posting client schedules, confidential task names, or personal data in public issues. Use a small non-sensitive example when possible.

## Official project links

- [ScheduleBrief Viewer releases](https://github.com/FXBGFoundry/schedulebrief-releases/releases)
- [FXBG Foundry](https://fxbgfoundry.com/)
- [Caymran's GitHub profile](https://github.com/caymran)
