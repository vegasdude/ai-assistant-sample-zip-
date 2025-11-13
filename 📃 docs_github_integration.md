---

## 📄 `docs/github_integration.md`

```markdown
# GitHub Integration

This project includes an example GitHub AI assistant that replies to issues automatically.

---

## 🧩 How It Works

1. A user opens a new issue on your repo.  
2. GitHub Actions triggers `ai_assistant.yml`.  
3. The workflow runs your Python or Node script.  
4. The assistant generates a helpful reply using OpenAI API.

---

## ⚙️ Setup Steps

1. Go to your repository on GitHub.
2. Navigate to **Settings → Secrets and variables → Actions**.
3. Add a new repository secret:
