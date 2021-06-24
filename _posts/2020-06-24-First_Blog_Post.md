---
title: "Useful Git commands"
date: 2020-06-24
---

The four commands above copy files between the working directory, the stage (also called the index), and the history (in the form of commits).

git add files copies files (at their current state) to the stage.
git commit saves a snapshot of the stage as a commit.
git reset -- files unstages files; that is, it copies files from the latest commit to the stage. Use this command to "undo" a git add files. You can also git reset to unstage everything.
git checkout -- files copies files from the stage to the working directory. Use this to throw away local changes.
