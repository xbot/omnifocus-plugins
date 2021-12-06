# omnifocus-plugins

## Generate work journal

`generate-work-journal.omnijs`

Aggregate all tasks completed today under folder named `Work`, then put the result into clipboard.

Each line starts with a task name, ends up with a status description except for an interview task. An interview task is identified by containing a substring called `面试`. The status description will always be `完成` except when there is a note for the task, the note content will be used in this condition.
