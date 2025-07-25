# ⚡ activity-pinger

> 🌀 A GitHub Action that commits a small update daily — used solely for **learning CI/CD**, **automation workflows**, and **maintaining personal activity**.

---

## 📚 About This Project

This repository contains a **custom GitHub Action** that:

- 🕒 Triggers once every 24 hours using a cron job
- 🧾 Appends a timestamp to a simple log file (`activity.log`)
- 📥 Commits and pushes the update back to the `main` branch
- 👨‍💻 Allows me to practice GitHub Actions, scripting, and workflow automation

This project was built **purely for educational purposes** as part of my learning journey into DevOps, automation, and GitHub Actions.

---

## ⚙️ Workflow Features

- `schedule`: Runs automatically at **midnight UTC** every day
- `workflow_dispatch`: Manually triggerable via GitHub UI
- Uses a **secure PAT (Personal Access Token)** stored in GitHub Secrets
- Adds a timestamp to `activity.log` and commits the file
- Skips commit if no changes are detected

---

## 🚨 GitHub-Friendly Use Policy

> ✅ **This action is not used to manipulate contribution streaks, inflate activity, or exploit GitHub's systems.**  
> ✅ It makes a valid change to a log file as part of an automation test.  
> ✅ This repository is active, and all automation is intentional, meaningful, and user-triggered.

This project aligns with GitHub's [Terms of Service](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service) and [Community Guidelines](https://docs.github.com/en/site-policy/github-terms/github-community-guidelines).

---

## 💡 Use Cases

- Learning GitHub Actions
- Practicing automation pipelines
- Exploring scheduled jobs & secure token handling
- Maintaining a clean, minimal, personal log

---

## 🔐 How to Use

1. Fork this repo
2. Generate a **Personal Access Token (PAT)** with `repo` access
3. Add your PAT as a GitHub Secret named `PAT`
4. Manually run or let it trigger daily

---

## 👤 Author

Built with 💙 by [SriramBharath-7](https://github.com/SriramBharath-7)

> 💬 "This is part of my cybersecurity and DevOps learning. Not for gaming the system — just sharpening the blade."

---

## 🛑 Disclaimer

This repo and its automation:
- Do **not** violate GitHub rules
- Are used only for **genuine educational purposes**
- Are **transparent** in what the workflow does

If GitHub ever updates their guidelines, I’ll promptly adjust this repo accordingly.
