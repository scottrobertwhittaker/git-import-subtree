git import-subtree
==================

This git subcommand is a super-simple tool for importing repositories for use
with the subtree merge strategy described at
<https://www.kernel.org/pub/software/scm/git/docs/howto/using-merge-subtree.html>.

Place this script in your `$PATH` and run

    $ git import-subtree <destination> <remote> <ref>

to create a new directory named `<destination>` containing the contents of the
specified `<remote>` repository at the specified `<ref>`, preserving the
history of the remote repository.
