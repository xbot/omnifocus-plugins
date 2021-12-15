# omnifocus-plugins

## Generate work journal

`generate-work-journal.omnijs`

Aggregate all tasks completed today under folder named `Work`, then put the result into clipboard.

Each line starts with a task name, ends up with a status description except for an interview task. An interview task is identified by containing a substring called `面试`. The status description will always be `完成` except when there is a note for the task, the note content will be used in this condition.

`open-jira-ticket.omnijs`

Open Jira ticket for the selected task or project. The project name must begin with a form like 'DEV-XXXX'.

First of all, Jira URL must be set before using this plugin. Hold the CTRL key and click the menu item `Automation` → `Open Jira Ticket` to open the preferences dialog.
