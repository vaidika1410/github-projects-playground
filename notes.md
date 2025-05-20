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

**🔃 Creating Pull Requests (PRs)**

A Pull Request is a way to propose changes you've made in a branch to be merged into the main codebase (usually the main or master branch). It enables code review, collaboration, and controlled updates.

✅ Steps to Create a Pull Request:
- Create a New Branch
- When you create or edit a file in someone else's repository (or even your own), GitHub will automatically create a new branch—often named patch-1, patch-2, etc.
- Commit Changes to That Branch
- You write your changes and commit them to this new branch.
- Open a Pull Request
- After committing, GitHub will prompt you to “Compare & pull request.”
- Add a title and description explaining what your changes do.
- Submit the PR.

👀 What Happens Next?
- The repository owner or collaborators will see your pull request.
- They can review your changes, suggest edits, or approve it.
- If approved, they can click “Merge pull request” to add your changes to the main branch.
- If not suitable, they may close the pull request or ask for revisions.

💡 Notes:
PRs are essential in open source for maintaining quality and collaboration.
Always include clear commit messages and descriptions to help reviewers.
Use PRs even in your own projects when following a team-like workflow or CI/CD automation.

**💬 Saved Replies (GitHub)**

🔹 What Are They?
Pre-written responses you can quickly insert in issue or PR comments—great for saving time and staying consistent.

⚙️ How to Enable:
  Go to Profile → Settings → Saved replies.
  Click “Add saved reply”, give it a title and message, then save.

💡 How to Use:
  In any issue or PR comment box, click the 💬 icon, then choose a saved reply.
  You can edit the message before posting.

✅ Use Cases:
  Bug acknowledgment
  Contribution tips
  Common responses
  Feature request replies
