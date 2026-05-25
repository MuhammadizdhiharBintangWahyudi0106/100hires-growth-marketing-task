# My Environment Setup Log - Junior Growth Marketing Specialist Task

Hi! This repository documents my step-by-step process of setting up Cursor IDE and configuring the environment for the technical evaluation. I faced a few system errors along the way, but managed to work around them to get everything ready.

---

## What I Did (Chronology)

### 1. Repository Setup
- First, I created this public repo `100hires-growth-marketing-task` directly on GitHub.
- To save time, I turned on the auto-generated README file.
- Then, I linked my GitHub account with Cursor IDE so the integration runs smoothly.

### 2. Facing Bottlenecks & How I Fixed Them

Since my local Windows machine didn't have all the pre-requisites installed, I ran into a few technical errors. Here is how I solved them manually:

* **Error with Git Commands:**
  I tried running `git clone` inside Cursor's built-in terminal, but got an error saying: `git : The term 'git' is not recognized...`. 
  * *My Fix:* Instead of wasting time troubleshooting the Windows PATH environment variable for Git, I used Cursor’s GUI. I created a local folder named `100hires-growth-marketing-task`, used `File > Open Folder`, and managed the project from there.

* **Cursor Agent Locked Behind Paywall:**
  When I clicked the `Agent` toggle on the Composer panel, a popup appeared: `"Upgrade to unlock premium models"`. It turns out free accounts can't use the automated agent directly.
  * *My Fix:* I bypassed this restriction by using Cursor's regular Chat sidebar panel and applying optimized prompts to generate my documents manually.

* **Error with NPX / Node.js:**
  I tried launching Claude Code from the terminal using `npx @anthropic-ai/claude-code`, but it threw the error: `npx : The term 'npx' is not recognized...` because Node.js isn't installed on this laptop yet.
  * *My Fix:* I bypassed the terminal completely. I went straight to the Cursor Extensions Marketplace GUI, searched for **"Claude Code for VS Code"** (by Anthropic) and **"Codex"** (by OpenAI), and hit install. Both are now successfully running and authenticated.

---

## Current Workspace Status
Even without standard CLI tools like Node or Git installed locally, the workspace is fully functional through Cursor's GUI alternatives. The environment is now optimized and ready for growth operations, user acquisition tracking, and marketing automation tasks.
