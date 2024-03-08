# Test

These tests are meant to **assess your competencies**. It is important for both of us to have a clear understanding of your current competencies when faced with problems similar to what you would encounter while working with us. Some problems _do_ have one right answer, but some are _more vague_: use your best judgement when designing and implementing your solutions.
The solutions will be discussed afterwards so make sure you are prepared to explain them.

## How to solve the test

First of all read the whole readme file and make sure you understand what is expected from you. If in doubt collect your questions and send it to the person you are in contact with. They will forward your questions for the right personel.

## Solution

Create a **private repository** in GitHub.
Create a new branch in your repository called feature_solutions.
Create a folder named Solution. All files that are part of you solution shall be put in this folder in a hierarchy of your choosing.
Make sure the solutions you submit is in line with how you would handle your daily tasks. Comment the code, format it etc.
We expect all text and code in your submission to be in English. 
If you are ready to submit your solution, add all assessors' GitHub username to your project (usernames will be provided by the person you are in contact with).

To do this, follow these steps:
1. Go to project settings (https://github.com/<Reponame>/settings)
2. Collaborators and teams
3. Manage Access
4. Add people
5. Add the provided github users with "Triage" permissions
6. Create a pull request (feature_solutions -> main branch) and add the assessors as reviewers.
    1. Make sure you explain your solutions in the pull request!

## Tasks

### Background
As a Data Engineer, one of your clients is entrusting you with a crucial task. The client is eager to analyze and visualize the purchasing behaviors of their customers. In order to fulfill this requirement, you are tasked with creating data mart tables that will serve as the foundation for a comprehensive analysis about customer buying patterns.

The assignment involves processing two **source files**: "customer" containing customer details and "CustomerSales" tracking purchases of customers. The stack you are using is your choice (SQL, Spark, etc.), but a brief description of the chosen runtime environment is required.

### Task descriptions
Task 0: Load the provided two files into the data platform of your choosing.

Task 1: Imagine that you receive these same files daily from the source system just with different data. Explain how would you load these files into the data platform of your choosing (how many tables would you create and why, what kind of transformations would you do on the data?). You don't have to provide the code for this, just the explanation. However if explaining the process or your following codes (that creates the data mart tables required in the following tasks) is easier for you that way, you can include them in your submission.

Task 2: A client asks you to provide a KPI which describes how much a specific customer spent in the year until each month in that year. The table should be designed in a way that the client could select a year and/or a month on the dashboard and the visualization shows how much a specific customer spent in that year until that month.

Task 3: For each customer, the client would like to know how many days have passed since their last purchase before the selected date. The table should be designed in a way that the client chooses any date from a dropdown list and the KPI would be calculated compared to that day (how many days have passed since their last purchase until that day).
