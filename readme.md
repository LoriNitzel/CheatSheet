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
`$ git commit -m "<commit message>"` - __Fill Me Out__

#### Branching
`$ git branch <branch name>` - __Fill Me Out__

`$ git branch` - __Fill Me Out__

`$ git checkout <branch name>` - __Fill Me Out__

#### Merging

`$ git merge <branch name>` - __Fill Me Out__
