# Hooks commit to Change-ID

Usage :

```bash
mkdir -p ~/.githooks && sudo wget https://raw.githubusercontent.com/ramaadni/hooks/refs/heads/main/commit-msg -O ~/.githooks/commit-msg && sudo chmod +x ~/.githooks/commit-msg
```

Set Git Configuration (If not already done) :

```bash
git config --global core.hooksPath ~/.githooks
```
