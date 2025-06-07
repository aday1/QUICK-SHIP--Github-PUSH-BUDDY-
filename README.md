# 🚀 QUICK-SHIP Git Management Scripts

**Git tools for sloppy devs who just wanna SHIP IT, mate!**

Chuck this bad boy into any messy project and it'll sort your git workflow right out. No fuss, no fancy pants stuff - just pure Aussie engineering that gets the job done.

## 🍺 What's This Thing Do?

### 🎨 Pretty Interface (Because Why Not?)
- **Big ASCII Headers** - Looks sick as
- **Shows Your Branch** - So you know where you're at
- **Stash Counter** - Visual reminder of your mess
- **Fancy Diagrams** - For the commits and pushes and that
- **Clean/Dirty Detection** - Tells ya if you've stuffed something up

### 🎯 Menu That Actually Makes Sense
**THE GOOD STUFF (What You Actually Use):**
- 🚀 **QUICK SHIP** - ⚡ Just bloody send it! (Commit + Clean + Push)
- 📝 **Make Commit** - ⭐ Chuck your changes in
- 🚀 **Push It** - ⭐ Send it to the interwebs
- 🔄 **Stash & Pull** - ⭐ Hide your mess and grab the latest

**OTHER STUFF:**
- 📊 Check Status, 📚 Look at Logs, 📦 See Your Stashes, 📋 Manual Git Check

### 🛡️ Won't Let You Stuff It Up (Much)
- **Stash Options** - Stash/Ignore/Cancel when you've got changes
- **Auto File Cleanup** - Handles package-lock.json and other junk
- **Any Branch Works** - Not hardcoded to main like some amateur hour script
- **Error Handling** - Won't just crash and burn (probably)

## 🚀 How To Use This Thing

### Windows (Because That's What You're On)
```powershell
# Grab the repo
git clone https://github.com/yourusername/QUICK-SHIP--Github-PUSH-BUDDY-.git
cd QUICK-SHIP--Github-PUSH-BUDDY-

# Run it
.\git-manager.ps1
```

### Unix/Linux/macOS (For the Fancy Folks)
```bash
# Get it
git clone https://github.com/yourusername/QUICK-SHIP--Github-PUSH-BUDDY-.git
cd QUICK-SHIP--Github-PUSH-BUDDY-

# Make it work and run it
chmod +x git-manager.sh
./git-manager.sh
```

## 📋 The Menu (It's Pretty Self-Explanatory)

```
╔══════════════════════════════════════════════════════════╗
║                    🎛️  GIT OPERATIONS 🎛️                 ║
║                                                          ║
║    🚀 QUICK ACTIONS (Just Hit Enter):                   ║
║    1. 🚀 QUICK SHIP              ⚡ JUST SEND IT         ║
║       (Commit + Clean + Push Everything)                 ║
║                                                          ║
║    THE USUAL SUSPECTS:                                   ║
║    2. 📝 Create Commit           ⭐ BASIC STUFF          ║
║    3. 🚀 Push Changes            ⭐ SEND IT              ║
║    4. 🔄 Stash & Pull Latest     ⭐ HIDE AND SEEK        ║
║                                                          ║
║    IF YOU'RE FEELING FANCY:                             ║
║    5. 📊 Check Status                                    ║
║    6. 📚 View Git Log                                    ║
║    7. 📦 Show Stash List                                 ║
║    8. 📋 Manual Git Status                               ║
║                                                          ║
║    0. 🚪 Get Outta Here                                  ║
╚══════════════════════════════════════════════════════════╝
```

## 🌟 The Money Shots

### ⚡ QUICK SHIP Mode (The Hero We Deserve)
When you just can't be bothered with proper workflow:
1. **Finds your changes** (even the dodgy ones)
2. **Cleans up the junk** (package-lock.json, logs, whatever)
3. **Commits with whatever message you give it**
4. **Pushes to wherever** (hopefully the right place)
5. **Shows you pretty progress bars** (because why not)

Perfect for "ah stuff it, just ship it" moments!

### 🔄 Enhanced Stash & Pull (For When You've Messed Up)
When you've got changes but need the latest stuff:
- **[S]** Stash your mess and pull (safe as houses)
- **[I]** Ignore your mess and pull anyway (living dangerously)
- **[C]** Cancel and run away (coward's option)

### 📝 Commit Workflow (Pretty Straightforward)
- Shows you what's what
- Stages everything automatically
- Lets you type a message
- Shows fancy ASCII art because we're not animals

## 🎨 What It Looks Like

### Branch Display (Fancy Boxes)
```
╔══════════════════════════════════════════════════════════╗
║                    🌟 CURRENT BRANCH 🌟                  ║
║                                                          ║
║      ┌─── main                                     ───┐  ║
║      │                                            │     ║
║      └────────────────────────────────────────────┘     ║
╚══════════════════════════════════════════════════════════╝
```

### Commit Process (With Pictures!)
```
╔══════════════════════════════════════════════════════════╗
║                   📝 COMMITTING CHANGES 📝               ║
║                                                          ║
║      ┌─ Your Mess ────────┐                             ║
║      │     [Changes]       │                            ║
║      └─────────┬───────────┘                            ║
║                │ git add .                              ║
║                ▼                                        ║
║      ┌─ Staging ───────────┐                            ║
║      │    [Staged]         │                            ║
║      └─────────┬───────────┘                            ║
║                │ git commit                             ║
║                ▼                                        ║
║      ┌─ Done ──────────────┐                            ║
║      │   [Committed]       │                            ║
║      └─────────────────────┘                            ║
╚══════════════════════════════════════════════════════════╝
```

## 🛠️ Setup (Dead Simple)

### What You Need
- **Git** (obviously)
- **PowerShell** (you're on Windows, so you've got it)
- **Internet** (for pushing/pulling)

### First Time Setup
1. **Grab this repo**
2. **Go to the folder**
3. **Run the script**
4. **Configure Git** (if you haven't already):
   ```powershell
   git config --global user.name "Your Name Here"
   git config --global user.email "your.email@whatever.com"
   ```

## 📚 More Reading (If You're Into That)

| File | What's In It |
|------|-------------|
| [`GIT-MANAGEMENT.md`](GIT-MANAGEMENT.md) | All the boring details |
| [`GIT-QUICK-REFERENCE.md`](GIT-QUICK-REFERENCE.md) | Quick how-to guide |
| [`git-v2-completion-summary.md`](git-v2-completion-summary.md) | v2.0 new stuff |
| [`git-implementation-summary.md`](git-implementation-summary.md) | How it works under the hood |

## 🔧 Handles The Annoying Stuff

### Junk File Management
Automatically deals with the usual suspects:
- `package-lock.json` and `react-app/package-lock.json`
- Log files (`*.log`)
- Environment files (`.env.local`)
- System files (`.DS_Store`, `Thumbs.db`)
- Node modules folders

### Works Everywhere
- **Windows**: PowerShell with pretty colors
- **macOS/Linux**: Bash that actually works
- **Same features** no matter what you're running

### Won't Let You Break Everything
- Checks if you're actually in a git repo
- Tests if you can reach the internet
- Gives you helpful errors instead of just dying
- Suggests what to do when things go wrong

## 🚧 When Things Go Wrong

### PowerShell Won't Run Scripts (Windows)
```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

### Permission Problems (Mac/Linux)
```bash
chmod +x git-manager.sh
```

### Git Won't Let You Push
- Set up SSH keys OR
- Use HTTPS with your username/token
- Check you've got internet

## 🤝 Want To Help Out?

1. Fork this thing
2. Make a branch
3. Do your changes
4. Use QUICK SHIP to commit and push!
5. Send a pull request

## 📝 License

It's MIT licensed, so do whatever you want with it.

## 🎯 Why This Exists

**QUICK-SHIP** exists because:
- **Command line git is a pain** when you just want to ship something
- **GUIs are slow** and have too many buttons
- **Scripts should look good** even if they're just tools
- **Sloppy projects need love too** and shouldn't be a nightmare to manage
- **Developers are lazy** and that's perfectly fine

Perfect for when you've got a messy project and just need to get it out the door without thinking too hard about git!

---

## 🌟 What's Changed

- **v2.0** - Made it pretty, added QUICK SHIP, better stash handling
- **v1.0** - Basic menu that worked

**Made by devs, for devs, who just want to ship stuff without the drama** 🚀

*May your commits be frequent and your merge conflicts rare!* 🍺
