# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
As an independent contractor, one of my biggest headaches is invoicing. I forget to track time, I invoice on an inconsistent interval, and I'm too cheap to pay for software. So instead of the spreadsheet that I've been using for the last three years, I am ready to use my newly honed programming skills to build an invoicing software that works for a self-employed person, like me, who might only have one client and would like to simplfy creating the next invoice with a single click. 

The application would be set up so that a user can log on, add clients and projects to their personal dashboard, and from there, input time entries on a per day, per project basis. The software will track how many days have gone by since time was entered, will remind users when they last generated and sent an invoice, and will track payments made while accounting for tax withholding for the fiscal year. Rock on!

### Features
User login: A user may register and login to see their personal dashboard, with its own lists of clients and projects.
Add client/project: A user may add a client to their personal database, and add projects tied to specific clients (or a default dummy client).
Add time entry: A user may add a time entry to their personal database that is tied to a specific date and to a specific projects. 
Generate invoice: A user may generate an invoice for a specific project, starting with the earliest time entry that hasn't been included in an invoice, up to the most current time entry.
Track payments: A user may indicate that an invoice has been paid, or track how much of an invoice has been paid by recording a payment and indicating which invoice it applies to.

### Technologies
*Visual Studio 2017
*C#/.NET
*ASP Core Framework with Razr Pages
*Git Bash
*SQL Server
*HTML/CSS


### What I'll Have to Learn
I will have to really make sure I understand SQL-like search strings using C#. I will likely be reviewing many of the lessons from Unit 3 to make sure my foundation is set. Beyond that, I will need to explore how web-apps compose and send emails, as I would like to include a "send" function so that one more step is simplified in my billing process. There will be a lot of join tables. I know I can use PersistentCheeseMVC as a base since it has the structure for adding "categories", but my objects are going to be more complex than I've made before so I will be brushing up on property and field management, get; set; and working with ViewModel structure. It's a lot but I think the core of it can be done relatively quickly. The added functions, like searching, dynamic reminders for how long it's been, etc, can come in sprints down the road. I will also be working via PivotalTracker for my project management. Link to project: https://www.pivotaltracker.com/n/projects/2236935.
