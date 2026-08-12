
## Project Management System Using Microsoft Power Apps

The Power Apps-based project management system helps teams manage projects, assign tasks, and track progress from one place. It reduces the need to switch between different tools to check project details, task status, deadlines, and progress by bringing the essential project information into a single solution. Managers can create projects, assign tasks, and monitor progress, while users can update their progress and keep track of their assigned work.

---
## Advantages of the Project Tracking System

Here are the key benefits of the project management app built with Power Apps:

- Provide employees and managers with role-based access to views and control app based on their roles.
- Quickly view to-do, upcoming, overdue, and completed tasks using status cards.
- Filter projects and tasks to quickly find the information you need.
- Let users update task progress while managers track the latest status.
- Send email notifications for task assignments, overdue reminder, and task completion.
- Connect with Microsoft 365 services such as SharePoint, Outlook, and Power Automate for data storage, notifications, and workflows.
- Integrate the application with Microsoft Teams and SharePoint pages for easier access.
- Customize the application based on your organization's project management needs.
- Set up the application with minimal configuration.
- Access the application across desktop, tablet, and mobile devices.

## Features of the Project Management Application

The project management application consists of three main areas:

 1. My Tasks
 2. Create/Edit
 3. My Projects

### 1. View 'My Tasks' Page to Track Assigned Tasks

The **My Tasks** page is available to tasks assigned members for viewing and managing the tasks assigned to them.

 - Displays quick overview cards for to-do, upcoming, overdue, and completed tasks.
 - Shows task details such as project, task name, description, assignee, start date, due date, priority, and status.
 - Provides filters based on **Status, Priority, and Due Date** to narrow down the task list.
 - Allows users to start their assigned tasks and update their status as work progresses.
 - By default, only active and pending tasks are displayed to help users focus on their ongoing work. Completed tasks can be viewed by setting the **Status** filter to *Completed*.

Here's a preview of the 'My Tasks' page.

![My Tasks Page](https://blog.admindroid.com/wp-content/uploads/2026/08/My-Tasks-Page-2.png)

### 2. 'Create or Edit' Page to Create Projects and Assign Tasks

The **Create/Edit** page is available only to Entra ID managers for creating projects and assigning tasks. This page has 2 tabs: *Create New and Use Existing*.

#### 'Create New' Tab to Create Projects and Assign Tasks

In this tab, managers can create a new project and assign tasks to users.

To create the project:
- Enter the project name and description, then set the project due date, owner, and priority.
- Add one or more tasks to the project and assign them to the respective users.

Here's a preview of the 'Create new' tab.

![Create a New Project](https://blog.admindroid.com/wp-content/uploads/2026/08/Create-a-new-project.png)

#### 'Use Existing' Tab to Add Tasks to Existing Projects

Using this tab, managers can add new tasks to existing projects. To do this,

 - Select an existing project.
 - Add new tasks, assign them to users, set the task priority and due date.
 - Submit the task details to automatically update the tasks to the selected project.

Here's a preview of 'Use existing' tab.

![Add Tasks to an Existing Project](https://blog.admindroid.com/wp-content/uploads/2026/08/Add-tasks-to-an-existing-project.png)

### 3. View 'My Projects' Page to Manage Project and Track Progress

The **My Projects** page is also available only to Entra ID managers and provides them with a centralized view of the projects they manage.

 - Shows due dates, owners, task counts, and overall progress as summary details for each project.
 - Allows managers to filter projects by **Status** and **Priority**.
 - They can also view the users associated with the project, task progress, completion percentage, and view tasks options.  
- Select **View Tasks** to open the *Project Details* page, where you can view, edit, or delete the associated tasks. 
 - Allows managers to place an active project on **Hold or Resume** a project that is on hold.

Here's a preview of the 'My Projects' page.

![My Projects Page](https://blog.admindroid.com/wp-content/uploads/2026/08/My-projects-page.png)

#### View 'Project Details' Page to Track Task Progress

This page provides detailed information about a specific project and allows managers to monitor and manage the project and its associated tasks.

 - Displays completed, in-progress, and overdue cards with task counts.
 - -Provides four separate tabs for each task status: **Not Started, In Progress, Overdue, and Completed**. It allows managers to view tasks by status along with the task name, assigned user, due date, and priority.
 - Allows managers to edit project or task details and hold or resume the project when required.

Here's a preview of the 'Project Details' page.

![Project Details Page](https://blog.admindroid.com/wp-content/uploads/2026/08/Project-details-page.png)

For more details, refer to: <https://blog.admindroid.com/project-management-system-using-power-apps/>

---

## How the Project Tracker Works

Here is the simple workflow of the project management system using Power Apps.

1. A manager creates a new project from the **Create/Edit page** and enters the required project details. The manager can also add tasks to an existing project when needed.
2. The manager assigns tasks to users along with the required task details, priority, and due date.
3. Once the project is submitted, the respective user receives an email notification containing the project details and a direct link to access the **My Tasks page** to view the assigned task. 
4. When a user starts working on a task, they can select the **Start** button. The system automatically changes the task status to *In Progress* and records the date as the task's *Start Date*. The updated status is also reflected in the manager's view.
5. When the tasks is finished, the users can update their task status as **Completed**, the manager receives a notification with the task completion details. Completed tasks can be viewed from the *My Tasks* page by applying the *Completed* status filter.
6. If a task passes its due date without being completed, the assigned user receives a daily email reminder about the overdue task.
7. Managers can also place a project *On Hold* from the **My Projects** or **Project Details** page. When a project is placed on hold, its associated tasks are paused and greyed out for users. These tasks become available again when the project is resumed.
8. Managers can monitor overall project progress from the *My Projects* page and open individual projects to view detailed task progress, including completed, in-progress, and overdue tasks. They can also edit project or task details whenever updates are required.
9. If a project is no longer needed, managers can delete the project from the *My Projects* page. Deleting a project also removes its associated tasks from the system. 

---
