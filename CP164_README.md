# 🚀 GitHub Basics for CP164: Clone & Pull  
#### Brought to you by [case]hacks 💻💡

> Congrats on wrapping up **CP164: Data Structures**! 🎉  
> You’ve just leveled up your problem-solving and coding skills, now let’s add some more Git commands to your toolkit.  
>  
> This guide is part two of our GitHub basics series. If you’ve already completed the [CP104 GitHub Basics](https://github.com/your-org/cp104-github-basics) on `push`, `add`, and `commit`, you’re in the right place.  
>  
> In this CP164 edition, you’ll learn how to:
> - 💻 **Clone** a repository to your computer  
> - 🔁 **Pull** changes from a remote repo to stay in sync

Let’s go!

---

## What You’ll Need
- A GitHub account
- Git installed on your machine
- [GitHub Desktop](https://desktop.github.com/) (optional, but helpful)
- Completed CP104 GitHub basics or basic knowledge of Git

---

## Step 1: Clone this repository

<details>
<summary>🤔 What does <code>clone</code> mean?</summary>

Cloning means **downloading a GitHub repository to your own computer** so you can edit files locally.

You’ll use this command so you can make changes using your code editor.

</details>

```bash
git clone https://github.com/casehacks/cp164-github-basics.git
cd cp164-github-basics
```

---

## Step 2: Check your remote

<details>
<summary>🤔 What is a <code>remote</code>?</summary>

A remote is a version of your project that's hosted somewhere else — like GitHub.

- `origin`: the original repo you cloned from (usually the course repo)

You can use Git commands to sync your local repo with the remote one.

</details>

```bash
git remote -v
```

You should see something like:

```
origin  https://github.com/casehacks/cp164-github-basics.git (fetch)
origin  https://github.com/casehacks/cp164-github-basics.git (push)
```

---

## Step 3: Pull changes from the remote repo

<details>
<summary>🤔 What does <code>pull</code> mean?</summary>

Pulling means **downloading and merging changes** from the remote repository (like GitHub) into your current branch on your computer.

This keeps your local version up to date with any new updates from your instructor or team.

</details>

```bash
git pull origin main
```

---

## Step 4: Make changes & commit

<details>
<summary>🤔 What does <code>commit</code> mean?</summary>

A commit is a saved snapshot of your changes. Think of it like hitting "Save + Version History" at the same time.

</details>

```bash
echo "hello from cp164!" >> sample.txt
git add .
git commit -m "Added my greeting"
```

---

## Step 5: Push your changes

<details>
<summary>🤔 What does <code>push</code> mean?</summary>

Pushing sends your commits (saved changes) from your computer back to the GitHub repo.

</details>

```bash
git push origin main
```

---

## You did it!
You’ve now completed both **parts of GitHub basics** with [case]hacks:
- ✅ CP104: Push, Add, Commit  
- ✅ CP164: Clone, Pull  

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