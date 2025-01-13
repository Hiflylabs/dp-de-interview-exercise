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
As a Data Engineer, one of your clients is entrusting you with a crucial task.

The assignment involves processing two **source files**: "customer" containing customer details and "CustomerSales" tracking purchases of customers. The stack you are using is your choice (SQL, Spark, etc.), but a brief description of the chosen runtime environment is required.

In solving the tasks, we are interested in the solutions provided using a platform of your choice. It is not necessary to provide a fully orchestrated data platform solution; it is sufficient if the individual tasks are meaningful on their own.
Additionally, we do not require any dashboard solutions. We appreciate code and more important we don't want to waste your time.


### Task descriptions
Task 1: Using the available data, design a data model for the platform of your choice.

The goal of the data model is to support efficient storage and analysis of sales and customer data.
Take into account data cleansing steps, relationships between data, and potential normalization levels.
It is not mandatory to use the 3rd Normal Form (3NF). Choose a suitable approach and justify why you chose it.

Task 2:
Create a procedure or SQL statements for loading sales and customer tables into a central layer. The procedure does not need to be complete, but the method of loading should be visible.
The focus is on the loading process itself, not the surrounding elements (e.g., logging, error handling, etc.).

Task 3
Write a query that answers the following question:
Which cities have at least 5 customers who purchased at least 3 different products in the last 90 days, and where the total purchase value of these customers falls in the top 50%?

Task 4
Create a test log that includes the tests and checks you would perform during or after tasks 2 and 3, or what checks you would integrate during execution.

