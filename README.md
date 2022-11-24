# omnifocus-plugins

## Generate work journal

`generate-work-journal.omnijs`

Aggregate all tasks completed today under folder named `Work`, then put the result into clipboard.

Each line starts with a task name, ends up with a status description except for an interview task. An interview task is identified by containing a substring called `面试`. The status description will always be `完成` except when there is a note for the task, the note content will be used in this condition.

## Open Jira ticket

`open-jira-ticket.omnijs`

Open Jira ticket for the selected task or project. The project name must begin with a form like 'DEV-XXXX'.

First of all, Jira URL must be set before using this plugin.

In macOS, hold the CTRL key and click the menu item `Automation` → `Open Jira Ticket` to open the preferences dialog.

In iOS, tap the console icon in the home perspective, then tap the corresponding menu item.

## Search in Flomo by project

Search in Flomo according to the selected project or the containing project of the selected task.

[xbot/omnifocus-plugin-find-in-flomo](https://github.com/xbot/omnifocus-plugin-find-in-flomo)

## Convert selected tasks to projects

Convert selected tasks to projects and put them into the chosen folder or the end of the library.

[xbot/omnifocus-plugin-convert-to-projects](https://github.com/xbot/omnifocus-plugin-convert-to-projects)

## Reset review status

`reset-review-status.omnijs`

Reset review status of projects under selected folders.

## Rearrange timescales of selected projects or tasks

`rearrange-object-timescales.omnijs`

Currently, the timescales are fixed. The selected projects or tasks can be rearranged to Morning, Noon, Afternoon, Evening, Daytime or Whole Day of the chosen date.

## Checklist

Make OmniFocus work as a checklist App.

[xbot/omnifocus-plugin-checklist](https://github.com/xbot/omnifocus-plugin-checklist)
