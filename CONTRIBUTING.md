# Contributing guidelines

1. [Fork](../../fork) this repo

1. If it doesn't exists yet, [open an issue](../../issues/new/choose) to address your
   desired changes

1. Before starting, remember to run `npm install` or `yarn`.

   This will install some git hooks that aids you before committing and pushing
   to prevent PR rejections due to incorrect coding standards, naming
   conventions, spacing, encoding, etc...

1. Open a new branch from [`master`](../../tree/master) following the given
   pattern:
   1. If the issue refers to a bug, name the branch fix-#00
   1. If the issue implements a new feature, name the branch ft-#00
   1. For other cases such as typos, docs, etc, name the branch misc-#00

1. [Open a pull request](../../compare) targeting the same branch as yours.

   Merging will be resolved under the build system according to packaged
   branches/commits.


### Note:

We have [`.editorconfig`](/.editorconfig) settings. Be sure to activate your
editor plugin to help coding.


## Please, don't!

* Edit [`setup.cfg`](/setup.cfg) `[bumpversion]` sections
* Fill in [`package.json`](/package.json),
  [`package-lock.json`](/package-lock.json) or [`setup.py`](/setup.py)
  `version` fields
