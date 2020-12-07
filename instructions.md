# Instructions

1. Accept the assignment but don't clone the repo. You will have access to your repo `rails-intro-[your_github_user]` as always.
2. Following the rails guide, you will create a `blog` repo containing your Rails app. First, inside your blog repo, change the name of `master` branch to `main`:

```bash
$ git branch -m master main
```
   Then, add a new `remote` pointing to your github classroom repo.

```bash
$ git remote add origin git@github.com:codeableorg/rails-intro-[your_github_user].git
```

3.  Make a "pull and rebase" from the remote origin (your github repo)

```bash
$ git pull --rebase origin main
```

Rebase is an special type of merge where you try to put all your "new" commits on top of the remote branch commits. You won't have any conflicts in this occasion.

4.  Finally, push your changes to your github repo.

```bash
$ git push origin main 
```
