# CodeGrade Review

## Learning Goals

- Review how to submit an assignment in CodeGrade
- Navigate around CodeGrade

## Introduction

This program utilizes a tool called CodeGrade to accept and automatically grade
your work.

## Submitting an Assignment

Before going to CodeGrade to submit an assignment, the first thing to do is make
sure you have already **added, committed, and pushed** your work up to GitHub.
Once your repo is up to date, you can start the submission process on CodeGrade.

To access the CodeGrade interface, you must do so through Canvas. Every
assignment that needs to be submitted will have a button at the bottom of its
page that says "Load <_the assignment name_> in a new window.

For example, the "Review: Variables Lab" assignment has this button:

![Button that says "Load Review: Variables Lab in a new window"](https://curriculum-content.s3.amazonaws.com/phase-1/codegrade-review/variables-lab-codegrade-button.png)

Clicking on this button will open a new tab with the CodeGrade interface for
that particular assignment. **Always double check you're in the correct
interface for the assignment you need to submit!** The title of the assignment
can be found in the top left corner of the interface:

![CodeGrade interface showing the title "Review: Variables Lab"](https://curriculum-content.s3.amazonaws.com/phase-1/codegrade-review/codegrade-assignment-header.png)

The process to submit an assignment from there is to, first, **connect your
GitHub account to CodeGrade**:

1. Click the "Create Submission" button.
1. If other students have already connected their GitHub accounts, you may be
   taken to a "Select an Account" page showing a list of other GitHub accounts.
   To connect yours, click on the "Connect Another Account" button in the bottom
   left.
1. When asked to choose your git hoster, click the "GitHub" button.

   - If you're already logged into GitHub, this should connect your GitHub
     account to CodeGrade.
   - If you were not already logged in, it will open up a GitHub login window,
     log in to connect your account.
   - In either case, if it asks you to authorize the connection, authorize it to
     properly connect your account.

1. Once your GitHub account is connected, the CodeGrade interface should display
   a list of all your GitHub repositories.

![Gif showing the CodeGrade interface, creating a submission, and connecting to GitHub](https://imgur.com/aXVrPtW.gif)

> **Note**: You should only have to connect your GitHub account once per phase.
> Once you've connected your GitHub, you should be able to find it on the
> "Select an Account" page. If for any reason you cannot find it, however,
> follow the above steps again.
>
> ![Screenshot showing the "Select an Account" page with two accounts and the "Connect your account" button](https://curriculum-content.s3.amazonaws.com/phase-1/codegrade-review/codegrade-select-account.png)

The next part of the process is to **connect your assignment repository to
CodeGrade**:

1. On the list of repos that shows up once you've connected or selected your
   GitHub account, find the correct repo to submit.

   - Again, be sure to double check that you are connecting the correct
     repository.

1. On the repo to submit, click the "Connect" button on the right.
1. Wait for CodeGrade to connect to the repo.
1. Once it connects and shows you a success message, you have successfully
   submitted your assignment. You are free to leave the window at this point.

   - However, if you would like to see CodeGrade score your assignment right
     after submission, click the link in the success message that says "here".
     This will take you to the submission page, which we will discuss in the
     next section.

![Gif showing how to connect a GitHub repo on CodeGrade](https://imgur.com/8hLcb3O.gif)

## The Submission Page

## Seeing your Grades

## Troubleshooting

Errors and mistakes can happen, and this section will cover some common ones. If
your problem is not listed here, please check with an instructor or technical
coach for guidance.

#### I accidentally connected the wrong repository! How do I remove it and connect the correct one?

Currently, there is no way to directly remove a submission or overwrite one in
CodeGrade. However, it is still removable via GitHub with the following steps:

![Gif showing the process of deleting a CodeGrade deploy key](https://imgur.com/bUB2dkM.gif)

1. Go to the repository you accidentally connected to CodeGrade.

   - Make sure you're in your forked version of the repo. Check this by looking
     for your username in the top left.

1. Go to the Settings tab, it should be on the far right.
1. On the settings page, go down to the "Security" section of the sidebar.
1. Click on the "Deploy keys" link.
1. Delete the CodeGrade Deploy key.

If you have multiple CodeGrade Deploy keys because you've submitted the repo
before, find the right one by checking the date the keys were added on.

![Deploy keys highlighting that the dates they were added are different](https://curriculum-content.s3.amazonaws.com/phase-1/codegrade-review/deploy-key-diff-date.png)

If both keys were added on the same day, the key at the bottom of the list is
typically the latest addition.

![Deploy keys highlighting that the dates are the same, and that the last key on the list is the most recently added](https://curriculum-content.s3.amazonaws.com/phase-1/codegrade-review/deploy-key-same-date.png)

After you've successfully deleted the deploy key, go back through the submission
process again and be sure to connect the correct repo!

> **Note**: When you first go back through the submission process, the incorrect
> repo will still be under the "Latest Submissions". It will be overridden once
> you submit a new repo.

## Conclusion

A short one or two paragraph summary of the contents of the lessons, recapping
the learning goals.
