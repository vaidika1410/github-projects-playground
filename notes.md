**GitHub Project Management – Course Notes**
Sub-course from: Career Essentials in GitHub (LinkedIn Learning)
Instructor: Ray Villalobos

**🔷 Two Types of GitHub Projects**
1. Classic Projects
Kanban-style boards (e.g., To do → In progress → Done)
Issues and pull requests are added as cards
Basic automation (e.g., move to “Done” when PR is merged)
Limited filtering, no custom fields
Best for small teams or simple task tracking

2. New GitHub Projects (Modern/Beta version)
Database-like with multiple views: Table, Board, Calendar, Roadmap
Fully customizable: fields, filters, sorting
Supports custom fields (e.g., priority, status, estimate)
Advanced automation and integrations
Ideal for larger teams, complex workflows, or product roadmaps


**📁 GitHub Project Templates (in new Projects)**
When creating a new project, GitHub offers three templates:

-> Team Task Board
- Kanban view with status columns
- For tracking to-dos and progress across a team
- Feature/Release Roadmap
- Timeline-based view
- Great for planning product launches and sprints

-> Personal Task Board
- Simplified, table-based layout
- Meant for individual contributors managing their own tasks

**👥 Project Access & Sharing with Teammates**
Projects can be shared with individuals, teams, or made public (for org-wide visibility).

Roles:
Admin: Full control, including field config and settings
Write: Can edit items, status, fields
Read: View-only access

Use @mentions in items for team collaboration

Projects can span across multiple repositories in an organization

**❓How to use GitHub issues with project management?**
From the views of project management, we can use any view to raise an issue for any github repositories. Lets say github-projects-playground is my repo for which I wanna raise issues, then I'll use the repo managing my projects ( say project-management-practice ) , and from the tasks, I can easily assign an issue to it.
The github-projects-playground will now show all the history of the project in the issues section.

We can also set milestones from the github-projects-playground repo.
**🏁 What Are Milestones in GitHub Issues?**
Milestones in GitHub are a way to group related issues and pull requests into a single goal or deadline. Think of a milestone as a target or phase in your project—like a release, sprint, or major feature completion.

✅ Purpose of Milestones:
- Track progress toward a specific goal or deadline
- Organize work around releases, sprints, or features
- Measure how many issues/PRs are done vs pending for that milestone
- Add a layer of planning to your issue management

Whenever an issue is closed, the milestone is completed and the issue or task moves to the correct status tag automatically.

- When we add any assignees, we directly contact them using the **Add a comment** option in the Issues section.
  The use of '@' sign allows us to mention an assignee and the '#' sign allows us to mention an issue.
