# COP4331C Small Project - Personal Contact Manager

## Group Members:

-   Omar Castro (Front-end)
-   Xutao Gao (Project Manager/Front-end)
-   Tetiana Kotvitska (API)
-   Luis Rodriguez-Rivera (Database/API)

## Description:

This project is a Personal Contact Manager website. It allows users to manage their contacts online, with features such as adding, editing, deleting, and searching contacts.

The project is built using the LAMP stack (Linux, Apache, MySQL, PHP) and is hosted on DigitalOcean. 
Link: [Contact Manager](http://www.cop4331xutaocontactmanager.xyz/)

### Technology Used:
**Postman:** API testing and development.
**Contribution:** Facilitated the creation, testing, and debugging of API endpoints. Allowed for efficient validation of the API functionality before integration with the frontend.
**Putty:** Secure remote access and management.
**Contribution:** Enabled team members to securely access and manage the server where the backend was hosted, ensuring smooth deployment and troubleshooting.
**Digital Ocean:** Cloud infrastructure provider.
**Contribution:** Hosted the backend services and the database. Provided a reliable and scalable environment for deploying the contact manager application.
**GoDaddy:** Domain registration and management.
**Contribution:** Managed the domain name for the website, making it accessible via a user-friendly URL. Simplified DNS management and ensured smooth domain setup.
**SwaggerHub:** API documentation and design.
**Contribution:** Created interactive API documentation that made it easier for the frontend team to understand and consume the API. Enhanced collaboration between backend and frontend developers.

## Installation

To set up this project locally, follow these steps:
1. Clone the repository to your local machine: `git clone https://github.com/XutaoG/cop4331-personal-contact-manager.git`
2. Import the database schema from database.sql into your MySQL database.
3. Update the database configuration with your MySQL credentials.
4. Place the project files in your server's web directory.
5. Start the DigitalOcean/Apache and MySQL services.
6. Access the project in your web browser.

## Usage
Once the project is set up, users can:

-   **Register** for an account or log in if they already have one.
-   **Add** new contacts, providing details such as name, phone number, email, etc.
-   **Edit** existing contacts to update their information.
-   **Delete** contacts they no longer need.
-   **Search** through contacts.

## Features

-   User authentication: Users can register for an account and log in securely.
-   Contact management: Users can add, edit, and delete contacts.
-   Search: Contacts can be categorized for better organization.
-   Accessible design: The interface is designed to be user-friendly.

## Git

For those not experienced with Git/Github, this will be a basic rundown of the commands you will need to pull/push your code.

### Cloning the Repository

To clone the repository, use `git clone <url>`. Make sure your Git SSH key authentication is properly configured, you will need to be authenticated to be able to push your work.

### Development Process

For this project, we will pivot towards a more feature-based development process where we will create a new git branch where you will work on new part of the project without disturbing the main branch. And only when the code on the branch you are current working on has been completed and tested will it be merged into the main branch by opening a pull request (confusing name, nothing to do with pulling).

Here is a short YouTube video explaning it: https://www.youtube.com/watch?v=02aQhH5cNBg

### Staging and Commit Commands

-   Add files into staging: `git add <file>` to add specified file
    -   `git add --all` to add all modified files into staging
-   Commit the changes: `git commit -m <commit_message>`
    -   Make your commit message short and concise please

### Branching

-   Show all existing branches: `git branch`
-   Create a new branch: `git branch <new_branch_name>`
    -   The new branch will first contain content based on which branch you are on when the command is executed.
-   Switch to a branch: `git switch <branch_name>`
-   For example, if you are on the API team, after you have cloned the repository onto your local machine, use `git branch api` to create a new api branch and use `git switch api` to switch to that branch. After finishing the work, add and commit the changes and push the changes into GitHub.

### Pushing

-   Push a branch into GitHub: `git push origin <branch_to_push>`

### Getting Changes onto Local Machine (Very important)

-   Before starting any work, making commits, or pushing the changes you have made into GitHub, make sure you current local repository is up to date with the cloud GitHub repository by pulling the new changes from GitHub using `git pull origin <branch_to_pull_from>`. This is to ensure that, in the case someone else changed some code you have worked, you will have the newest work.

These are the basic commands you will need, if you need any help or run into any issues/conflicts, message me on discord.
