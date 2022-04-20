---
layout: default
---
![stability-wip](https://img.shields.io/badge/stability-work_in_progress-lightgrey.svg)

# Code signal Arcade



```
rm -rf code-signal-arcade-intro
rm -rf code-signal-arcade-thecore
rm -rf code-signal-arcade-databases
rm -rf code-signal-arcade-graphs
rm -rf code-signal-arcade-python
rm -rf code-signal-arcade-actual
rm -rf code-signal-arcade-practice
rm -rf code-signal-arcade-bloomtech
rm -rf leetcode-arcade-practice
rm -rf 02-javascript-algorithms-and-data-structures
rm .gitmodules
rm -rf .git
git init
git branch -M main
git remote add origin https://github.com/code-signal/code-signal-arcade.git
git submodule add https://github.com/code-signal/code-signal-arcade-intro.git
git submodule add https://github.com/code-signal/code-signal-arcade-thecore.git
git submodule add https://github.com/code-signal/code-signal-arcade-databases.git
git submodule add https://github.com/code-signal/code-signal-arcade-graphs.git
git submodule add https://github.com/code-signal/code-signal-arcade-python.git
git submodule add https://github.com/code-signal/code-signal-arcade-actual.git
git submodule add https://github.com/code-signal/code-signal-arcade-practice.git
git submodule add https://github.com/code-signal/code-signal-arcade-bloomtech.git
git submodule add https://github.com/leetcode-Arcade/leetcode-arcade-practice.git
git submodule add https://github.com/freeCodeChallenges/02-javascript-algorithms-and-data-structures.git
git add .
git commit -m 'first commit'
git push --set-upstream origin main --force
```

