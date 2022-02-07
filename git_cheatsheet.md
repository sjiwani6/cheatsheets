
<h1> Git[Hub] Useful Commands </h1>

<code>git --version</code>-> get the version

<code>git config --global user.name "new-username"</code>-> Configure the default username for all repos.

<code>git config --global user.email "user@email.com"</code>-> Configure the default email for all repos.

<code>git init</code>-> Initialize a new repo.

<code>git status</code>-> Check status of current files

<code>git add file.py</code>-> Track file.py/stage changes

<code>git add --all/-A</code>-> Stage all changes

<code>git commit -m "message"</code>-> Commit changes with an associated message.

<code>git status --short</code>-> See our changes in a more compact way
<ul>
<li> <code>??</code> - Untracked files
<li> <code>A</code> - Files added to stage
<li> <code>M</code> - Modified files
<li> <code>D</code> - Deleted files
</ul>

<code>git log [origin/main]</code>-> History of commits

<code>git [command] -help</code> or <code>git help --all</code>-> Find help

<code>git branch [-a]</code>-> See the branches we have. * indicates which branch we are currently on. <code>-a</code> will show us remote branches and local branches. 

<code>git branch hello-branch</code>-> Creates a new branch

<code>git branch -d gross-branch</code>-> Delete gross-branch

<code>git checkout [-b] hello-branch</code>-> Checkout a branch. <code>-b</code> will allow us to create a new branch and move to it

<code>git merge new-branch</code>-> Merge current branch with new-branch 

<h2>Pushing local repo to GitHub</h2>

<code>git remote add origin URL</code>-> Adding a remote repository with specified URL as an origin to your local Git repo

<code>git push --set-upstream origin main</code>-> Push main branch to the origin URL & set as default remote branch 

<h2>Using GitHub</h2>

<code>git fetch origin</code>-> Gets all changes of a tracked branch/repo 

<code>git diff origin/main</code>-> Show differences between our main and remote main 

<code>git pull</code>-> Combination of fetch and merge