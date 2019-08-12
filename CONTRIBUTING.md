# Contribution Guidelines

To start contributing you will need a github account, you can create one
[here](https://github.com/join?source=header-home).

Before starting to contribute you need to check the [issues
board](https://github.com/infobayes/ScientificComputingNewApproach/issues).

If you want to contribute with an already created issue you must comment that
you want to work on it ask for an assigment to the issue. If want to contribute
with something not present on the issues board, create a new issue and ask for
assigment to the issue.

After you have been assigned to the issue you want to collaborate you can start
collaborating to the project.

The steps to make a new contribution are the following:

1. Make a fork of the repository to your own github account.

You can do it by clicking on the fork button on the top section of this repo
page.

2. Clone the repository to your local computer and enter the repository
   directory.

```
$ git clone https://github.com/your-username/ScientificComputingNewApproach.git
$ cd ScientificComputingNewApproach
```

3. Add the upstream remote.

The upstream remote is the reference of the original repository, with the
upstream reference you can pull the latest changes from the original
repository.

```
$ git remote add upstream https://github.com/infobayes/ScientificComputingNewApproach.git
```

4. Pull the latest changes.

```
$ git checkout master
$ git pull upstream master
```

5. Create a branch for the development of you work.

Please provide a suitable name to your branch, it will help to identify which
issue you are working on.

```
$ git checkout -b exercises-probability-section
```

6. Add continuosly your work.

When working in your changes (`git add` and `git commit`) make sure to make
small steps and writte good commit messages. Please take into account these two
references.

* https://code.likeagirl.io/useful-tips-for-writing-better-git-commit-messages-808770609503
* https://www.codelord.net/2015/03/16/bad-commit-messages-hall-of-shame/

7. Push your changes back to your github fork.

```
$ git push origin exercises-probability-section
```

8. Open a Pull Request

After pushing your changes to the repository you it will be possible to create
new pull request under the *pull requests* tab on **your fork**. A page with a
title and body will open. Always target the base repository from infobayes and
the master branch.

After opening your pull request reference on the issues board the PR that
closes that issue, this way we can keep track of issues to be closed.

## Writting your pull request message and review process

When writting pull requests you must provide a good title and link to the issue
from the issues board. Write what you have changed, why you have changed and
other pertinent details regarding your changes. Guide others on how to test
your changes and where to look more carefully.

To have your PR accepted you need at least two approves, one by a coleague and
another one by [@renatovicente](https://github.com/renatovicente).


## Conflicts

You may find conflicts while submitting a PR, if you are not
able to solve the conflicts by yourself still open the PR and for help,
[@otaviocv](https://github.com/otaviocv) will be always available to fix
conflicts.
