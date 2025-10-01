<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=200&section=header&text=⌨️%20Linux%20Terminal%20Shortcuts&fontSize=40&fontColor=ffffff&animation=twinkling"/>
</p>

---

## 🧭 Navigation & Editing

| Keys | Action |
|------|--------|
| <kbd>Ctrl</kbd> + <kbd>A</kbd> | Move cursor to **beginning** of line |
| <kbd>Ctrl</kbd> + <kbd>E</kbd> | Move cursor to **end** of line |
| <kbd>Alt</kbd> + <kbd>B</kbd> | Move back **one word** |
| <kbd>Alt</kbd> + <kbd>F</kbd> | Move forward **one word** |
| <kbd>Ctrl</kbd> + <kbd>U</kbd> | Delete from cursor → **start** of line |
| <kbd>Ctrl</kbd> + <kbd>K</kbd> | Delete from cursor → **end** of line |
| <kbd>Ctrl</kbd> + <kbd>W</kbd> | Delete word **before cursor** |
| <kbd>Alt</kbd> + <kbd>D</kbd> | Delete word **after cursor** |
| <kbd>Ctrl</kbd> + <kbd>Y</kbd> | Paste (yank) last deleted text |
| <kbd>Ctrl</kbd> + <kbd>L</kbd> | Clear screen (same as `clear`) |
| <kbd>Ctrl</kbd> + <kbd>_</kbd> | Undo last change (bash only) |

---

## 📜 History & Recall

| Keys | Action |
|------|--------|
| <kbd>↑</kbd> / <kbd>↓</kbd> | Scroll through command history |
| <kbd>Ctrl</kbd> + <kbd>R</kbd> | Search command history (reverse search) |
| <kbd>Ctrl</kbd> + <kbd>G</kbd> | Exit history search without executing |
| `!!` | Run last command again |
| `!abc` | Run last command starting with `abc` |
| `!$` | Last argument from previous command |
| `!*` | All arguments from previous command |
| `^old^new` | Replace text in last command |

---

## ⚙️ Process Control

| Keys | Action |
|------|--------|
| <kbd>Ctrl</kbd> + <kbd>C</kbd> | Kill/terminate process |
| <kbd>Ctrl</kbd> + <kbd>Z</kbd> | Suspend (pause) process |
| `fg` | Resume job in foreground |
| `bg` | Resume job in background |
| `jobs` | List background jobs |
| `kill %n` | Kill job by number |

---

## 🖥️ Screen & Terminal Control

| Keys | Action |
|------|--------|
| <kbd>Ctrl</kbd> + <kbd>D</kbd> | Logout / EOF (End of File) |
| <kbd>Ctrl</kbd> + <kbd>S</kbd> | Stop screen output (pause) |
| <kbd>Ctrl</kbd> + <kbd>Q</kbd> | Resume screen output |
| <kbd>Ctrl</kbd> + <kbd>T</kbd> | Swap last two characters |
| `reset` | Reset broken terminal |

---

## 📂 Command-Line Shortcuts (Shell Tricks)

### 📁 File & Directory
```bash
cd -        # Switch to previous directory
pushd <dir> # Push directory onto stack
popd        # Return to last directory from stack
dirs        # Show directory stack

📜 History Expansion

history   # Show history
!n        # Run command number n
!$        # Last argument of previous command
!!        # Repeat last command



📤 Output & Redirection

command > file      # Redirect output (overwrite)
command >> file     # Redirect output (append)
command 2> file     # Redirect errors
command &> file     # Redirect stdout + stderr
command1 | command2 # Pipe output into another command


📊 Visual Keyboard Map (Quick View)
<p align="center"> <img src="https://user-images.githubusercontent.com/74750414/197353706-0e8a853d-07c1-4d43-8a17-ff1c6a97f0bb.png" width="600" alt="Linux Keyboard Shortcuts"/> </p>
<!-- Footer --> <p align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=100:2c5364,0:0f2027&height=120&section=footer"/> </p> ``
