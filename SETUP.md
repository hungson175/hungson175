# GitHub Profile Setup Guide

This is your GitHub profile README that will appear on your profile page at: https://github.com/hungson175

## Deployment Steps

### 1. Create Special Repository

On GitHub, create a new repository named exactly `hungson175` (matching your username).

- Repository name: `hungson175`
- Description: "My GitHub Profile"
- Visibility: **Public** (required for profile README)
- ✅ Initialize with README: **NO** (we have our own)

### 2. Push This Content

```bash
cd ~/dev/github-homepage/hungson175
git init
git add README.md
git commit -m "feat: Add GitHub profile README

- Animated typing header with name and title
- Tech stack badges (Python, Java, C++, JavaScript, LangChain, OpenAI, etc.)
- Recent projects showcase (AI-teams-controller, coder-mem, deep-research)
- GitHub stats cards with tokyonight theme
- Professional layout for AI/LLM engineer focus"

git branch -M main
git remote add origin https://github.com/hungson175/hungson175.git
git push -u origin main
```

### 3. Verify

Visit: https://github.com/hungson175

Your profile README should now appear at the top of your profile page!

## Features Included

✅ **Animated Typing Header** - Eye-catching introduction with your name and title
✅ **Tech Stack Badges** - Visual representation of your skills
✅ **Recent Projects** - Highlighted work on self-improving coding agents
✅ **GitHub Stats** - Automatic stats cards showing your contributions
✅ **Professional Design** - Purple/indigo theme (tokyonight) for AI/LLM focus
✅ **Contact Information** - Email badge for easy contact

## Customization Tips

- **Theme**: Currently using `tokyonight`. Other options: `radical`, `merko`, `gruvbox`, `dracula`
- **Stats Position**: Cards arranged side-by-side for desktop viewing
- **Projects**: Featured projects align with your CV (AI agents, memory systems, research)
- **Tagline**: "Building AI agents that build themselves" - reflects your current focus

## Preview

The README includes:
1. Animated typing SVG with name and title
2. About section with 20+ years experience highlight
3. Research areas and achievements
4. Tech stack badges (11 technologies)
5. Recent projects with descriptions
6. GitHub stats cards (contributions, languages, streak)
7. Contact section with email
8. Profile view counter

Ready to deploy! 🚀
