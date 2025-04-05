# 📖 AI Help Terminal Script

This script allows you to quickly get AI-powered answers to your questions using OpenRouter's API with the Mistral 7B Instruct model.

---
## 🌟 Features
- Simple command-line interface
- Secure API key storage
- Free to use (with OpenRouter's free tier)
---
## 🛠️ Installation
### Steps
1. **Download the script:**
```bash
curl -O https://github.com/Maksonik/terminal_ai_assistant/blob/main/ai_help
```
1. **Go to the folder**:
```bash
cd ./terminal_ai_assistant
```
1. **Make it executable:**
```bash
chmod +x ai_help
```
2. **Move it to your bin directory for global access:**
```bash
sudo mv ai_help /usr/local/bin/
```
---
## 🔑 Obtaining an API Key
1. Go to [OpenRouter API Keys](https://openrouter.ai/settings/keys)
2. Click "Create new key"
3. Copy the key (it should start with `sk-...`)
---
## 🚀 Usage
1. Simply run the script:
```bash
ai_help
```
2. **The first time you run it:**
   - You'll be prompted to enter your OpenRouter API key
   - The key will be securely stored in `.openrouter_key` in the current directory
2. **Subsequent runs** will use the stored key.

### Prerequisites
- Bash shell
- `curl` (usually pre-installed)
- `jq` (will be installed automatically if needed)
---
## 🧹 Uninstallation
To completely remove the script, run the following commands:
```bash
sudo rm /usr/local/bin/ai_help
rm ~/.openrouter_key  # or wherever you first ran it
```