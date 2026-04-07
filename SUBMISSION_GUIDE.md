# 📋 AIT Submission Guide — PBI Independent Analysis

This guide walks you through submitting your PBI Independent Analysis assignment via GitHub.

---

## Prerequisites

- Git is installed on your machine.
- You have a GitHub account.
- You have been added as a **collaborator** to the `dsp-debug/DellOne-PBI-Independent-Analysis` repository.
- You have accepted the collaboration invite (check your email).

---

## Step-by-Step Instructions

### 1. Clone the Repository

Open your terminal (Git Bash or Command Prompt) and run:

```bash
git clone https://github.com/dsp-debug/DellOne-PBI-Independent-Analysis.git
```

Then navigate into the repo:

```bash
cd DellOne-PBI-Independent-Analysis
```

### 2. Create Your Branch

Create a new branch using your name in lowercase, separated by hyphens:

```bash
git checkout -b firstname-lastname
```

**Example:**
```bash
git checkout -b blessings-chinyama
```

### 3. Create Your Folder

Inside the repo, create a folder with your name using underscores:

```
Firstname_Lastname/
```

**Example:** `Blessings_Chinyama/`

### 4. Add Your Files

Place the following files inside your folder:

| File | What It Is |
|------|-----------|
| `README.md` | A short description of your topic, your data source, and key insights |
| `*.pbix` | Your Power BI report file |
| `CoverLetter.pdf` | A professionally written cover letter presenting your project, its relevance, and what you sought to uncover — written as you would compose a formal submission email to Ms. Chama, Mr. Spratt, and Dr. Shale |
| `Summary.pdf` | A PDF summarizing your findings, key insights, and conclusions |

> ⚠️ **Strict Attention to Detail (ATD) is mandatory.** Your cover letter, file naming, folder structure, commit messages, and PR formatting will all be scrutinized. Sloppy work will not be accepted.

Your folder should look like this:

```
Blessings_Chinyama/
├── README.md
├── Admissions_Analysis.pbix
├── CoverLetter.pdf
└── Summary.pdf
```

### 5. Stage and Commit Your Files

```bash
git add .
git commit -m "PBI Independent Analysis — Blessings Chinyama"
```

Replace the name with your own.

### 6. Push Your Branch

```bash
git push origin firstname-lastname
```

**Example:**
```bash
git push origin blessings-chinyama
```

### 7. Open a Pull Request

1. Go to [https://github.com/dsp-debug/DellOne-PBI-Independent-Analysis](https://github.com/dsp-debug/DellOne-PBI-Independent-Analysis) in your browser.
2. You should see a yellow banner saying **"blessings-chinyama had recent pushes"** — click **Compare & pull request**.
3. Set the **title** to: `PBI Independent Analysis — [Your Full Name]`
4. In the description, briefly state your topic and data source.
5. Click **Create pull request**.

### 8. Done!

Your Pull Request is your submission. Mr. Spratt or Ms. Chama will review it. You may receive comments — check back and respond if needed.

---

## ⚠️ Important Rules

- **DO NOT** push directly to the `main` branch. Always use your own branch.
- **DO NOT** modify any files outside your own folder.
- Use a **professional commit message** (not "asdf" or "test").
- Your PR is your submission. **No PR = No submission.**

---

## Common Errors

| Problem | Solution |
|---------|----------|
| "Permission denied" when pushing | Make sure you accepted the collaborator invite in your email |
| "Branch already exists" | You already created it — just run `git checkout firstname-lastname` |
| "Merge conflict" | You likely modified files outside your folder. Ask Mr. Spratt for help. |
| Can't see the PR button | Make sure you pushed your branch first (`git push origin firstname-lastname`) |

---

*If you are stuck, ask for help. Do not submit late because of a Git issue you didn't report.*
