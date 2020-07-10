You need to symlink pre-commit file in .git/hooks/ directory, because git sources hooks file from .git/hooks/ directory.
It will be easier to manage the scripts if you write scripts in separate folder and just just symlink those in .git/hooks/ directory.

Also need to add executable persmission to run this script.
> $ chmod +x pre-commit
