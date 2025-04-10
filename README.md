# Niubi's Natural Commits 💻🌿

This repository uses a GitHub Actions workflow to simulate natural and realistic commit activity.  
Instead of committing every day like a bot (sus!), this workflow:

- Randomly decides whether to commit on a given day
- Makes a random number of commits (1–5) on selected days
- Adds natural time gaps between each commit (1–20 minutes)

## 🤖 How it works

The workflow runs **once daily at 10:00 PM UTC**.

If the day is randomly selected as a commit day, it:
- Updates a file called `commit_number.md`
- Increments the commit number
- Pushes the changes to the repository
- Waits a few minutes between commits to mimic human behavior

This makes your GitHub contribution graph look **active and natural**, without obvious automation patterns.

## 💡 Why use this?

Many developers use GitHub contribution graphs to show consistency.  
But constant, repeated commits can look fake or suspicious.  
This approach gives a **more authentic appearance** of activity while keeping your profile looking fresh.

---

> ⚠️ This is for fun, personal learning, and GitHub profile aesthetics.  
> Don't use this to cheat in real job applications or mislead anyone about your actual work.

---

Made with ❤️ by **Niubi**  

