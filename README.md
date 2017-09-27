# qdo
 
Quick bash scripts to support a workflow I use.

I often find while I'm reading through code and working I want to mark places where I need to do something before commit. These aren't `TODO`s I may want to commit, but small tasks I want to be reminded of before I issue a pull request and commit.

Rather than writing them down or breaking them into tasks, I pepper the file with a comment that starts with `qdo` (quick todo). Then I can easily use `:grep qdo` in vim to pull these into a quickfix list and move through them.

The two line bash script will find these and strip them out. This is useful if I decide I don't need to do the tasks or I want to leave them in while I move through the quickfix list.
