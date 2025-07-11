# React session prerequisite

## Setup instructions
- Clone the repository
- Run via VS code live server: Ctrl+Shift+p -> Live Preview: Start Server
- Navigate to **http://127.0.0.1:3000/** in the browser


## Instructions to submit PR

### 1. ✅ Fork the Repository
- Go to the GitHub repository you want to contribute to.
- Click the **"Fork"** button at the top-right.
- Choose your GitHub account.
- This creates a copy of the repo under your GitHub account.

---

### 2. 📥 Clone Your Fork to Your Computer
```bash
git clone https://github.com/your-username/repo-name.git
cd repo-name
```

### 3. Create a new branch
- Create a separate branch to make your changes.

```bash
git checkout -b my-feature-branch
```

- Replace my-feature-branch with something descriptive like fix-typo, add-footer, etc.

### 4.🛠 Make Your Changes
- Open the project in your code editor (e.g. VS Code).

- Make your improvements or fixes.

- Save your work.

### 5. 💾 Stage and Commit Your Changes
```bash
git add .
git commit -m "your clear and concise commit message"
```
Examples:

   - "fix: corrected typo in README"

   - "feat: added login button"

### 6. 🚀 Push to Your GitHub Fork
```bash 
git push origin my-feature-branch
```

### 7. 🔁 Create a Pull Request (PR)

* Go to your **forked repo** on GitHub.
* Click **"Compare & pull request"**.
* Double-check the PR settings:

  * **Base repository**: original repo (e.g., `original-user/repo`)
  * **Head repository**: your fork (e.g., `your-user/repo`)
  * **Base branch**: usually `main`
  * **Compare**: your feature branch
* Add a title and description for your changes.
* Click **"Create pull request"**.


### 8. ⏳ Wait for Review

* Organizers will review your PR.
* They may approve, request changes, or leave comments.



### **IMPORTANT**: Please fill this out when submitting your pull request. PRs without this may not be reviewed.


---

1. What feature or change did you implement?
Write clearly in your own words what you added/modified. Be specific.

> Example: I added a search bar that filters the list of users by name.




2. Why did you choose to implement this?
Explain your reasoning. What problem does it solve or improve?

> Example: I noticed the user list was long and thought a search would improve usability.




3. How did you approach building this?
Briefly describe the steps you took. Did you try multiple approaches?

> Example: I started with vanilla filtering but later used Array.filter() with lowercase matching.




4. What was the most challenging part for you?
Mention any obstacle you faced and how you overcame it (or where you got stuck).

> Example: I had trouble making the input debounce, so I left that part out for now.




5. Did you refer to any tutorials or resources?
It’s okay to learn from others—just be honest about what you used.

> Example: I used a tutorial on filter functions from MDN and watched a YouTube video on input events.




6. What would you add next if you had more time?
This helps us understand how you think beyond what's required.

> Example: I'd add a dropdown to filter by user role in addition to the search bar.
