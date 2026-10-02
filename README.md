# Hello World

Follow this Hello World exercise to learn GitHub's pull request workflow.

## Introduction

This tutorial teaches you GitHub essentials like repositories, branches, commits, and pull requests. You'll create your own Hello World repository and learn GitHub's pull request workflow, a popular way to create and review code.

In this quickstart guide, you will:

* Create and use a repository.
* Start and manage a new branch.
* Make changes to a file and push them to GitHub as commits.
* Open and merge a pull request.

### Prerequisites

* You must have a GitHub account. For more information, see [Creating an account on GitHub](/en/account-and-profile/how-tos/account-management/creating-an-account-on-github).

* You don't need to know how to code, use the command line, or install Git (the version control software that GitHub is built on).

## Step 1: Create a repository

The first thing we'll do is create a repository. You can think of a repository as a folder that contains related items, such as files, images, videos, or even other folders. A repository usually groups together items that belong to the same "project" or thing you're working on.

Often, repositories include a README file, a file with information about your project. README files are written in Markdown, which is an easy-to-read, easy-to-write language for formatting plain text. You can learn more about Markdown and README files in [Basic writing and formatting syntax](/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) and [Managing your profile README](/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme).

GitHub lets you add a README file at the same time you create your new repository. GitHub also offers other common options such as a license file, but you do not have to select any of them now.

Your `hello-world` repository can be a place where you store ideas, resources, or even share and discuss things with others.

1. In the upper-right corner of any page, select <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-plus" aria-label="Create something new" role="img"><path d="M7.75 2a.75.75 0 0 1 .75.75V7h4.25a.75.75 0 0 1 0 1.5H8.5v4.25a.75.75 0 0 1-1.5 0V8.5H2.75a.75.75 0 0 1 0-1.5H7V2.75A.75.75 0 0 1 7.75 2Z"></path></svg>, then click **New repository**.

   ![Screenshot of a GitHub dropdown menu showing options to create new items. The menu item "New repository" is outlined in dark orange.](/assets/images/help/repository/repo-create-global-nav-update.png)
2. In the "Repository name" box, type `hello-world`.
3. In the "Description" box, type a short description. For example, type "This repository is for practicing the GitHub Flow."
4. Select whether your repository will be **Public** or **Private**.
5. Select **Add a README file**.
6. Click **Create repository**.

## Step 2: Create a branch

Branching lets you have different versions of a repository at one time.

By default, your repository has one branch named `main` that is considered to be the definitive branch. You can create additional branches off of `main` in your repository.

Branching is helpful when you want to add new features to a project without changing the main source of code. The work done on different branches will not show up on the main branch until you merge it, which we will cover later in this guide. You can use branches to experiment and make edits before committing them to `main`.

When you create a branch off the `main` branch, you're making a copy, or snapshot, of `main` as it was at that point in time. If someone else made changes to the `main` branch while you were working on your branch, you could pull in those updates.

This diagram shows:

* The `main` branch
* A new branch called `feature`
* The journey that `feature` takes through stages for "Commit changes," "Submit pull request," and "Discuss proposed changes" before it's merged into `main`

![Diagram of the two branches. The "feature" branch diverges from the "main" branch and is then merged back into main.](/assets/images/help/repository/branching.png)

### Creating a branch

1. Click the **Code** tab of your `hello-world` repository.

2. Above the file list, click the dropdown menu that says **main**.

   ![Screenshot of the repository page. A dropdown menu, labeled with a branch icon and "main", is highlighted with an orange outline.](/assets/images/help/branches/branch-selection-dropdown-global-nav-update.png)

3. Type a branch name, `readme-edits`, into the text box.

4. Click **Create branch: readme-edits from main**.

   ![Screenshot of the branch dropdown for a repository. "Create branch: readme-edits from 'main'" is outlined in dark orange.](/assets/images/help/repository/new-branch.png)

Now you have two branches, `main` and `readme-edits`. Right now, they look exactly the same. Next you'll add changes to the new `readme-edits` branch.

## Step 3: Make and commit changes

When you created a new branch in the previous step, GitHub brought you to the code page for your new `readme-edits` branch, which is a copy of `main`.

You can make and save changes to the files in your repository. On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes so that other contributors can understand what you’ve done and why.

1. Under the `readme-edits` branch you created, click the `README.md` file.
2. To edit the file, click <svg version="1.1" width="16" height="16" viewBox="0 0 16 16" class="octicon octicon-pencil" aria-label="Edit file" role="img"><path d="M11.013 1.427a1.75 1.75 0 0 1 2.474 0l1.086 1.086a1.75 1.75 0 0 1 0 2.474l-8.61 8.61c-.21.21-.47.364-.756.445l-3.251.93a.75.75 0 0 1-.927-.928l.929-3.25c.081-.286.235-.547.445-.758l8.61-8.61Zm.176 4.823L9.75 4.81l-6.286 6.287a.253.253 0 0 0-.064.108l-.558 1.953 1.953-.558a.253.253 0 0 0 .108-.064Zm1.238-3.763a.25.25 0 0 0-.354 0L10.811 3.75l1.439 1.44 1.263-1.263a.25.25 0 0 0 0-.354Z"></path></svg>.
3. In the editor, write a bit about yourself.
4. Click **Commit changes**.
5. In the "Commit changes" box, write a commit message that describes your changes.
6. Click **Commit changes**.

These changes will be made only to the README file on your `readme-edits` branch, so now this branch contains content that's different from `main`.

## Step 4: Open a pull request

Now that you have changes in a branch off of `main`, you can open a pull request.

Pull requests are the heart of collaboration on GitHub. When you open a pull request, you're proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in different colors.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

In this step, you'll open a pull request in your own repository and then merge it yourself. It's a great way to practice the GitHub flow before working on larger projects.

1. Click the **Pull requests** tab of your `hello-world` repository.

2. Click **New pull request**.

3. In the **Example Comparisons** box, select the branch you made, `readme-edits`, to compare with `main` (the original).

4. Look over your changes in the diffs on the Compare page, make sure they're what you want to submit.

   ![Screenshot of a diff for the README.md file. 3 red lines list the text that's being removed, and 3 green lines list the text being added.](/assets/images/help/repository/diffs.png)

5. Click **Create pull request**.

6. Give your pull request a title and write a brief description of your changes. You can include emojis and drag and drop images and gifs.

7. Click **Create pull request**.

### Reviewing a pull request

When you start collaborating with others, this is the time you'd ask for their review. This allows your collaborators to comment on, or propose changes to, your pull request before you merge the changes into the `main` branch.

We won't cover reviewing pull requests in this tutorial, but if you're interested in learning more, see [Pull request reviews](/en/pull-requests/reference/pull-request-reviews). Alternatively, try the [GitHub Skills](https://skills.github.com/) "Reviewing pull requests" course.

## Step 5: Merge your pull request

In this final step, you will merge your `readme-edits` branch into the `main` branch. After you merge your pull request, the changes on your `readme-edits` branch will be incorporated into `main`.

Sometimes, a pull request may introduce changes to code that conflict with the existing code on `main`. If there are any conflicts, GitHub will alert you about the conflicting code and prevent merging until the conflicts are resolved. You can make a commit that resolves the conflicts or use comments in the pull request to discuss the conflicts with your team members.

In this walk-through, you should not have any conflicts, so you are ready to merge your branch into the main branch.

1. At the bottom of the pull request, click **Merge pull request** to merge the changes into `main`.
2. Click **Confirm merge**. You will receive a message that the request was successfully merged and the request was closed.
3. Click **Delete branch**. Now that your pull request is merged and your changes are on `main`, you can safely delete the `readme-edits` branch. If you want to make more changes to your project, you can always create a new branch and repeat this process.
4. Click back to the **Code** tab of your `hello-world` repository to see your published changes on `main`.

## Conclusion

By completing this tutorial, you've learned to create a project and make a pull request on GitHub.

As part of that, we've learned how to:

* Create a repository.
* Start and manage a new branch.
* Change a file and commit those changes to GitHub.
* Open and merge a pull request.

## Next steps

* Take a look at your GitHub profile and you'll see your work reflected on your contribution graph.
* If you want to practice the skills you've learned in this tutorial again, try the [GitHub Skills](https://skills.github.com/) "Introduction to GitHub" course.
* Personalize your profile and learn some basic Markdown syntax for writing on GitHub, see [Personalize your profile](/en/account-and-profile/tutorials/personalize-your-profile).

## Further reading

* [GitHub flow](/en/get-started/using-github/github-flow)85d3624296dfb4ea091eb1c5bf520e4b2be30c81GitHub Issues Visual Studio Extension
===============

[![Build status](https://ci.appveyor.com/api/projects/status/cq3t38xds110oxb8/branch/master?svg=true)](https://ci.appveyor.com/project/rprouse/githubextension/branch/master) [![Latest Release](https://img.shields.io/github/release/rprouse/GitHubExtension.svg)](https://visualstudiogallery.msdn.microsoft.com/e4ba5ebd-bcd5-4e20-8375-bb8cbdd71d7e) [![Join the chat at https://gitter.im/rprouse/GitHubExtension](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/rprouse/GitHubExtension?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![Follow Rob Prouse](https://img.shields.io/twitter/follow/rprouse.svg?style=social)](https://twitter.com/rprouse)

A visual studio extension for working with issues on GitHub by [Rob Prouse](http://www.alteridem.net). 

Access and manage GitHub issues for repositories that you have commit access to. You can filter and view issues for a repository, edit issues, add comments and close issue. This is the first Alpha release, more features are coming. 

## Download ##

The easiest way to download is by going to *Tools | Extensions* in Visual Studio and searching for the GitHub Extension. It is also available in the [Visual Studio Gallery](https://visualstudiogallery.msdn.microsoft.com/e4ba5ebd-bcd5-4e20-8375-bb8cbdd71d7e) and in the [GitHub Releases](https://github.com/rprouse/GitHubExtension/releases) for the project. 

## Instructions ##

- To view a list of open issues, go to **View | Other Windows | GitHub Issue List** (Ctrl+W, Ctrl+G)
- Log in to GitHub by clicking the logon icon at the upper right of the issue list window
- Open the issue window by double clicking an issue in the list, or by going to **View | Other Windows | GitHub Issue Window** (Ctrl+W, Ctrl+H)
- Add a new issue to the selected repository with the + button in the issue list, or from **Tools | New Issue on GitHub** (Ctrl+W, Ctrl+I)
- Edit an issue with the edit button on the Issue window
- Add comments to, or close and issue with the comment button on the issue window

## Two Factor Authentication ##

We do not currently support GitHub's Two-Factor Authentication system. However, you can generate a Personal Access Token to log in to your GitHub account instead.

1. Visit the following URL: https://github.com/settings/tokens/new
2. Enter a description in the Token description field, like "Visual Studio token".
3. Click Create Token.
4. Your new Personal Access token will be displayed.
5. Copy this token, and enter it in the Token text box in the logon dialog. You can now log in as usual.

If you ever want to revoke the token, visit the GitHub Applications settings page and click Delete next to the key you wish to remove.

## Credits ##

- Button and application images by [Font Awesome](http://fortawesome.github.io/Font-Awesome/) ([SIL OFL 1.1](http://scripts.sil.org/OFL))

## Screenshots ##

### Login Window ###

![Login](/images/logon.png)

### Issue List ###

![Issue List](/images/issue_list.png)

### Issue Window ###

![Issue Window](/images/issue.png)

## Building ##

This project supports Visual Studio 2012 and newer. You will need the Visual Studio SDK installed for the particular version of Visual Studio you are testing.

Optionally, set the GitHub `CLIENT_ID` and `CLIENT_SECRET` in `Secrets.cs` which is in the
`Model` folder of the `GitHubIssues` project. Note that if these values are not set, the
only supported authentication method will be specifying an access token generated according
to the steps described in **Two Factor Authentication**, above.

To debug, 

1. Set `GitHubExtension` as the startup project
2. Select **Debug** &rarr; **Start Debugging**
title: "[General] "
labels: ["General Introduction"]
body:
  - type: markdown
    attributes:
      value: |
        This is text that will show up in the template!
  - type: textarea
    id: improvements
    attributes:
      label: Top 3 improvements
      description: "What are the top 3 improvements we could make to this project?"
      value: |
        1.
        2.
        3.
        ...
      render: bash
    validations:
      required: true
  - type: markdown
    attributes:
      value: |
        ## Markdown header
        And some more markdown
  - type: input
    id: has-id
    attributes:
      label: Suggestions
      description: A description about suggestions to help you
    validations:
      required: true
  - type: dropdown
    id: download
    attributes:
      label: Which area of this project could be most improved?
      options:
        - Documentation
        - Pull request review time
        - Bug fix time
        - Release cadence
    validations:
      required: true
  - type: checkboxes
    attributes:
      label: Check that box!
      options:
        - label: This one!
          required: true
        - label: I won't stop you if you check this one, too
  - type: markdown
    attributes:
      value: |
        ### The thrilling conclusion
        _to our template_
