- What is source code management

Is for tracking modifications to a source code repositoy

- What is Git

Git is an open source software, which allows us to work on open source projects or team projects, where programmers need to work on different task, so we can work independently on parallel branches running in different Systems.

- What is GitHub

Is a code hosting platform cloud-based and let us manager Git repos and version control is nothing more than tracking and managing changes to software code.

- What is the difference between Git and GitHub

Git is an open-source tool developers install locally to manage source code, while GitHub is an online service to which developers who use Git can connect and upload or download resources

- How to create a repository

On GitHub we just have go to the upper-right corner of and page and use the + drop-don menu, and select New Repo.

- What is a README

A README file is a document that explains what our project is about along with a repository license, citation file, contribution guidelines, and a code of conduct, communicates expectations for your project and helps you manage contributions..

- How to write good READMEs

We can solve this questions:

What the project does?

Why the project is useful?

How users can get started with the project?

Where users can get help with your project?

Who maintains and contributes to the project?

- How to commit

git commit -m “commit message”

- How to write helpful commit messages

Commit messages are important because we can communicate others or to ourselves why a change was made and understanding that makes development and collaboration more efficient.

Run `git commit` without a message or option and it'll open up your default text editor to write a commit message.

To configure your "default" editor:

```
git config --global core.editor nano

```

This would configure Git to use nano as your default editor. Replace "nano" with "emacs," "vim," or whatever your preference is.

In the opened editor, the first line is the subject (short description), leave a blank line after it, and everything else is the extended description (body).

```
<Summarize change(s) in around 50 characters or less>

<More detailed explanatory description of the change wrapped into about 72
characters>
```

- How to push code

git push

- How to pull updates

1. First, run git status. Git will tell you the repository is clean, nothing to worry about.
2. Then run git fetch.
3. Next, run git status again. Git will say your branch is one commit behind.
4. Finally, run git pull to update your local branch.

- How to create a branch

git branch name_of_branch

- How to merge branches

git merge name_of_branch

- How to work as collaborators on a project

Click on the “Settings” tab of your rep, then “Collaborators” then search for Github users and add them by clicking “Add Collaborator”

- Which files should and which files should not appear in your repo

1. Files that don’t belong to the project
2. Files that are automatically generated
3. Libraries (depends on the situation)
4. Credentials
