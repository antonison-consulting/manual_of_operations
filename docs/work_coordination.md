# Work Coordination and Prioritization

## Overview

[Trello](https://trello.com/b/6Ui67y6w/game-changer-scheduling) will be used for managing work related to GCS.  Trello is both an easy to use and fully featured Kanban tool.

## Ownership

Jami owns the prioritization of the Backlog.

## Process

1. When a unit of work comes up, a card should be created in Trello and placed at the bottom of the backlog.  This supports letting everyone know what is currently being worked on.
   1. A ticket should have a brief description of the work to be done and a label indicating the kind of work.
      1. project-management: Work related to project coordination
      2. product-design: Work related to determining application features and UI
      3. software: Work related to writing software
      4. devops: Work related to IT infrastructure, development workflow, or deployments
      5. data-algorithms: Work related developing algorithms or data modeling
   2. If a ticket needs to be moved up in the Product Backlog, please coordinated with Jami to ensure what work it should come in front of and to ensure any previously planned work is adjusted.
2. When ready, a ticket(s) should be pulled from the top of the Backlog and pulled into `To Do`.  At this point in a time, a `Due Date` should be added to the ticket to indicate how long this will take.  If multiple tickets are selected, although not required it would be helpful to also set `Start Dates`.
3. When work begins, an issue should be pulled into `In Progress`.  A ticket should stay in this lane until it is either ready for review or if it is decided the work will no longer be done.  A person should also be assigned to this ticket.
4. Once the work is complete, it should be placed in `Review`.
   1. If the ticket is not connected to a Pull Request, keep feedback comments in the ticket.
   2. If a ticket is tied to a GitHub pull request, please connect the `Pull Request` to the ticket and keep comments related to it in the `Pull Request.
5. Once complete, place the ticket in the `Done` lane.