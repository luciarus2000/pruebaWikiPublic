<h3><b><u>Pull Request</u></b></h3>

  
  

<FONT SIZE=4>Developers will need to create a Pull Request originating from the feature branch and merging into the develop branch to deploy their changes. Uploads to the pre-production and production environments will be made by creating two pull requests - first one originating from the develop branch and merging into the release branch, and second one originating from the release branch and merging into the main branch, in that order respectively.</font>

![image.png](/Project/.imgs/pullrequest.png)

<h3>Permissions:</h3>

  
<FONT SIZE=4><b>Developers will have contributor permission</b>, so they will only be able to create pull requests from feature to develop. Administrators will be responsible for merging and creating pull requests to the upper environments.</font>

  
    

<h3><b><u>Conflicts:</u></b></h3>


<FONT SIZE=4>Version control systems consist of managing contributions from various distributed authors (usually developers). Sometimes, it may happen that several developers try to edit the same content. If developer A tries to edit code that developer B is also editing, a conflict could occur. To prevent conflicts from arising, developers work on separate, isolated branches.</font>

<h3>Resolving a merge conflict on GitHub:</h3>

<FONT SIZE=4>You can only resolve merge conflicts on GitHub that are caused by competing line changes, such as when people make different changes to the same line of the same file on different branches in your Git repository. For all other types of merge conflicts, you must resolve the conflict locally on the command line.  [Guide Command Line](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line)</font>

1. <FONT SIZE=4>Under your repository name, click  Pull requests.</font>
2. <FONT SIZE=4>In the "Pull Requests" list, click the pull request with a merge conflict that you'd like to resolve.</font>
3. <FONT SIZE=4>Near the bottom of your pull request, click Resolve conflicts.</font>
![image.png](/Project/.imgs/resolveconflict.png)
4. <FONT SIZE=4>Decide if you want to keep only your branch's changes, keep only the other branch's changes, or make a brand new change, which may incorporate changes from both branches. Delete the conflict markers <<<<<<<, =======, >>>>>>> and make the changes you want in the final merge.</font>
5. <FONT SIZE=4>If you have more than one merge conflict in your file, scroll down to the next set of conflict markers and repeat steps four and five to resolve your merge conflict.</font>
6. <FONT SIZE=4>Once you've resolved all the conflicts in the file, click Mark as resolved.</font>
7. <FONT SIZE=4>If you have more than one file with a conflict, select the next file you want to edit on the left side of the page under "conflicting files" and repeat steps four through seven until you've resolved all of your pull request's merge conflicts.</font>
8. <FONT SIZE=4>Once you've resolved all your merge conflicts, click Commit merge. This merges the entire base branch into your head branch.</font>
![image.png](/Project/.imgs/commitmerge.png)


<h3>Resolving a merge conflict on Visual Studio Code:</h3>

1. <FONT SIZE=4>If you're collaborating with others in the same branch, you might see merge conflicts when you push your changes.</font>
2. <FONT SIZE=4>Visual Studio detects if the local branch you've been working on is behind its remote tracking branch and then gives you options to choose from. <br>In this example, select Pull then Push to include changes introduced to the remote repository. If there are any merge conflicts when you're pulling changes or trying to merge two branches, Visual Studio lets you know in the Git Changes window, in the Git Repository window, and on any files that have conflicts.</font>
3. <FONT SIZE=4>The Git Changes window shows a list of files with conflicts under Unmerged Changes. To start resolving conflicts, double-click a file. Or if you have a file with conflicts opened in the editor, you can select Open Merge Editor.</font>
![image.png](/Project/.imgs/mergeeditor.png)
4. <FONT SIZE=4>In Merge Editor, start resolving your conflict by using any of the following methods (as depicted in the numbered screenshot).
Go over your conflicts line by line, and choose between keeping the right or the left side by selecting the checkboxes. Keep or ignore all of your conflicting changes.
Manually edit your code in the Result window.</font>
5. <FONT SIZE=4>When you're done resolving the merge conflicts, select Accept Merge. Repeat this process for all conflicting files.</font>
![image.png](/Project/.imgs/acceptmerge.png)
6. <FONT SIZE=4>Use the Git Changes window to create a merge commit and resolve the conflict.</font>


<h3><b><u>How to add test?</u></b></h3>

  

<FONT SIZE=4>The template created to introduce the tests to be executed can be found at the following [link](https://github.com/TotalEnergiesCode/salesforce-one-back/blob/main/.github/pull_request_template.md).</font><br>

<FONT SIZE=4>When creating a pull request, in the "write" section we must add the necessary tests separated by spaces.<b> NO delete "testsToBeRun".</b></font>

![image.png](/Project/.imgs/tests.png)


<h3><b><u>How to add reviewers?</u></b></h3>


<FONT SIZE=4>On the right-hand panel of our Pull Request, we will see a section called 'Reviewers' with a gear icon. There, we can add the users we deem appropriate.</font>

![image.png](/Project/.imgs/reviewers.png)
  

<h3><b><u>How to check the execution steps?</u></b></h3>

  

<FONT SIZE=4>When opening the created pull request, we will find a series of comments headed by <i>"Starting build"</i>, where we can follow the steps that are carried out with a check if they have been successful or a cross if they have failed. To access the failures, we will click on the URL generated by the comment <i>"Navigate to workflow run URL"</i>.</font>

![image.png](/Project/.imgs/flowsteps.png)
