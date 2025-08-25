# How to Upload Your Project to GitHub

Here is a step-by-step guide to get your project from your local computer onto GitHub.

### Prerequisites

1.  **Git Installed:** Make sure you have Git installed on your computer. If not, you can download it from [git-scm.com](https://git-scm.com/).
2.  **GitHub Account:** You need a GitHub account. If you don't have one, sign up at [github.com](https://github.com).
3.  **Project on Your Local Machine:** Your project code should be saved on your computer.

---

### Step 1: Create a New Repository on GitHub

1.  Log in to your GitHub account.
2.  In the top-right corner, click the **+** icon, then select **New repository**.
3.  Give your repository a name (e.g., `indian-bank-app`).
4.  You can add an optional description.
5.  Choose whether to make the repository **Public** or **Private**.
6.  **Important:** Do **not** initialize the repository with a `README`, `.gitignore`, or `license` file, since your project already has these.
7.  Click **Create repository**.

GitHub will now show you a page with some commands. You'll use the URL from this page in the next steps. It will look something like this: `https://github.com/your-username/your-repository-name.git`.

---

### Step 2: Set Up Your Local Project with Git

Now, open a terminal or command prompt on your computer and navigate to your project's root directory.

1.  **Initialize Git:**
    This command creates a new Git repository in your project folder.
    ```bash
    git init -b main
    ```

2.  **Add all your files to be tracked by Git:**
    The `.` means all files in the current directory.
    ```bash
    git add .
    ```

3.  **Commit your files:**
    This saves a snapshot of your files. The message should be a short description of the changes.
    ```bash
    git commit -m "Initial commit"
    ```

---

### Step 3: Connect Your Local Repository to GitHub

1.  **Link your local repository to the one on GitHub:**
    Replace the URL with the one you got from GitHub in Step 1.
    ```bash
    git remote add origin https://github.com/your-username/your-repository-name.git
    ```

2.  **Verify the new remote:**
    You should see `origin` listed with the correct URL.
    ```bash
    git remote -v
    ```

---

### Step 4: Push Your Code to GitHub

**Push your committed files to the repository on GitHub:**
This command uploads your code to the `main` branch on GitHub.

```bash
git push -u origin main
```

And that's it! If you refresh your repository page on GitHub, you will see all of your project files. Now you can manage your code, track changes, and collaborate with others using Git and GitHub.
