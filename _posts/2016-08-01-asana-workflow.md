---
title: 'Quick-start guide: Basic development workflow in Asana.'
category: Process
---

## {{ page.title }}

This guide is a quick overview of using Asana in a
basic development process.

This does not cover workflows involving customer validation and modifcations that are often made
when A/B testing a piece of an application.

This guide attempts to avoid pushing any particular development methodology,
and is meant to be altered to suit your needs, whether you do
2-week sprints, or assess your priorities daily.

### Asana interface layout

All your projects are listed in the sidebar on the left.
Generally there's a 'Backlog' project, as well as one or more 
named with a date or time period (i.e. a month name).

To the right of the sidebar towards the center of the screen
are the tickets for the selected project.
Once a ticket is selected, its details will appear to the right, such as
due date, assignee, ticket description, attachments and conversations about the ticket.

![Asana interface]({{ site.url }}/assets/images/articles/asana-workflow.png){:width="90%"}

### Workflow overview

The basic development flow consists of product developers and managers adding
tickets to the Backlog. This can be a feature, a bug, a copy change,
or any change that development may make.

When it has been decided that a ticket should be performed and is
ready to go (meaning details have been fully flushed out),
it gets moved from the 'Backlog' project to the active 
project.

There is always one active project that developers are working from.
Depending on the project and development style, it's often named based on a start
day, or a time frame. For weekly or bi-weekly sprints, the active project might be named
'2016/08/22'. The next week, you would have a new project named '2016/08/29'. Or you may
use month projects named after the moth it's for.

### The life of a ticket in the active project

When a ticket is first moved from the Backlog to the active project, it gets
placed in the 'Ready' section.

When I developer has time available, they are free to pull a ticket from the
'Ready' section and move it to the 'In-progress' section. If it wasn't already assigned to 
them, they should assign it to themselves at this time so others know who
is working on it.

Once the ticket is complete, the developer will move it on down through the sections
as called for by the project. For example, tickets may go through a flow that looks like this:
In-progress -> On staging -> Deployed, at which point they can be marked complete.

Note: It can be helpful to set Asana to lit  'All tasks' so that you can continue
to see the ones that have been marked complete. Since they're off in there own section, they 
won't be in the way.

### Conclusion

This is a basic development flow using Asana, and should be altered to suit your needs. That said,
this flow works as is in many, many situations.

If you aren't already using a flow like this, give it a shot, then share the results with us!
