![Logo of the project](/docs/images/logo.sample.png)

# Git Repository Template
> A template repository that adheres to Entisys360's Git standards

This repository is a template for initializing new git repositories or importing existing work.


## Installing / Getting started

Follow the official Github 
[documentation](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)
for creating a new repository using this template.

General Git usage information can be found in Entisys360's Microsoft Teams Git channel.


## Style guide

Entisys360 coding and style guidelines are hosted at 
https://github.com/entisys360/guidelines

If specific code style changes are required for this repository document them as rules in docs/styleguide.md along with instructions on how to validate. Also note here that additional guidelines exist and don't forget to update .editorconfig 


## Quick command reference / API reference

Clone this repository
```shell
git clone https://github.com/entisys360/git-template.git
```

Change directory into ./git-template

Checkout a new branch
```shell
git checkout -b your_new_branch_name
```

Add and/or modify files and directories
```shell
git add your_modified_files
```

Commit your code often as you work
> Remember: A proper commit message completes the sentence, "If applied, this commit will ..."

```shell
git commit -m "Change X because Y"
```

Push your commits upstream to the Git server
```shell
git push --set-upstream origin your_branch_name
```

Create a 
[pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)
when your branch is ready to merge.

