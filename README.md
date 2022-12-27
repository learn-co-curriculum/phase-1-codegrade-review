# CodeGrade Review

## Learning Goals

- Review how to submit an assignment in CodeGrade
- Navigate around CodeGrade
- Troubleshoot common errors while navigating CodeGrade

## Introduction

This program utilizes a tool called CodeGrade to accept and automatically grade
your work. Like any tool, it can take some time to get used to. This lesson will
walk you through using the tool and help troubleshoot some common problems you
may come across while using it.

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

The submission page is where you can see CodeGrade automatically grade your
assignment by running the same tests you run while completing the lab.

There are two ways to navigate to this page.

![The submission success message with a redirect link](https://curriculum-content.s3.amazonaws.com/phase-1/codegrade-review/submission-redirect.png)

1. Right after submitting an assignment, click on the redirect link in the
   submission sucess message ("here").

![Gif demonstrating reopening CodeGrade and clicking the Latest Submission button](https://imgur.com/NCv3o04.gif)

2. Any time after submitting an assignment, go back to the assignment you want
   to view this page for on Canvas, click on the "Load" button at the bottom of
   the page to open the CodeGrade interface, then click on the "Latest
   Submission" button.

Once you're on the page, you'll notice it consists of three different views:

![The three submission page tabs - Code, Feedback Overview, AutoTest](https://curriculum-content.s3.amazonaws.com/phase-1/codegrade-review/submission-page-views.png)

1. Code
1. Feedback Overview
1. AutoTest

Let's go over each one.

![Screenshot of the "Code" view](https://curriculum-content.s3.amazonaws.com/phase-1/codegrade-review/code-view.png)

The "Code" view displays all of your code. It brings in all the files from the
GitHub repo you connected. You can use the file explorer to view all your files.
Here is where you can make sure you submitted the correct repo.

Additionally, you can add comments on your files while on this view. If there
was a part of your code that you couldn't get working, for example, you could
add a comment on that specific line explaining what you tried or what confused
you. The gif below demonstrates how to add a comment:

![Adding a comment to a specific line of a file in the Code view](https://imgur.com/wgWwAcq.gif)

> **Note**: Responses to your comments are not immediate nor guaranteed as those
> are _not_ automated like tests and require manual input.
>
> We generally recommend utilizing the technical coaches or working with your
> peers for any assignment questions you have that are necessary for your
> fundamental understanding.

In cases where you _do_ get responses, however, you would see them on the second
view - the "Feedback Overview".

![Screenshot of the "Feedback Overview" view](https://curriculum-content.s3.amazonaws.com/phase-1/codegrade-review/feedback-view.png)

This view is where you can view all the comments you left, as well as any
responses or general feedback your instructors have left for you. You can also
manage your comments here, such as deleting or editing them. You can reply to
any feedback received as well, though we only recommend doing so when necessary.

The view you will likely look at the most, however, is the last one: the
"AutoTest" view.

![Screenshot of the AutoTest view](https://curriculum-content.s3.amazonaws.com/phase-1/codegrade-review/autotest-view.png)

If all you want to know is whether or not you passed an assignment, that is
immediately viewable in the table under the "Categories" section. As long as the
"Pass" column has a green checkmark, that means you passed the assignment!

If you go to this view immediately after submitting an assignment, however, that
checkmark may not be there yet. This is because CodeGrade has to get set up
before running the AutoTest.

You can tell if the AutoTest is not finished yet by looking at the status box on
the right side of the "Setup" bar. If it says anything but "Done", the tests are
still being run. The gif below shows an example.

![Gif of the Setup status box](https://imgur.com/FCXMmnN.gif)

Once the AutoTest finishes, you should see your score out of 100%, and either a
checkmark or an "X" under the "Pass" column.

You can see more details about the tests by clicking on the row. This will
display what tests you have passed.

![Gif clicking on a row and displaying more info on the tests](https://imgur.com/HZNa5Fu.gif)

> **Note**: Your grades on this view should _not_ be a surprise. The AutoTest
> uses the same tests you should be running as you work on the assignment. As
> long as you've passed all the tests while working locally, they should pass on
> CodeGrade too.

## Seeing your Grades

tba

## Troubleshooting

Errors and mistakes can happen, and this section will cover some common ones. If
your problem is not listed here, please check with an instructor or technical
coach for guidance.

### I accidentally connected the wrong repository! How do I remove it and connect the correct one?

Currently, there is no way to directly remove a submission or overwrite one in
CodeGrade. However, it is still removable via GitHub with the following steps:

![Gif showing the process of deleting a CodeGrade deploy key](https://imgur.com/OCK3r3r.gif)

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
> repo will still be under the "Latest Submissions". That is OK - it will be
> overridden once you submit a new repo.

### I refreshed the CodeGrade page and it's asking me to log back in. What are my account details to log in?

If you don't remember creating a username and password for CodeGrade, that's
because you did not. To access CodeGrade, you must always do so from Canvas.

To get back to the submission page for a specific assignment, return to the
assignment on Canvas and click on the "Load" button at the bottom of the page
again. If the button is not there due to being clicked once before, refresh the
Canvas page and it should reappear.

![Gif demonstrating the login bug when refreshing CodeGrade, then shows reopening the CodeGrade interface through Canvas](https://imgur.com/ccWeiDT.gif)

## Conclusion

A short one or two paragraph summary of the contents of the lessons, recapping
the learning goals.
