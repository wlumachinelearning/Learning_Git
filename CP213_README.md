# 🚀 GitHub Basics for CP213  
#### Brought to you by [case]hacks 💻💡  

> Congrats on making it to **CP213**! 🎉  
> Whether you're diving into data structures or working on practical coding assignments, learning how to navigate GitHub effectively will make your workflow smoother and smarter.  
>  
> This guide builds on what you may have learned in [CP104 GitHub Basics](link) and [CP164 GitHub Basics](link), where we covered `add`, `commit`, `push`, `clone`, and `pull`.  
>  
> In this edition, you’ll learn how to:
> - 🌱 Create and manage **branches**
> - 🍴 **Fork** a repo and keep it in sync

Let’s get started!

---

# Branches & Forks

This guide will help you understand how to use **branches** and **forks** to manage your codebase on GitHub.

## Branches

Branches let you work on features or fixes without affecting the main code.

<details>
<summary>🤔 What is a <code>branch</code>?</summary>

A branch is like a copy of your project where you can make changes without messing up the original (usually the `main` or `master` branch). Once you're happy with your changes, you can merge your branch back into the main one.

</details>

### 🛠️ How to create a branch

**In GitHub (UI):**
1. Go to your repo.
2. Click the dropdown near the branch name (`main` by default).
3. Type a new branch name.
4. Press Enter to create it.

**In Git (Terminal):**
```bash
git checkout -b my-feature
```

### How to switch branches

```bash
git checkout branch-name
```

<details>
<summary>🤔 What does this command do?</summary>

This command switches your local environment to the selected branch so you can work on it.

</details>

### How to delete a branch

**Local branch:**
```bash
git branch -d branch-name
```

**Remote branch:**
```bash
git push origin --delete branch-name
```

<details>
<summary>🤔 When should I use delete? </summary>

Use with caution! Only delete branches that are no longer needed or have already been merged.

</details>

---

## Forks

Forks let you copy someone else's project to your own GitHub account, so you can experiment freely.

<details>
<summary>🤔 What is a fork? </summary>

A fork is a personal copy of someone else's repository. You can work on it independently, and later suggest changes to the original via a pull request.

</details>

### How to fork a repository

1. Go to the repository you want to fork.
2. Click the **Fork** button (top right).
3. Choose your account or organization.

### Keeping your fork up to date

```bash
git remote add upstream https://github.com/ORIGINAL_OWNER/REPO_NAME.git
git fetch upstream
git merge upstream/main
```

<details>
<summary>🤔 What is the purpose of this?</summary>

This keeps your fork in sync with the original repository so you always have the latest code and updates.

</details>

---

By understanding branches and forks, you're well on your way to managing your projects like a pro! 👩‍💻👨‍💻

---
## You did it!
You’ve now completed both **parts of GitHub basics** with [case]hacks:
- ✅ CP104: Push, Add, Commit  
- ✅ CP164: Clone, Pull  
- ✅ CP213: Fork, Pull  

You're well on your way to collaborating like a pro.

---

## Additional Resources

Here are some additional resources to help you out!
- (Link our video once it's made)
- [Git Cheatsheet by GitHub](https://education.github.com/git-cheat-sheet-education.pdf) 

---

## Acknowledgements

This quick guide was brought to you by **[case]hacks**!

Make sure to keep an eye on our repositories! We will be posting guides and videos on how to use the code you learned in class and turn it into actual projects!  
[case]Hacks (our website link)

Happy Coding 💛!