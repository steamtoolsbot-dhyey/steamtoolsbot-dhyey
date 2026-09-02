# ⚠️ GitHub Token Warning

## Kyro

**DO NOT PASTE YOUR GITHUB TOKEN INTO RAW CODE.**

Never put your GitHub token directly inside source code, scripts, or files.

### ❌ DON'T

```text
ghp_xxxxxxxxxxxxxxxxxxxxxxxxx
```

Do not hardcode your token into:

* `.js`
* `.py`
* `.ps1`
* `.bat`
* `.env` files that are committed
* GitHub repositories
* README files
* screenshots or logs

### ✅ DO

Use GitHub CLI authentication or environment variables instead.

```powershell
gh auth login
```

If an application needs the token, load it from a secure environment variable rather than writing the actual token into the source code.

### 🚨 If You Already Leaked Your Token

**Revoke it immediately and generate a new token.**

> **Kyro, never paste your GitHub token into raw code.**
