Git Nodnol
==========

This reverses the order of the commits that are reachable from where you are when you run this command onto a new branch called `nodnol`.

This currently works against a repo which has a single line of commits. This is untested for merges.

This does not take special action to preserve any unstaged files. They will be committed along with the rest of the working directory into the first commit of the new branch.
