
# Pending Name

## Project Description:
With the chaos of the world today it is easy to loose track of yourself and your daily tasks. PROJECT NAME will help you keep track of your to do list, fitness, and whatever else you need to check off. You can watch your creature grow up and learn and gain a personality while you create more focus in your life. 

## Meeting Time: TBD

## Team Member Bios:

Michaela Gerweck - Team Lead

In my last semester here at EMU, majoring in Computer Science with a double minor in Communcations and Public & Nonprofit Administration. I enjoying playing TTRPGs, hanging out with my dog and boyfriend, and traveling with friends. 

Sam Keim - Team Deputy

Tyler Lopez - Team Member

This is my last year at EMU, my first semester on-campus; I hate coming to campus. I've had an Android internship at Strava, which is a fitness app, that I no-lifed and received a return offer to, so my early-career will be entirely Android focused.
I like climbing at Planet Rock and have climbed outdoors on some big trips a couple of times.
 	
Brandon Jones - Team Member
	
Joseph Paredes Gleespen - Team Member

Jeremy Genovese - Team Member


## Commit Message Guideline:
Commits should be structured as shown below.

Commit Message Title
Content of commit message. 
GitHub Issue #

Commit Message Title: Briefly explain what the commit is for.
Content of commit message: Describe what has been changed in this commit and why it has been changed. If the commit is fixing a bug, for instance, you should explain why the bug was occurring and how the changes in this commit resolve it. If there is something unusual or confusing in your changes, clarify why it was done that way. Your commit message is an opportunity to help your teammates and yourself understand your changes.
GitHub Issue #: The bottom line should have the Issue # so that everyone can know what issue this commit is associated with.

## Pull Request Guideline:
Your working branch should be synced with main before submitting a pull request. Follow these steps to do that:

1. Git pull. This makes sure that main is up to date.
2. Git merge main. Do this while in the working branch. This updates your working branch with any changes in main. At this point there may be conflicts.
    - If there are conflicts:
    1. Resolve conflicts in necessary files.
    2. Git add & git commit. This stages and commits the changes from the conflict resolution.
3. Git push origin workingBranchName. This pushes any changes in the local working branch to the remote working branch.

We do this because it allows us to resolve merge conflicts before creating the pull request. This has the benefit of resolving the conflicts early, before the working branch is being merged to main.

Once you have done the above procedure, you should create a pull request in GitHub. The title of the pull request should be a brief description of the purpose of the pull request. For example: Improved main page layout. The body of the pull request should have a detailed summary of the changes and why they were made, much like the commit messages discussed above. The purpose of this comment is to help your code reviewer understand your changes, so explain anything that may be difficult or confusing to understand. Assign a team member to review the pull request. Add any relevant labels. Link the relevant issue case. This helps the reviewer know what issue case this pull request is resolving, and also allows the issue to be automatically resolved once the pull request is merged.

## Code Review Checklist:
	1. Fit for Purpose
Code may work, but does it work in the way that you expects?
2. Notice What's Missing
For example, it’s important to think through edge cases,unexpected inputs, and error handling scenarios that the code’s author may not have considered.  What happens when the user hits the submit button twice in rapid succession? What happens when the user’s browser isn’t supported?
3. Readability
Readability in software means that the code is easy to understand. If not, have you made any comments there to help your teammates to understand.
4. Maintainability
    	Avoiding hard-coded configuration. 
5. Testing
Check that tests are present and well documented for all common functionality. 
Make sure that tests are well isolated, so you can find the problem quickly if a test fails. 
6. Performance
Is the project as performant as it could be, or are these obvious optimizations that might improve performance?
