<h2 align="center">Conventional commits </h2>
In the Jira issue in the development section, you have two options, create branch and create commit, which can help you create commit messages and branch names. If you use this feature, first make sure you follow the rules below, such as adding a commit type.

<b>To associate a commit with a Jira issue, the commit must contain a Jira issue ID.

The commit message should be structured as follows:

<p align="center"><FONT COLOR=" #0ca80e"> type</FONT>:<FONT COLOR=" #0352fc">  description <FONT COLOR=" f000"> Jira issue ID </FONT></FONT></p></b>
Commit types:

<b>fix</b>  -  Commits, for all code changes.
<b>feat</b> - Commits, that adds a new feature.
<b>bug</b>   -  Commits, which are used when working on bug fixes.
<b>docs</b>  - Commits, that affect documentation only.

Examples of correct commit messages: 

<img src="https://static.thenounproject.com/png/2537955-200.png" 
     width="25" 
     height="25" /> fix: some fix INAPP-90
<img src="https://static.thenounproject.com/png/2537955-200.png" 
     width="25" 
     height="25" /> feat: new feature INAPP-90 

Examples of incorrect commit messages:
- fix: some fix
- INAPP-90 some fix

<h2 align="center">Branch name rules </h2>

<b>To associate a branch with a Jira issue, the branch name must begin with a Jira issue ID.</b>

Examples of correct branch names: 

<img src="https://cdn.iconscout.com/icon/free/png-256/git-branch-458285.png" 
     width="25" 
     height="25" /> INAPP-90-some-text
<img src="https://cdn.iconscout.com/icon/free/png-256/git-branch-458285.png" 
     width="25" 
     height="25" /> INAPP-90 

Exampes of incorrect branch names:
- some-text-INAPP-90
- some-text