Git: three different elements: -remote repository -local repository (content of that .git folder which contains the whole repository…) -local working copy/ or named “directory”

Yesterday we pulled from the remote repository -fetch -merge

Pull changes from remote repo to local working copy

Remote repo to local working copy: pull
Remote repo to local repo: fetch
Local repo to local working copy: merge

Mostly we just pull

If we want to save our work without interfering with work of others —> create new branch

Better ten short files than one huge file

Use a dash for new branch…

Could provide additional argument behind git switch -c <newbranchname> (zum Beispiel “feature/installation” oder “fix/buginform” or including an #issuenumber)

Origin/main branch

Git status will show me on which branch

Git switch main —> switch to main branch

Cd - will bring you back to the folder where you came from (said cd dash)

Cd switch - (minus) takes me back to the branch where I was before

I can switch branches with a modified file

-u means upstream

Git push -u origin <branchname> if you haven’t done that you can’t create a push request for a change later…

Git push -u

Pull request should be named push request (incorporate changes into main branch and delete the other branches)

Pull means pull a push

The pull request will basically be a new commit
In the comment you can refer to an issue (is a whole section in guthup issues)
Create a pull request out of a push request

You create a pull request but then you or other person has to merge - usually other person:
In many companies it is not possible to merge yourself that option is disabled, only other people who look over it and approve can merge it to the main branch

In GitHub directly after merging a button is provided delete branch
But
Also delete in locally
Git branch -d <branchname>

Git pull to get the new changes in that branch (in which you are in/ oooor in the repository)

Never commit anything unstable into the main branch

Every repository has its own main branch

You can not switch folders between branches “that’s not how it works” different versions of files in folders in different branches

Avoid having repositories inside repositories even though it is technically possible (don’t execute .git in it)

spiced-bootcamp git clone and copy that clone link f.e. git@github.com:RoyceBrouer/session-notebook.git to clone a repository from GitHub

How remove session-notebook\_
(Was cloned)
