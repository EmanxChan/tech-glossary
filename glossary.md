# My Technical Glossary

A personal dictionary of technical terms explained in simple language.

**Last updated**: 2026-01-08

---

## Git & Version Control

### Forking
- **Simple definition**: Making your own copy of someone's project on GitHub that stays connected to the original
- **Analogy**: Like making your own copy of a recipe book that you can modify. Your changes don't affect the original book, but you can still see updates the original author makes and suggest your improvements back to them
- **When you'll use it**: When you want to contribute to someone else's project or create your own version of an existing project
- **Related terms**: Clone, Pull Request, Repository
- **Example**: You love someone's cookie recipe project on GitHub. You fork it to experiment with adding chocolate chips, then you can suggest they add your version to their original recipe book

### Cloning
- **Simple definition**: Downloading a copy of a project from GitHub (the website) to your computer so you can work on it locally
- **Analogy**: Like photocopying recipes and bringing them to your kitchen counter to cook with. The recipes are now on your counter where you have all your cooking tools
- **When you'll use it**: When you need to work on a project locally with your regular tools and editors
- **Related terms**: Fork, Repository, Remote
- **Example**: After forking a project, you clone your fork to your computer so you can edit the files in VS Code or your favorite editor

### Repository (Repo)
- **Simple definition**: A project folder that git is tracking. Contains all your files plus the history of every change ever made
- **Analogy**: Like a recipe binder that not only has the current recipes, but also every previous version and who made what changes
- **When you'll use it**: Every time you work with git - every project is a repository
- **Related terms**: Clone, Fork, Commit

### Git
- **Simple definition**: A tool installed on your computer that tracks changes to files over time
- **Analogy**: Like a super-powered undo button that remembers every version of your work and lets you go back to any point
- **When you'll use it**: When you want to track changes in your code, collaborate with others, or have a safety net for your work
- **Related terms**: GitHub, Commit, Repository

### GitHub
- **Simple definition**: A website where you can store your git repositories online and share them with others
- **Analogy**: Like Google Drive, but specifically designed for code projects with git's time-travel features built in
- **When you'll use it**: When you want to backup your code online, share it with others, or contribute to open-source projects
- **Related terms**: Git, Repository, Fork, Clone

### Push
- **Simple definition**: Uploading your local commits (saved snapshots) from your computer to GitHub
- **Analogy**: Like backing up photos from your phone to iCloud. Your photos stay on your phone AND get copied to the cloud
- **When you'll use it**: After making commits locally, you push them to GitHub to back them up and share them
- **Related terms**: Pull, Remote, Clone
- **Example**: You add 3 new terms to your glossary and commit them locally. Then you "push" those commits to GitHub so they're backed up online

### Remote
- **Simple definition**: The connection between your local repository and the online version on GitHub
- **Analogy**: Like having your friend's phone number saved. The "remote" is the address that tells git where to find the online version
- **When you'll use it**: Git uses this automatically when you push or pull. You set it up once and forget about it
- **Related terms**: Push, Pull, Origin
- **Example**: When you run `git push`, git uses the remote to know "push to GitHub at this specific URL"

---

## How to Use This Glossary

- **When learning**: Look up terms you've forgotten
- **When I add terms**: I'll automatically update this file and commit the changes
- **Seeing history**: Run `git log` in this folder to see every time we've updated the glossary
- **Viewing old versions**: Git keeps every version, so you can always go back to see how your understanding has grown

---

**Terms covered**: 7
