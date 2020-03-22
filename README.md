This is a starting point for Python solutions to the
["Build Your Own Git" Challenge](https://codecrafters.io/challenges/git).

In this challenge, you'll build a small Git implementation that's capable of
cloning a public repository, committing changes and pushing back to a git
server. Along the way we'll learn about the `.git` directory, Git objects
(blobs, commits, trees etc.), Git's transfer protocols and more.

**Note**: If you're viewing this repo on GitHub, head over to
[codecrafters.io](https://codecrafters.io) to signup for early access.

# Usage

1. Ensure you have `python (3.8)` installed locally
1. Run `./your_git.sh` to run your Git implementation, which is implemented in
   `app/main.py`.
1. Commit your changes and run `git push origin master` to submit your solution
   to CodeCrafters. Test output will be streamed to your terminal.
 
# Passing the first stage

CodeCrafters runs tests when you do a `git push`. Make an empty commit and push
your solution to see the first stage fail.
   
``` sh
git commit --allow-empty -m "Running tests"
git push origin master
```

The first stage expects you to create a `.git` directory. You should see a
failure message that says the `.git` directory wasn't found. 

Go to `app/main.py` and uncomment the implementation provided. Commit and
push your changes, and you'll now see the first stage pass.

Time to move on to the next stage!
