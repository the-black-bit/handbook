Scheduling message.
In progress tasks should have deadline.
In progress is set in daily.
Status notes

# Commit-m project board Template

Why should we keep our tasks up to date?
* Tracking the progress of work.
* Transparency and alignment.

## Views

### Daily

Columns
* Title
* Assignee: If there are two assignees, break the task. For pair-programming new task.
* Status: [See "Task Statuses" Below](#task-statuses)
* Notes: Explanatory notes for pending status.
* Priority
* Deadline
* Estimate
* Actual

### Milestones

### Planning

## Attributes

## <a name="#task-statuses"></a>Task Statuses:

| Status         | Required Columns      | Meaning                                                     | Process                                                                                                                               |
| -------------- | --------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| Future         | Title, Brief Desc     | #TODO comments in codebase, ideas for when backlog runs dry | Regularly review and prioritize during sprint planning to determine when they move to "Backlog" or "Ready"                            |
| Backlog        | Clear Desc, Priority  | Well-defined and Prioritized tasks for the next sprint      | Refine, break down into smaller tasks, change status to New at the begining of the sprint when they are assigned.                     |
| New            | Assignee, Estimate    | Tasks chosen for the current sprint.                        | Well-defined, clear scope, to be reviewed by the assignee, has initial estimate which will be reviewed by the assignee                |
| Pending        | Notes                 | Tasks awaiting specific event/action to proceed             | Clearly document reason, identify resolution needed to move task forward, the person that is supposed to resolve it and timeline.     |
| Ready          |                       | Tasks ready for team execution, Estimate is accurate        | Ensure dependencies are met and scope is well-understood and estiamte is good enough                                                  |
| Blocking       | Notes                 | Tasks blocking other tasks                                  | Give more priority and collaborate to address and unblock the pending task                                                            |
| In Progress    | Deadline              | Tasks actively being worked on                              | Provide updates, communicate challenges, seek help if needed to ensure smooth progression                                             |
| In Review      | Actual                | Completed tasks under quality assurance                     | Conduct thorough reviews, address feedback, ensure tasks meet acceptance criteria before marking as "Done"                            |
| Done           |                       | Successfully completed tasks                                | Celebrate completion, gather feedback for improvement, archive task details for future reference                                      |
| Failed         | Actual                | Unsuccessful tasks                                          | Conduct retrospective, analyze reasons for failure, identify lessons learned, take corrective actions to prevent similar failures     |


### Additional Guidelines:
- Updating Task Deadlines: Whenever a task's deadline is changed, ensure that a comment is added under the task explaining the reason for the change and indicating the initial deadline value.
- Communication: Maintain active communication within the team regarding task statuses, progress updates, and any impediments faced to facilitate collaboration and alignment.

By adhering to these defined task statuses and processes, the Scrum team can effectively manage their work items, monitor progress, and proactively address any issues or challenges that may arise during the sprint cycle. 🛠️🚀
