# Open Services Group SCRUM

This repository contains information on how we implement SCRUM and holds issues for sprints.
Sprints are planned in the [SCRUM BOARD].

# TL;DR;

1. check the stakeholder backlog for issues assigned to you and well define them so that they can be prioritized
2. keep your assigned issues in the other columns updated
3. once done, move it to the `Done` column - don't do it just prior to the meeting
4. come [prepared] to the sprint meeting

## Asynchronous work

This work happens all the time and *not* during the sprint planning meeting.

### Stakeholder Backlog
The goal of the [Stakeholder Backlog] is to collect issues and ideas (notes) from all Stakeholders/ users/ contributors/ etc..
Issues and ideas can be unprioritzed, unsorted and even not well defined.
The [Product Owner] reviews them regularly and decides, which of these need more attention, need more details and/ or need to be worked on (prioritized).

  1. all issues start in the Stakeholder Backlog
  1. all new and unassigned issues are reviewed by the [product owner] ([PO])
  1. the product owner decides if an issue is well defined and needs to be prioritized
     1. if an issue is well defined, the [PO] sets the label to `triage/accepted`
     1. if an issue is not well defined, the [PO] assigns it to a contributor e.g. for decscribing it better or get more details
        1. This loop continues until the [PO] sets the label `triage/accepted` and leaves it unassigned
     1. if an issue is well defined `triage/accepted` and is prioritized by the [PO], the [PO] moves it to the [Product Backlog]
  1. all assigned issues have to be completed by the assignee and unassigned once ready for review

### Product Backlog
The goal of the [Product Backlog] is to have a collection of well defined (`triage/accepted`) and ready to be worked on issues.
 - Issues in the [Product Backlog] are prioritized and need to be worked on in the next sprints.
 - During the [Sprint Planning] these issues can be moved to the [Sprint Backlog].
 - The [Product Backlog] holds only issues;
these issues must be `triage/accepted`, but they don't need to be "assigned" to any person yet.

### In Progress
The goal of [In Progress] is to see, which issues are currently worked on.
 - During the [Sprint Planning] issues are assigned and moved to the [Sprint Backlog].
 - All issues in the [Sprint Backlog] will be worked on during the [Sprint].
 - When an assignee actively works on one or more of his/her/* issues, the assignee moves the issue to [In Progress].

### Done
The goal of [Done] is to collect all the solved issues.
 - Issues here are ready to be tested/ checked/ approved by the Stakeholder (creator of the issue in general). 
 - Solved is defined as: the assignee took care of all the mentioned acceptance criteria during the sprint.
 - The assignee defines solved and moves the issue from [In Progress] to [Done].
 - The [PO] checks the [Done] issues regularly and informs the `Stakeholder` to check/test the solution for the issue:
   - This can be delegated to/ done by the issue assignee.

### Prior to the Sprint Planning / Review meeting
1. All: Go through all issues that are assigned to you
   1. in [Sprint Backlog]
      1. are you working on an issue? --> move it to [In Progress]
   1. in [In Progress]
      1. is an issue solved? --> move it to Done
   1. in [Done]
      1. talk to the [PO] or `Stakeholder` (creator of the issue in general) of the issue, if the provided solution is accepted [Approved by Stakeholder]
 1. All: Go through all issues that are not assigned to you
    1. in [Done]
       1. +1 or -1 any issue
    1. in [Product Backlog]
       1. understand the issues here
       1. do they fit your skills/ goals
       1. be prepared to talk about them/ discuss complexity/ estimates
 1. [PO]
    1. [Stakeholder Backlog] see above: check priority and well defined; assign or label or/and move to [Product Backlog]
    1. [Done] see above: inform `Stakeholder` about the solved issues and request 

### Sprint
The [Sprint] is the time period between Sprint Planning and Sprint Review.
We will use a 2 weeks period.
We combine the Sprint Planning and the Sprint Review into one meeting at the beginning of every other week.
During the [Sprint] the assignees work on their issues that are in the [Sprint Backlog].
As a rule of thumb, an issue needs to have 13 or less Story Points (see [Glossary] & [Story Points Estimates]) to be solvable in one [Sprint] (two weeks).
Therefore an associate can have only 13 or less Story Points alltogether in one [Sprint].
These are just general guidelines. Over time each team can find its own rules and time estimates ([Velocity])


### Approved by Stakeholder
tbd

#### During the [Sprint]
tbd

### Backlog Refinement Session
Goal of [Backlog Refinement Session] is to understand issues better if needed and split issues bigger than 13 Story Points (= Epics) into smaller issues (<= 13 Story Points).
This will lead to issues that can be direct worked on (allow them into the [Product Backlog])

tbd: when, who and how - hands on

---

## Synchronous work

### Sprint Planning / Review meeting
Goal of the Sprint

#### Review 
#### Sprint Planning

#### During the meeting

1. issues in the `Done` column with a -1 are discussed and all other issues are closed out
2. issues in the `Product Backlog` are assigned and moved to the `Sprint Backlog`

#### Sprint Backlog

## Product Owner
The [Product Owner] is repsonsible for:
 - Priorizing issues: Move it from [Stakeholder Backlog] to [Product Backlog]
 - Well defined: Approve an issue or Request a better defintion --> set `triage/accepted` label
 - Check or delegate the [Approved by Stakeholder]

[@goern](https://github.com/goern) and [@durandom](https://github.com/durandom) are product owners

## Glossary
PO - Product Owner
well defined issue - an issue that has enough details, understanding of the problem, that it can be used in the [Product Backlog](#product-backlog)
Story Points - Effort estimation for an issue.  [Glossary] 

## The Scrum Board
[SCRUM BOARD]
| Stakeholder Backlog | Product Backlog | Sprint Backlog | In Progress | Done | Approved by Stakeholder | Closed |
|---------------------|-----------------|----------------|-------------|------|-------------------------|--------|
|                     |                 |                |             |      |                         |        |

# Further reading
The Thoth team practiced SCRUM and maintains their [Terms and Conditions](https://github.com/thoth-station/core/blob/master/docs/TermsAndConditionsForTheScrum.md), which we can build upon.

[SCRUM BOARD]: https://github.com/orgs/open-services-group/projects/21/views/1
[product owner]: #product-owner
[PO]: #product-owner
[prepared]: #prior-to-the-meeting
[Glossary]: #glossary
[Product Backlog]: #product-backlog
[Stakeholder Backlog]: #stakeholder-backlog
[Sprint Backlog]: #sprint-backlog
[Sprint Planning / Review meeting]: #sprint-planning-/-review-meeting
[Sprint Planning]: #sprint-planning
[Sprint]: #sprint
[In Progress]: #in-progress
[Done]: #done
[Approved by Stakeholder]: #approved-by-stakeholder
[The Scrum Board]: #the-scrum-board
[Story Points Estimates]: https://github.com/thoth-station/core/blob/master/docs/TermsAndConditionsForTheScrum.md#estimates
[Velocity]: https://www.scrum.org/resources/blog/agile-metrics-velocity
[Backlog Refinement Session]: #backlog-refinement-session
