## What happed to a tag if its related commit is gone?

Then the tag points to an unexisting commit, it's no longer meaningful.

## How to change the commit message at HEAD~10?

Use rebase in interactive mode, make some changes on the commit message, then keep all following commits the same. All the commit SHA value will be updated.
