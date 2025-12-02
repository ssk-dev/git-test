# git-test
This is a git playground for testing branches, tags, pr's...

## Clone it

1. Cloning a repository
-> git clone git@github.com:ssk-dev/git-test.git

2. Switch to directory of the repository
-> cd git-test

3. Mark the repository as trusted 
->  git config --global --add safe.directory C:/git-test

## Working on a branches

1. Checkout a new branches
-> git checkout -b doc/FEAT-0001_add-general-readme
*valid naming convention
• feature/FEAT-0001_implementation-of-feature-xyz
• bugfix/FIX-0010_fix-of-wrong-button-xyz
• release/software-release_v1.0
• doc/adding-initial-readme