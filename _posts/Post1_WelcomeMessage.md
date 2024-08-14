---
layout: post
title: Lab Notebook Generation
date: '2024-08-14'
---

Lab Intro to Open Lab Notebook on GitHub

Step1: fork repository from lab notebook of interest
Step2: edit config file on your local respository with your own personal information
Step3: push repository to Github
Follow https://github.com/barryclark/jekyll-now for more detailed instructions

# Use git to stage, commit, and push NEW_MD_FILE to GitHub
git add "$NEW_MD_FILE"
git commit -m "created new post: $NEW_MD_FILE"
git push origin master
