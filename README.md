# Rebase Tutorial
# How To Rebase

Resource: https://www.youtube.com/watch?v=f1wnYdLEpgI&ab_channel=TheModernCoder

## Quick guide

git rebase -i < the branch you are wanting to sync against > \
Typically it will be one of the following,
* git rebase -i origin/dev 
* git rebase -i origin/main

-i stands for Interactive
This is the way we bring up the Interactive menu for rebasing  

It allows us to do a few things. You will mainly be interested in:
* squash 
* fixup (a squash, but without the commit message)
* reword
* drop (**BE CAREFUL WITH THIS ONE**)

# How To Squash

Resource: https://www.youtube.com/watch?v=V5KrD7CmO4o&ab_channel=TheModernCoder
## Quick guide

STARTS WITH --->

pick f40aaaa Your First Commit \
pick 7509865 Another Commit

TO --->

pick f40aaaa Your First Commit \
**squash** 7509865 Another Commit

RESULTS --->

pick **a23d44** Your First Commit








