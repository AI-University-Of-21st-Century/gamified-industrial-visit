# Gamified Industrial Visit

**Central Repository for the Gamified Industrial Visit Project**

This is the **central hub** for our AI-guided SDLC project that combines industrial visit management with gamification mechanics. All project artifacts, code, documentation, and collaboration happen through this repository.

---

## 🌐 Live Site

**View the interactive PDF viewer:** [Gamified Industrial Visit - PDF Showcase](https://ai-university-of-21st-century.github.io/gamified-industrial-visit/)

Click the link above to view the professional PDF document viewer with:
- 📄 Full PDF viewing capabilities
- 🔍 Zoom controls (50% - 200%)
- ⬅️➡️ Page navigation controls
- ⌨️ Keyboard navigation support (arrow keys)
- 🚀 Fast, optimized rendering with PDF.js

---

## Project Overview

The **Gamified Industrial Visit** project aims to create an engaging, gamified experience for students and professionals attending industrial site visits. Through point systems, achievement levels, and interactive reporting, participants gain deeper insights while staying motivated throughout the visit.

### Key Features (Planned)
- User authentication and profile management
- Gamification system (points, levels, badges)
- Industrial visit task/challenge management
- Real-time progress tracking
- Visit report generation
- Leaderboards and achievements

---

## Repository Access & Roles

**Organization:** AI-University-Of-21st-Century  
**Repository Status:** Private  
**Current Members:** 2 Organization Owners (Full admin access)

### Access Management
- Both members have **Maintainer/Admin** permissions
- Branch protection enabled on `main` branch
- Pull request review required before merging
- All changes tracked via Git commits

---

## Development Workflow

We use **GitHub Codespaces** as our primary development environment, combined with GitHub for collaboration and Git for version control.

### Three-Tier Interaction Model

#### 1. GITHUB (Web UI) - Collaboration & Project Management
Tasks performed in GitHub web interface:
- Creating and assigning **Issues** for features/tasks
- Creating **Projects/Boards** for task tracking
- Managing **access, roles, and branch protection**
- Reviewing and merging **Pull Requests**
- Viewing commit history and release notes
- Managing Codespaces (start/stop/delete)
- Repository settings and documentation

**When to use:**
- Planning sprints
- Code reviews
- Tracking project progress
- Managing access and permissions

#### 2. CODESPACES TERMINAL - Primary Development
Tasks performed inside GitHub Codespaces (browser-based IDE):
- Creating and organizing **project folder scaffolding**
- Writing and editing code
- Running Git commands (git status, git add, git commit, git push)
- Running application and tests locally
- Debugging and development

**When to use:**
- **ALL PRIMARY CODING WORK**
- No need for local Git Bash installation
- Codespaces provides built-in terminal with Git pre-installed

#### 3. GIT BASH (Local) - Optional Backup/Offline Work
Tasks performed on your local machine (optional):
- Clone repo for offline access
- Regular Git operations (pull, push, branch)
- Local development as backup

**When to use:**
- Only if you need local copy or offline work
- **NOT REQUIRED** if all work stays in Codespaces
- Use SSH keys for secure authentication

---

## KEY CLARIFICATION: Git Bash vs Codespaces Terminal

Both run Bash and Git commands, but:

- **Git Bash** = Program installed on your laptop/PC
- **Codespaces Terminal** = Browser-based terminal inside GitHub's cloud dev environment

You **never avoid Bash commands** - you use them in Codespaces instead of local Git Bash.

**Mental Model:**
- Must use Bash/Git commands? YES, for any serious Git workflow.
- Must use Git Bash application? NO, if all work stays in Codespaces.
- Codespaces terminal REPLACES Git Bash for this project.

---

## Getting Started

### For New Developers

1. **Access the Repository**
   - Go to: https://github.com/AI-University-Of-21st-Century/gamified-industrial-visit

2. **Create a Codespace** (Primary development environment)
   - Click green Code button → Codespaces tab → Create codespace on main
   - Wait for browser-based IDE to load
   - You now have a full dev environment with terminal access

3. **Inside Codespace Terminal:**
```bash
# Verify Git is ready
git status

# Create a feature branch
git checkout -b feature/your-feature-name

# Make changes, then commit and push
git add .
git commit -m "Descriptive commit message"
git push -u origin feature/your-feature-name
```

4. **Open Pull Request on GitHub**
   - Go back to repo on GitHub
   - Click Compare & pull request
   - Add description, reference related Issues
   - Request review from other owner
   - Merge after approval

---

## Project Structure (To be Created)

```
gamified-industrial-visit/
├── src/
│   ├── frontend/           # React/Vue UI code
│   ├── backend/            # APIs & server logic
│   └── game-engine/        # Gamification rules
├── docs/
│   ├── vision-and-scope.md
│   ├── requirements.md
│   ├── architecture.md
│   ├── gamification-design.md
│   └── industrial-visit-log.md
├── tests/                  # Automated tests
├── config/                 # Environment config
├── scripts/                # Helper scripts
├── public/                 # Static assets
├── README.md               # This file
├── .gitignore              # Git ignore rules
├── LICENSE                 # Project license
└── package.json / requirements.txt
```

---

## Collaboration Workflow

### For Both Owners

**Step 1: Create Issues**
- Go to Issues tab → New Issue
- Example: "Set up base project scaffolding"

**Step 2: Create Feature Branch (in Codespace)**
```bash
git checkout -b feature/scaffolding
```

**Step 3: Code & Commit (in Codespace)**
```bash
git add .
git commit -m "Set up project scaffolding"
git push -u origin feature/scaffolding
```

**Step 4: Open Pull Request (on GitHub)**
- Click "Compare & pull request"
- Add description and link Issue
- Request review

**Step 5: Code Review & Merge (on GitHub)**
- Other owner reviews
- Click "Merge pull request"
- Delete feature branch

This keeps main stable and ensures reviewed code.

---

## Essential Git Commands

```bash
# Check status
git status
git log --oneline

# Create & switch branches
git checkout -b feature/xyz
git checkout main
git branch -a

# Commit & push
git add .
git add filename.txt
git commit -m "Your message"
git push
git push -u origin feature/xyz

# Pull latest
git pull

# Handle merge conflicts
# 1. Resolve conflicts in files
# 2. git add .
# 3. git commit -m "Resolved merge conflict"
# 4. git push
```

---

## Documentation Structure

All project docs live in `docs/` folder (version-controlled):

- **vision-and-scope.md** - Project goals, stakeholders
- **requirements.md** - Functional & non-functional requirements
- **architecture.md** - System design, tech stack, diagrams
- **gamification-design.md** - Points, levels, badges, mechanics
- **industrial-visit-log.md** - Visit observations, photos
- **sprint-notes/** - Sprint planning & retrospectives

---

## Technology Stack (TBD)

- **Frontend:** (React, Vue, etc.)
- **Backend:** (Node.js, Python, etc.)
- **Database:** (PostgreSQL, MongoDB, etc.)
- **Deployment:** GitHub Pages / Cloud

---

## Questions?

- **Git/merge issues** → Create an Issue
- **Code questions** → Comment on Pull Requests
- **Design decisions** → Create an Issue for discussion
- **Setup problems** → Check GitHub Codespaces docs

---

**Last Updated:** January 2026  
**Maintained by:** AI-University-Of-21st-Century Organization
