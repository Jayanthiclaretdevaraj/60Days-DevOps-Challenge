## 🔧 Day 2 – Linux Shell Scripting & Automation

### 📌 What I Did
- Wrote a basic shell script to:
  - Greet the user
  - Show current date
  - Display hostname and directory
  - Show disk usage

### 📝 Script: `auto_hello.sh`

```bash
#!/bin/bash
echo "👋 Hello, $USER!"
echo "📅 Today is: $(date)"
echo "💻 You are logged in from: $(hostname)"
echo "📂 Your current directory is: $(pwd)"
echo "💾 Your disk usage:"
df -h
