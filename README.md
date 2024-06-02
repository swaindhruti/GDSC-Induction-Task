# 📋GDSC-Induction-Task 

This is the repository for submitting your GDSC NIT Rourkela induction task provided to you by the GDSC NITR team.

## 🛠️Pre-requisites

- Learn how to use Git and GitHub. Make sure Git is installed on your system.
  - [Git Tutorial](https://www.freecodecamp.org/news/git-and-github-for-beginners/)
  - [Install Git](https://git-scm.com/downloads)
- Follow the below links to set up your Git username and email:
  - [Setting up git username](https://docs.github.com/en/get-started/getting-started-with-git/setting-your-username-in-git)
  - [Setting up git email](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-email-preferences/setting-your-commit-email-address#setting-your-commit-email-address-in-git)

## 📝Procedure for submitting your task

1. Fork the repo using the fork option on GitHub.
2. Clone the forked repo using the following command:

   ```bash
   git clone https://github.com/<your_user_id>/GDSC-Induction-Task.git
   ```

3. Navigate to the cloned repo:

    ```bash
    cd GDSC-Induction-Task
    ```

4. Create a folder with your name inside the repository. Inside this folder, create a README.md file and a Projects folder which will contain the induction tasks:

    ```bash
    mkdir -p <your_name>/Projects
    touch <your_name>/README.md
    ```

5. After completing your tasks, add the changes to the staging area and commit the changes:

    ```bash
    git add -A
    git commit -m "your commit message"
    ```
6. Push the changes to the remote repository:

    ```bash
    git push origin main
    ```