## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - shows differences between the working directory and the one you cloned (index)

#### Repo History
`$ git log` - gives a list of the commits

`$ git log --oneline --decorate --color --graph --all` - this will put all commits on a single, the graph flag will draw a text based graph of the flags on the left side of the commits--decorates adds the names of branches or tags of the commits shown, color puts the name of branches or tags in different colors.

`$ git log -p [filename]` show patch introduced at each commit

#### Stage files to commit
`$ git add <filename>` - stages specific files for commit

`$ git add -A` - stages all files for commit

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - saves staged file changes and adds message describing those changes

#### Branching
`$ git branch <branch name>` - creates new branch and names it

`$ git branch` - lists all of the branches in your repo

`$ git checkout <branch name>` - checks out specified branch, making it the current branch and updating the working directory to match

#### Merging

`$ git merge <branch name>` - Merge the change sinto the current branch from the changes of a remote repository. This act as a combinations of git commands by doing a git fetch followed by a git merge.

#### Aliases

Git doesn’t automatically infer your command if you type it in partially. If you don’t want to type the entire text of each of the Git commands, you can easily set up an alias for each command using git config. Here are a couple of examples you may want to set up:

$ git config --global alias.co checkout
$ git config --global alias.br branch
$ git config --global alias.ci commit
$ git config --global alias.st status
