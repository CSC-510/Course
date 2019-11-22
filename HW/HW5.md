# HW5 - Configuration Management and Continuous Deployment

Create an ansible playbook that is able to:

* **Setup: (40 points)** Install the following items:
    * Install node.js
    * Install forever
    * Pull/clone git repo into a destination: https://github.com/CSC-DevOps/App
    * Install npm packages
    
* **Tasks: (40 points)**:
    * Run app: `forever start node main.js`
    * Security: Create a task that ensures `bash`, `openssl`, `openssh-client`, and `openssh-server` are running latest version.
    * Cleanup: Remove content in `/tmp/*`

* **Concepts (20 points)**:

**Explain continuous integration. How is it used on a project?**
    
Answer - **Continuous integration** is a practice merging all developer working copies to a shared mainline several times a day, where developers automatically build, test, and analyze a software change in response to every software change committed to the source repository. A continuous integration server monitors the status of every commit and reports any problems.
It is particularly useful in projects by reducing repetitive processes saving time, cost, and effort. CI can enable team members to release deployable software at any point in time. Detecting defects and fixing them faster is enabled by CI. 


    * Why should developers use configuration management tools to manage their software programs? What can go wrong if they don't?

## Submission

Submit your [repo link](https://docs.google.com/forms/d/e/1FAIpQLScVABwfEuL1K170KXJJoy6JUdMrt0oQuf1VBSMZy9v8ktCczg/viewform?usp=sf_link).

* README.md (which documents steps for running ansible and playbook).
* Ansible playbook files
* Screencast demo of performing setup, tasks, running app.

Due, Monday, November 25th, before midnight.
