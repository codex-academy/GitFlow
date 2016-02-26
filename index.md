---
layout: default
title: Git Flow
---

# Git Flow

A text-file based thing for practising Git Flow workflow. Follow the [git flow model](http://nvie.com/posts/a-successful-git-branching-model/) and take one feature per person. Don't worry about Hotfix branches for now: just concentrate on using `master`, `develop`, and `feature` branches, and use `git tag` for a release.

To get your code into our text application thing:

* Push your feature branch to GitHub.
* Make a Pull Request on GitHub for merging your feature branch into develop.
* Ask someone to review your Pull Request, and give you a :+1: in a comment when they are happy.
* Merge the Pull Request on GitHub.

Get started by doing a `git clone` on this repo. Then look at [Feature List Part 1](1-feature-list-part-1.html), then [Part 2](2-feature-list-part-2.html).

## Discussion topics

* Why use `develop` as the main branch instead of `master`?
* What state should `master` be in, in terms of tests?
* What happened when you pushed and pulled `develop`?
* What branches are allowed to merge into and out of `develop` and `master`?
* What does `git tag` do and why is it useful?
