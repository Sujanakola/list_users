# 🔐 GitHub Read Access Checker

A simple bash script to list all users who have **read (pull)** access to a specific GitHub repository using the GitHub API.

---

## 🧠 What It Does

✅ Connects to GitHub using your credentials  
✅ Fetches all collaborators of a given repository  
✅ Lists users who have **read access** (can only view/pull the code)

---

## ⚙️ Requirements

- GitHub [Personal Access Token (PAT)](https://github.com/settings/tokens) with `repo` scope  
- `curl`  
- [`jq`](https://stedolan.github.io/jq/) for JSON parsing  

---

## 🔧 Setup

1. Clone this repository or copy the script locally.

2. Export your GitHub credentials in your terminal:

```bash
export username="your_github_username"
export token="your_personal_access_token"
