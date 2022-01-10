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

`search-flomo-by-project.omnijs`

Search in Flomo according to the selected project or the containing project of the selected task.

You must set settings in the preferences dialog before this plugin works.

In macOS, hold the CTRL key and click the menu item `Automation` → `Search Flomo` to open the preferences dialog.

In iOS, tap the console icon in the home perspective, then tap the corresponding menu item.

### Settings

`Pattern` is a regular expression which will be used to match the selected project name.

`Keyword template` is a string template, the matched results will be used to fill this template and then be used to search in flomo as a keyword.

`Tag` is the name of a tag in Flomo, this option is optional, if set, it will be appended to the query URL to filter the results as an additional dimension.

## Convert selected tasks to projects

`convert-tasks-to-projects.omnijs`

Convert selected tasks to projects and put them into the chosen folder or the end of the library.

## Reset review status

`reset-review-status.omnijs`

Reset review status of projects under selected folders.

## Rearrange timescales of selected projects or tasks

`rearrange-object-timescales.omnijs`

Currently, the timescales are fixed. The selected projects or tasks can be rearranged to Morning, Noon, Afternoon, Evening, Daytime or Whole Day of the chosen date.
