# gexplorer
A modern CLI file explorer for Linux

# 📦 gexplorer Installer

## 🚀 Install Latest Version (Debian-based systems)

```bash
wget https://github.com/gandhardate/gexplorer/raw/main/releases/gexplorer_1.2.0_all.deb
sudo dpkg -i gexplorer_1.2.0_all.deb
```

▶️ Run it
```
gexplorer
```

🧰 Features
🔍 Explore files and folders with keyboard navigation

🎨 Theming support: dark, retro, neon

⚙️ Permissions & Size	i[number] to inspect file size and permissions (ls -lh style)

🌿 Git-aware: displays status of files in Git repos

🧠 Smart execution: Prompts before running executables

🧾 Preview files

✏️ Create/edit/delete files & folders

💻 Command mode for custom terminal operations

🔄 Configurable via ~/.gexplorer


📚 Help Guide
Inside gexplorer, you can press h at any time to view help.

🕹️ Controls & Commands
Command	Description
[number]	:Open the file/folder with that index
p[number]	:Preview the first 10 lines of the file
i[number] :Show size and permission info
d[number]	:Delete the file/folder with that index
n	:Next page of files
p	:Previous page
/keyword	:Filter/search files by name
m	:Make a new file or directory
config	:Open config file in editor and reload
cmd or terminal	:Enter command mode (like mini-shell)
explore	:Exit command mode and return to browser
q	:Quit gexplorer
h	:Show help

⚙️ Configuration
Located at ~/.gexplorer. Default values:
```
SHOW_HIDDEN=false
VIEW_MODE="list"           # list or tiles
EDITOR="vim"               # any terminal editor
THEME="default"            # dark, retro, neon
ENABLE_GIT_STATUS=false    # skip git status check in huge repos
```
