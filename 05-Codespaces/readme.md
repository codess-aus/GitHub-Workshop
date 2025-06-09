#  What’s GitHub Codespaces?
It’s your dev setup in the cloud—no installs, no drama.
Just log in, code, and ship from anywhere with Wi-Fi.

## ⚙️ What’s Inside?
- Fully loaded dev environment 🔧
- Supports all your fave languages & tools 🧪
- Runs in a container = clean, fast, and isolated
- Totally customizable for your project vibe 🎨

## 🔁 Codespace Life Cycle
1. Create it – Boom, workspace ready
2. Pause it – Step away, no worries
3. Reconnect – Pick up right where you left off
4. Delete it – When you’re done, clean it up 🧹
Your changes? Safe and sound the whole time.

![Lifecycle](https://github.com/codess-aus/GitHub-Workshop/blob/f932884c177588b68c4315c5ad6882f5af12656c/assets/codespace-circular-lifecycle.png)

## 🚀 How to Create a Codespace
You’ve got 4 ways to spin up a Codespace:

- From a template – Starting fresh? Use a GitHub template repo 🆕
- From a branch – Working on a new feature? Branch it out 🌿
- From a pull request – Wanna test WIP code? Dive right in 🔍
- From a commit – Debugging history? Time travel to that commit 🕵️‍♀️

##💡 Use It Your Way
- Just testing? Use it temporarily 🧪
- Long-term feature work? Keep it running 🛠️
- Multiple ideas? You can create more than one Codespace per repo or branch (but there’s a limit, so clean up when needed 🧹)

## 🔁 Pro Tips for Workflow

- New Codespace every time? Push your changes often so nothing gets lost 💾
- Long-running Codespace? Pull the latest from main before you start 🔄
- Starting a new project? Use a template, then publish it later 📦

## ⚡ Speed Boost
Repo admins can enable prebuilds to make Codespace creation even faster ⚙️💨

# 🛠️ Codespace Creation = 4-Step Magic
When you spin up a Codespace, here’s what goes down:

- 🖥️ VM + Storage → Your cloud workspace gets its own space
- 📦 Container → Dev tools + languages packed in
- 🔌 Connection → You link up from VS Code, browser, or CLI
- ⚙️ Post-setup → Your custom config kicks in

![Creation](https://github.com/codess-aus/GitHub-Workshop/blob/f932884c177588b68c4315c5ad6882f5af12656c/assets/codespace-connection-editor.png)

## 💾 Saving Your Work
- Web? AutoSave = ON by default
- VS Code? You gotta turn AutoSave ON manually
- Work is saved in the cloud ☁️
- Close it? No prob. Come back later and pick up where you left off
- But if you delete the Codespace = 💥 it’s gone unless you pushed to GitHub

## 🔁 Reopen, Resume, Repeat
- Open your Codespace from GitHub, VS Code, JetBrains, or CLI
- Go to https://github.com/codespaces → pick your repo → resume your session
- You can even hit the . key in a repo to launch it fast ⚡

## ⏱️Timeouts & Disconnects
- Inactive for 30 mins? Codespace sleeps 😴
- Lost internet? No panic—your unsaved changes are still there
- Reconnect and you’re back in action 💪
- Pro tip: Commit + push often if your Wi-Fi’s wobbly

## 🛑 Stop, Restart, or Rebuild
- Stop = saves your work, cuts CPU costs
- Restart = apply changes like new machine type
- Rebuild = refresh your dev container (cache helps speed it up)
- Full rebuild = clears cache, starts fresh
- Only stuff in /workspaces survives a rebuild

## 🧹 Delete When Done
- Pushed your changes? Safe to delete
- Unpushed commits? GitHub will warn you
- You can export changes to a new branch before deleting
- Inactive Codespaces auto-delete after 30 days (or sooner if you set it)

