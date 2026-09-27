# 🚀 GitHub Basics for CP317  
#### Brought to you by [case]hacks 💻💡  

> Congrats on making it to **CP317**! 🎉  
> Whether you're building complex systems or collaborating with teammates, GitHub will be your best friend for version control and team-based development.  
>  
> This guide builds on what you may have learned in [CP104 GitHub Basics](link), [CP164 GitHub Basics](link), and [CP213 GitHub Basics](link) where we covered `add`, `commit`, `push`, `fork`, `clone`, `pull` and `branch`.  
>  
> In this edition, you’ll learn how to:
> - 🔁 Create **pull requests** and work as a team  
> - 💥 Resolve **merge conflicts**
> - 🔀 Understand the difference between **merging** and **rebasing**

Let’s get started!

---

# Pull Requests, Conflict Resolution, Merging & Rebasing

This guide focuses on **collaboration**, helping you work with others using GitHub effectively.

## 🔁 Pull Requests (PRs)

Pull Requests allow you to propose changes to the code, and discuss them with your team or instructors.

### How do I create a pull request?

1. Push your branch to GitHub:
```bash
git push origin your-branch-name
```
2. Go to your GitHub repo.
3. Click **Compare & pull request** next to your branch.
4. Add a clear title and description of your changes.
5. Click **Create pull request**.

<details>
<summary>🤔 What is a pull request?</summary>

A pull request (PR) asks the repo owner to review and (hopefully) merge your changes into the main codebase. It's a key part of collaboration in GitHub-based projects.

</details>

---

## 💥 Conflict Resolution

### What do I do if there's a merge conflict?

1. Open the file with the conflict.
2. Look for conflict markers:
```
<<<<<<< HEAD
Your version
=======
Other version
>>>>>>> branch-name
```
3. Edit the file to keep what you want.
4. Save, then commit the changes:
```bash
git add .
git commit -m "Resolved conflict"
```

<details>
<summary>🤔 What is a merge conflict?</summary>

A conflict happens when two people edit the same part of the same file differently. Git doesn’t know which version to keep and asks you to manually resolve it.

</details>

---

## 🔗 Merging vs. Rebasing

### How do I merge a branch?

```bash
git checkout main
git merge feature-branch
```

<details>
<summary>🤔 What is merging?</summary>

Merging brings another branch’s changes into your current branch. It preserves the full history and creates a new "merge commit."

</details>

---

### How do I rebase a branch?

```bash
git checkout feature-branch
git rebase main
```

<details>
<summary>🤔 What is rebasing?</summary>

Rebasing rewrites your branch’s history to make it look like your work was built on top of the latest version of the main branch. It makes history cleaner, but should be used carefully.

</details>

---

### Which one should I use?

<details>
<summary>🤔 Should I merge or rebase?</summary>

- Use **merge** when working in teams—it’s safer and keeps history intact.
- Use **rebase** if you want a cleaner commit history before submitting a pull request. Avoid rebasing shared branches.

</details>

---

These tools help you work together without stepping on each other’s toes.  
Teamwork makes the code work! 🚀

---
## You did it!
You’ve now completed both **parts of GitHub basics** with [case]hacks:
- ✅ CP104: Push, Add, Commit  
- ✅ CP164: Clone, Pull  
- ✅ CP213: Fork, Branch 
- ✅ CP317: Pull Requests, Conflict Resolution, Merging & Rebasing

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