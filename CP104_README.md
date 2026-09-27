# 🚀 Welcome to GitHub Basics: Brought to you by [case]hacks

🎉 **Congratulations on finishing CP104!** You've taken your first big step into the world of programming.

But here’s a heads-up: some of the skills you learned in CP104 (and the code you wrote!) will be super helpful in **CP164**. So let’s make sure you don’t lose that hard work. This guide will walk you through a **fail-proof way to save your content** using **GitHub**.

**Why does Understanding GitHub Matter?**
Why is understand Git important anyways? Git is very important in the tech world, especially if you are trying to break into the Software Engineering world.

Through Git, you can...
- Back up your code automatically 
- Make collaboration easier in your future courses (hint hint: CP 317)
- Helps you build a professional portfolio 

---

## Step 1: Set Up Git & GitHub

If you don't already have a GitHub Account, let's get that set up:

1. **Create a GitHub Account**  
- Go to [https://github.com](https://github.com)  
- Click **Sign Up** and follow the steps  

2. **Download Git**  
- [https://git-scm.com/downloads](https://git-scm.com/downloads)  
- Follow the installation instructions for your operating system.

3. **Set up Git on your computer**  
Open a terminal or Git Bash and run:
```bash
   git config --global user.name "Your Name"
   git config --global user.email "your@email.com"
```
<details><summary>What does <code>--global mean?</code></summary>
<p>The <code>--global</code> flag tells Git to apply these settings everywhere on my laptop, not just for this one project.</p>
</details>


<details><summary>What does this config part do?</summary>
<p><code>git config --global user.name "Your Name"</code>  sets your name in Git. Every time you make a commit, Git will record that it was made by "Your Name".</p>
<p><code>git config --global user.email "you@example.com"</code> sets your email address in Git. That email will be attached to every commit you make and GitHub uses it to link your commits to your account (if the emails match).</p>
</details>



---

## Step 2: Understanding Basic Git Commands with an Examples

Here are the most basic Git workflow commands you need to get your project up on GitHub.

Let’s say your project is in a folder called **CP104-FinalProject** on your computer. Here's how you can upload it to GitHub step by step:

### 1. Open your terminal and go into the project folder
```bash
cd CP104-FinalProject
```
<details><summary>What does <code>cd</code> do?</summary>
<p><code>cd</code> stands for "change directory". It moves you into your project folder.</p>
</details>

### 2. Initialize Git
```bash
git init
```
<details><summary>What does <code>git init</code> do?</summary>
<p>This sets up Git tracking in your project folder, so Git knows to watch your files.</p>
</details>

### 3. Add your files
```bash
git add .
```
<details><summary>What does <code>git add .</code> do?</summary>
<p>This stages all the files in your folder to be included in your next save (called a commit). The "." means "add everything in this folder".</p>
</details>

### 4. Commit your work
```bash
git commit -m "Initial commit"
```
<details><summary>What's happening here?</summary>
<ul>
  <li><code>commit</code> saves a snapshot of your files</li>
  <li><code>-m</code> lets you add a message about what you’ve changed. You can change  the message in the "quotations marks" as needed.</li>
</ul>
</details>

### 5. Create a GitHub repo & connect it
On GitHub, click **New Repository** and name it something like `CP104-FinalProject`. 

### 6. Link your local project to GitHubThen run:
```bash
git remote add origin https://github.com/YOUR-USERNAME/CP104-FinalProject.git
```

Make sure to use the right link to the repository. Otherwise it won't work.

<details><summary>What does <code>git remote add origin</code> mean?</summary>
<p>This tells Git where to send your files. You're linking your local project with the online version on GitHub.</p>
</details>

### 7. Push your project
```bash
git branch -M main
git push -u origin main
```
<details><summary>Break it down</summary>
<ul>
  <li><code>branch -M main</code> renames your branch to "main"</li>
  <li><code>push</code> uploads your code</li>
  <li><code>-u</code> sets the default remote for future pushes</li>
</ul>
</details>

And you're done! You can find your project live on GitHub now. 

---

## Cheatsheet of Basic Git Workflow

Here a recap of the Git commands and process we used in the example above:

### 1. Initialize Git: 

In the folder where you code lives:
```bash 
git init 
```

### 2. Add your files:

This stages your files for a commit:
```bash 
git add .
```

### 3. Commit your changes: 

This gaves a version of you work:
```bash 
git commit -m "Add initial project files"
```
### 4. Push to GitHub: 

First, create a repository on GitHub. Then connect it to your local project:
```bash
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git branch -M main
git push -u origin main
```

---
## Additional Resources

Here are some additional resources too help you out!
- (Link our video once it's made)
- [Git Cheatsheet by GitHub](https://education.github.com/git-cheat-sheet-education.pdf) 


---
## Acknowledgements

This quick guide was brought to you by **[case]hacks**!

Make sure to keep an eye on our repositories! We will be posting guides and videos on how to use the code you learned in class and turn it into actual projects!

[case]hacks (our website link)

Happy Coding 💛!
