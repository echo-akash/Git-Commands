# Git Commands

## Getting and Cleaning Projects
<table>
<tr>
<th>Command</th>
<th>Description</th>
</tr>
<tr>
  <td><code>git init</code></td>
<td>Initialize a local Git Repository</td>
</tr>
<tr>
  <td><code>git clone ssh://git@github.com/[username]/[repository-name].git</code></td>
<td>Create a local copy of a remote repository</td>
</tr>
</table>


## Basic Snapshotting
<table>
<tr>
<th>Command</th>
<th>Description</th>
</tr>
<tr>
  <td><code>git status</code></td>
<td>Check Status</td>
</tr>
<tr>
  <td><code>git add [file-name.txt]</code></td>
<td>Add a file to the staging area</td>
</tr>
<tr>
  <td><code>git add -A</code></td>
<td>Add all new and changed files to the staging area</td>
</tr>
<tr>
  <td><code>git commit -m "[commit message]"</code></td>
<td>Commit changes</td>
</tr>
<tr>
  <td><code>git rm -r [file-name.txt]</code></td>
<td>Remove a file/a folder</td>
</tr>
</table>


## Branching and Merging
<table>
<tr>
<th>Command</th>
<th>Description</th>
</tr>
<tr>
  <td><code>git branch</code></td>
<td>List branches (the asterisk denotes the current branch)</td>
</tr>
<tr>
  <td><code>git branch -a</code></td>
<td>List all branches (local and remote)</td>
</tr>
<tr>
  <td><code>git branch [branch name]</code></td>
<td>Create a new branch</td>
</tr>
<tr>
  <td><code>git -d branch [branch name]</code></td>
<td>Delete a branch</td>
</tr>
<tr>
  <td><code>git push origin --delete [branch name]</code></td>
<td>Delete a remote branch/a folder</td>
</tr>
<tr>
  <td><code>git checkout -b [branch name]</code></td>
<td>Create a new branch and switch to it</td>
</tr>
<tr>
  <td><code>git checkout -b [branch name] origin/[branch name]</code></td>
<td>Clone a remote branch and switch to it</td>
</tr>
<tr>
  <td><code>git branch -m [old branch name] [new branch name]</code></td>
<td>Rename a local branch</td>
</tr>
<tr>
  <td><code>git checkout [branch name]</code></td>
<td>Switch to a branch</td>
</tr>
<tr>
  <td><code>git checkout -</code></td>
<td>Switch to the branch last checked out</td>
</tr>
<tr>
  <td><code>git checkout -- [file-name.txt]</code></td>
<td>Discard changes to a file</td>
</tr>
<tr>
  <td><code>git merge [branch name]</code></td>
<td>Merge a branch into a active branch</td>
</tr>
<tr>
  <td><code>git merge [source branch] [target branch]</code></td>
<td>Merge a branch into target branch</td>
</tr>
<tr>
  <td><code>git stash</code></td>
<td>Stash changes in a dirty working directory</td>
</tr>
<tr>
  <td><code>git stash clear</code></td>
<td>Remove all stashed entries</td>
</tr>
</table>


## Sharing and Updating Project
<table>
<tr>
<th>Command</th>
<th>Description</th>
</tr>
<tr>
  <td><code>git push origin [branch name]</code></td>
<td>Push a branch to remote repository</td>
</tr>
<tr>
  <td><code>git push -u origin [branch name]</code></td>
<td>Push changes to remote repository (and remember the branch)</td>
</tr>
<tr>
  <td><code>git push</code></td>
<td>Push changes to remote repository (remembered branch)</td>
</tr>
<tr>
  <td><code>git push origin --delete [branch name]</code></td>
<td>Delete a remote branch</td>
</tr>
<tr>
  <td><code>git pull</code></td>
<td>Update local repository to the newest commit</td>
</tr>
<tr>
  <td><code>git pull origin [branch name]</code></td>
<td>Pull changes from remote repository</td>
</tr>
<tr>
  <td><code>git remote add origin ssh://git@github.com/[username]/[repository-name].git</code></td>
<td>Add a remote repository</td>
</tr>
<tr>
  <td><code>git remote set-url origin ssh://git@github.com/[username]/[repository-name].git</code></td>
<td>Set a repository's origin branch to SSH</td>
</tr>
</table>
