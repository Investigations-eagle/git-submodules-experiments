# Lerna

## Run `npm install` for all sub-projects

* `lerna bootstrap`

## Build application

* `lerna run --scope [sub-project-name] [command-name]`  
Example: `lerna run --scope reports build`

# Git Submodules

## Add git Submodule

* `git submodule add [path to git repo]`

## Cloning a Project with Submodules

* cd *"./packages/[package-name]"*
* `git submodule init`
* `git submodule update`

**For more info:** https://git-scm.com/book/en/v2/Git-Tools-Submodules

## Remove git Submodule

* remove module from *".gitmodules"*
* remove module from *".git/config"*
* `git rm --cached <submodule_path>;`
