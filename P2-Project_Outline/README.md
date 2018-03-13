# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
My project will be an expense tracker that will allow users to track their expenses by time, date, and category. Users will be able to create an account, log in, create, edit, and remove expense_categories, create, edit, and remove expenses. They will be able to review all expenses, expenses by month, and expenses by category.

I decided to make this project because I am getting married next year, and weddings are expensive. I want to track the expenses of the wedding, and generally have a better understanding of my own expenses to better plan for my finacial future. This application can be beneifical for anyone that is looking to gain insight on their own spending habits.


### Features

- User Sign up: Users will be able to create a new profile for themselves, allowing them to track their own expenses, based on their own categories.
- User Login: Users will be able to login after creating a profile. Passwords will be hashed, salted, and possibly peppered.
- Edit, Create, and Delete Categories: Users will be able to create new categories to track their own expenses. Categories will be flexible, and can be edited, and deleted.
- View Expense History: Users will be able to see a full history, and total of their logged expenses.
- View Expense by Month: Users will be able to see a full log of expenses, and expense total in any given month.
- View Expenses by Category: Users will be able to see a log, and total for any given category.

### Technologies
- Rust
- Rocket
- Cargo
- Handlebar Templates
- A Rust crate for DB connectivity, and ORM
- Foundation CSS

### What I'll Have to Learn
I am newish to Rocket. I understand HTTP Requests, HTTP Responses, and serving up templates. I don't know how to connect to a DB, or of any ORM's in Rust. I will have to do some research on what is available, and what makes sense for a project of this size. I also will have to dive deeper into Handlebar Templates -- mainly fragmenting, and reusing templates within templates.