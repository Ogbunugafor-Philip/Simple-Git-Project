# greenwood-library-website

# Collaborative Development Project on GitHub

## Introduction
Welcome to this Collaborative Development Project using GitHub! This project demonstrates the power of teamwork and the incredible results that can be achieved when developers from diverse backgrounds collaborate to build software solutions. By leveraging GitHub as a version control tool, we explore various aspects of collaborative development, providing a comprehensive understanding of the entire process.

Through GitHub's powerful features, such as version control, issue tracking, code review, and continuous integration, we aim to foster a learning environment where contributors can enhance their skills, share knowledge, and gain hands-on experience in a real-world development setting. Join us on this journey of teamwork and learning, and let's create something remarkable together!

## Objectives
- Practice cloning a repository and working with branches in Git.
- Gain experience in staging, committing, and pushing changes from multiple developers.
- Create pull requests and merge them after resolving any potential conflicts.

## Project Steps

### Step 1: Setting Up the Repository
1. **Create a GitHub repository** named `greenwood-library-website`.
2. **Clone the repository** by selecting the code of the repository and running the following command in Git Bash:
   ```bash
   git clone https://github.com/Ogbunugafor-Philip/greenwood-library-website.git
   ```
3. **Open the main branch** in VS Code and create files for each webpage, adding random content to each:
   - `home.html`
   - `about_us.html`
   - `events.html`
   - `contact_us.html`
4. **Stage, commit, and push the changes** directly to the main branch:
   - Stage changes:
     ```bash
     git add .
     ```
   - Commit changes:
     ```bash
     git commit -m "my first commit"
     ```
   - Add the origin:
     ```bash
     git remote add origin https://github.com/Ogbunugafor-Philip/greenwood-library-website.git
     ```
   - Push changes:
     ```bash
     git push origin main
     ```
     <button onclick="navigator.clipboard.writeText('git push origin main')">Copy</button>
5. **Confirm success** by checking the GitHub repository to ensure the files are visible.

### Step 2: Adding Book Reviews
1. **Create a branch** for developer Morgan and switch to the new branch:
   ```bash
   git checkout -b Adding-Book-Review
   ```
2. **Add a new file** `book_review.html` to represent the book reviews section.
3. **Stage, commit, and push changes** with a descriptive message:
   - Stage changes:
     ```bash
     git add .
     ```
   - Commit changes:
     ```bash
     git commit -m "Add book review section"
     ```
   - Push changes:
     ```bash
     git push origin Adding-Book-Review
     ```
4. **Merge Morgan's work** into the main branch:
   - Switch to the main branch:
     ```bash
     git checkout main
     ```
   - Pull the latest changes:
     ```bash
     git pull origin main
     ```
   - Merge the branch:
     ```bash
     git merge Adding-Book-Review
     ```
   - Push changes to the main branch:
     ```bash
     git push origin main
     ```

### Step 3: Updating the Events Page
1. **Create a branch** for developer Morgan and switch to the new branch:
   ```bash
   git checkout -b Updating-event-Page
   ```
2. **Update the `events.html` file** with relevant content.
3. **Stage, commit, and push changes** with a descriptive message:
   - Stage changes:
     ```bash
     git add .
     ```
   - Commit changes:
     ```bash
     git commit -m "Updating event page"
     ```
   - Push changes:
     ```bash
     git push origin Updating-event-Page
     ```
4. **Merge Morgan's work** into the main branch:
   - Switch to the main branch:
     ```bash
     git checkout main
     ```
   - Pull the latest changes:
     ```bash
     git pull origin main
     ```
   - Merge the branch:
     ```bash
     git merge Updating-event-Page
     ```
   - Push changes to the main branch:
     ```bash
     git push origin main
     ```

