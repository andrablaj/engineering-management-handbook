<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [Install the pre-commit hook](#install-the-pre-commit-hook)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Install the pre-commit hook

Install `doctoc` by running`npm install -g doctoc`.

Run `sh .git_hooks/install_hooks.sh `.

Install `pre-commit` with `brew install pre-commit` (or check the [installation guide](https://pre-commit.com/) for your OS).

Run `pre-commit install` to set up the git hook scripts. Now `pre-commit` will run automatically on `git commit`!
