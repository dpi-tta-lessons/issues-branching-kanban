# Mastering GitHub Workflow: Issues, Branches, and Kanban Boards

<!-- TODO: ISSUES
- way to break up work
- backlog of work to do
- title, description, comment thread
- assign
- prioritize

-->

<!-- TODO: BRANCH NAMING
- standard conventions
  - `<issue-number>-<initials>-<description>
  - `feature/description`
  - refer to readme contribution guidelines
  - etc.
-->

## Kanban Boards

Kanban boards are visual tools that help manage workflow efficiently. They use cards and columns to represent tasks and their stages of progress. The main benefits of Kanban boards include:

1. **Visualization**: Makes it easy to see the status of work items.
2. **Workflow Management**: Helps manage tasks from start to finish.
3. **Limiting Work in Progress (WIP)**: Encourages teams to focus on completing tasks before starting new ones.
4. **Continuous Improvement**: Provides a visual representation of bottlenecks and inefficiencies, allowing teams to improve processes continuously.
5. **Prioritize**: Vertical position of issues on the board may indicate priority

## GitHub Project Boards

![Creating a Project Board](assets/kanban_board_example.jpeg)

GitHub Project Boards bring the power of Kanban boards into the realm of software development. They offer a flexible way to organize and prioritize your work. Here’s how you can use GitHub Project Boards to manage your projects:

### Creating a Project Board

1. Navigate to the main page of your repository.
2. Click on the **Projects** tab.
   
![Creating a Project Board](assets/tab-projects.jpeg)

4. Click **New Project**.

![Creating a Project Board](assets/new_project_button.jpeg)

6. Choose a template (**Kanban**, **Team planning**, etc.) and name your project.

### Adding Columns

1. Click **+** to the right of the columns.

![Creating a Project Board](assets/add_column.jpeg)

3. Name your column (e.g., To Do, In Progress, Done).
4. Repeat for additional columns.

### Adding Items

- Items represent tasks and can be added to columns.
- Click on **+ Add item** at the bottom of a column to create a new item.

![Creating a Project Board](assets/add-item.jpeg)

## Linking Issues to the Project Board

Issues can be linked to project boards to track work items. Here's how to do it:

### Directly from the Issue

1. Navigate to an issue within your repository.
2. On the right-hand side, look for the **Projects** section.

![Creating a Project Board](assets/linking_issue_to_project.jpeg)

4. Click the wheel icon and select the desired project(s).
5. You can change the status and additional information from this view as well.

### From the Project Board

1. Go to your project board.
2. Click on **+ Add item**.
3. In the **+ Add item** dialog, you can search for the repository and the existing issues to add.

## Linking Pull Requests to the Project Board

Just like issues, pull requests can also be linked to project boards:

### Directly from the Pull Request

1. Navigate to a pull request within your repository.
2. On the right-hand side, look for the **Projects** section.
3. Click the wheel icon and select the desired project and column.

### From the Project Board

1. Go to your project board.
2. Click on **+ Add item**.
3. In the "+ Add item" dialog, you can search for the repository and the existing pull requests to add.

## Practical Example

Let’s go through a practical example to understand how to set up and use a GitHub Project Board:

### Creating a Project

1. Go to your repository on GitHub.
2. Click the **Projects** tab.
3. Click **New project**, name it "Development Workflow", and choose the **Kanban** template.

### Adding Columns

- You will have three default columns: "To do", "In progress", and "Done".
- You can add more columns if needed by clicking "+" to the right of the columns.

### Creating and Linking Issues

1. Go to the **Issues** tab in your repository.
2. Create a new issue, for example, "Set up development environment".
3. In the issue, link it to your project by clicking the wheel icon in the **Projects** section, filter projects and search for the project you would like to link, and change the status.

### Moving Issues Across Columns

- As you start working on the task, move the issue from "Todo" to "In progress".
- Once the task is completed, move it to the "Done" column.

### Linking Pull Requests

1. When you create a pull request for the issue, link it to your project board in the same way.
2. This helps in tracking the progress of your code review and merge process.

## Quiz

- What are Kanban boards primarily used for?
- Managing workflow
  - Correct! Kanban boards help visualize and manage tasks throughout their stages.
- Writing code
  - Not correct. Kanban boards are not necessarily used to write code.
- Creating databases
  - Not correct! Kanban boards do not manage database creation.
{: .choose_best #kanban_primary_use title="Primary use of Kanban boards" points="1" answer="1"}

- You can only link issues to a GitHub Project Board, but not pull requests.
- True
  - Not correct. GitHub Project Boards support linking both issues and pull requests.
- False
  - Correct! You can link both issues and pull requests to a GitHub Project Board.
{: .choose_best #deep_nesting title="Deep Nesting in Routes" points="1" answer="2"}

- Which of the following is NOT a benefit of using Kanban boards?
- Visualization of work items
  - Incorrect. Visualization is a primary benefit of Kanban boards.
- Compiling code
  - Correct! Compiling code is a task for development tools, not a benefit of Kanban boards.
- Limiting Work in Progress (WIP)
  - Incorrect. Limiting WIP is a key benefit of using Kanban boards.
{: .choose_best #kanban_benefits title="Kanban board benefits" points="1" answer="2"}


## Link In Bio
[Link In Bio](https://github.com/DPI-WE/link-in-bio) is an index of [link in bio URLs](https://chapters.firstdraft.com/chapters/887). Follow the contribution guidelines to add your link in bio and practice your pull request skills.

- Enter your `https://github.com/DPI-WE/link-in-bio/pull/<id>` pull request URL:
- `https://github.com/DPI-WE/link-in-bio/pull`
  - Great job!
- any
  - Not quite. Make sure the URL looks like: `https://github.com/DPI-WE/link-in-bio/pull/<id>`
{: .free_text #link_in_bio_pull_request_url title="Link in Bio Pull Request URL" points="1" answer="1" }

<div class="alert alert-danger mt-2">

After you submit the Pull Request URL here, return to Canvas and submit the URL again in the assignment "Pull Request URL for Link in Bio".

An instructor will provide additional feedback on your submission there.
</div>

<!--  TODO: add instructions to contribute to these repos to practice (just like above)
https://github.com/DPI-WE/first-project
https://github.com/DPI-WE/request-to-meme
-->

## Conclusion

This guide is just the beginning of how you can use GitHub Project Boards to manage your projects. To learn more about GitHub Projects and explore advanced features, check out the [GitHub Project Board Documentation](https://docs.github.com/en/issues/planning-and-tracking-with-projects)

By following these steps, you can effectively manage your projects using GitHub Project Boards, keeping track of issues, tasks, and pull requests all in one place. This organization helps streamline your workflow and improve team collaboration.

---

- Approximately how long (in minutes) did this lesson take you to complete?
{: .free_text_number #time_taken title="Time taken" points="1" answer="any"}
