# CLAUDE.md - AI Assistant Guide

## Repository Overview

**Repository**: `mrhaste-pm/mrhaste-pm`
**Type**: GitHub Profile Repository
**Purpose**: Personal GitHub profile page that appears on the user's profile at github.com/mrhaste-pm

This is a special GitHub repository where the README.md content is automatically displayed on the owner's GitHub profile page.

## Repository Structure

```
mrhaste-pm/
├── README.md          # Main profile content (displayed on GitHub profile)
├── CLAUDE.md          # This file - Guide for AI assistants
└── .git/              # Git version control
```

### Key Files

- **README.md**: The primary and only content file. This markdown file is rendered on the user's GitHub profile page. Any changes here directly affect the public profile.

## Technology Stack

- **Language**: Markdown (GitHub Flavored Markdown)
- **Platform**: GitHub Profile Special Repository
- **Version Control**: Git

## Development Workflow

### Branch Strategy

- **Main Branch**: Default branch for all changes
- **Feature Branches**: Use `claude/` prefix for AI-assisted changes
  - Current feature branch: `claude/claude-md-mi9jty59we8nr9l6-01YGhziRCoHjvie3EkjUsu2i`

### Making Changes

1. **Always read README.md first** before making any modifications
2. **Preserve existing structure** unless explicitly asked to change it
3. **Use GitHub Flavored Markdown** syntax
4. **Test markdown rendering** mentally before committing
5. **Keep profile professional** but allow personality to show through

### Git Workflow

```bash
# Always work on feature branches
git checkout -b claude/feature-name

# Make changes to README.md
# Edit the file...

# Stage and commit changes
git add README.md
git commit -m "Descriptive commit message"

# Push to feature branch
git push -u origin claude/feature-name
```

## Content Guidelines

### README.md Conventions

1. **Profile Introduction**
   - Start with a greeting emoji and name
   - Include professional background (PM experience)
   - Keep it concise and welcoming

2. **Markdown Features to Use**
   - Emojis for visual interest (👋, 👀, ✨, etc.)
   - Lists for organized information
   - Bold/italic for emphasis
   - Links to projects, social media, or portfolio
   - Headers for sections (if content expands)

3. **Common Profile Sections** (add as needed)
   - 👋 Introduction
   - 💼 Professional Experience
   - 🔧 Skills & Technologies
   - 🌱 Currently Learning
   - 📫 How to Reach Me
   - ⚡ Fun Facts
   - 📊 GitHub Stats (using shields.io or similar)
   - 🔗 Links (LinkedIn, Twitter, Blog, etc.)

4. **Content Best Practices**
   - Keep it authentic and personal
   - Update regularly with current information
   - Avoid sensitive personal information
   - Make it scannable (use lists and headers)
   - Consider adding visual elements (badges, stats)

## AI Assistant Instructions

### When Updating the Profile

1. **Always read the current README.md** before making changes
2. **Understand the user's intent** - are they adding, removing, or updating content?
3. **Maintain consistency** with existing tone and style
4. **Preserve working markdown** - don't break existing formatting
5. **Use emojis judiciously** - match the existing style
6. **Keep it concise** - profile content should be brief and impactful

### Common Tasks

#### Adding New Sections
```markdown
## 💼 Professional Background
- 10+ years as Product Manager
- Focus areas: [specific domains]
- Key achievements: [highlights]
```

#### Adding Skills/Technologies
```markdown
## 🔧 Skills & Tools
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
```

#### Adding Contact Information
```markdown
## 📫 How to Reach Me
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)
- Email: your.email@example.com
- Twitter: [@yourhandle](https://twitter.com/yourhandle)
```

#### Adding GitHub Stats
```markdown
## 📊 GitHub Stats
![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=mrhaste-pm&show_icons=true&theme=radical)
```

### What NOT to Do

1. ❌ Don't add unverified information about the user
2. ❌ Don't include sensitive personal data (phone numbers, addresses)
3. ❌ Don't use overly complex markdown that may not render well
4. ❌ Don't make the profile too long (keep it scannable)
5. ❌ Don't remove existing content without explicit permission
6. ❌ Don't change the tone drastically from the original

### Testing Changes

Before committing:
- Mentally verify all markdown syntax is correct
- Check that links are properly formatted
- Ensure emojis are appropriate and render correctly
- Verify list formatting is consistent
- Make sure headings follow a logical hierarchy

## GitHub Flavored Markdown Reference

### Emojis
Use GitHub emoji shortcodes: `:wave:` = 👋, `:eyes:` = 👀, `:sparkles:` = ✨

### Links
```markdown
[Link Text](https://example.com)
```

### Images
```markdown
![Alt Text](https://example.com/image.png)
```

### Lists
```markdown
- Unordered item
- Another item

1. Ordered item
2. Another item
```

### Code
```markdown
`inline code`

```language
code block
```
```

### Badges
Use shields.io for dynamic badges:
```markdown
![Badge](https://img.shields.io/badge/label-message-color)
```

## Commit Message Conventions

Use clear, descriptive commit messages:

- `Add contact information to profile`
- `Update professional background section`
- `Add GitHub stats widget`
- `Fix markdown formatting in skills section`
- `Update README with current projects`

## Current State (as of 2025-11-22)

### Existing Content
- Introduction with name (Roman)
- Professional experience mention (10+ years as PM)
- HTML comment explaining the special repository
- Clean, minimal profile

### Potential Enhancements
The profile is currently minimal. Consider these additions when requested:
- Detailed skills and technologies
- Current projects or focus areas
- Contact information
- GitHub statistics
- Links to portfolio or blog
- Professional achievements
- Areas of expertise in PM

## Resources

- [GitHub Profile README Guide](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Awesome GitHub Profile README](https://github.com/abhisheknaiidu/awesome-github-profile-readme)
- [Shields.io](https://shields.io/) - For badges
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) - For stats widgets
- [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)

## Notes for AI Assistants

1. **This is a public-facing profile** - all changes are immediately visible on GitHub
2. **Respect the user's professional image** - maintain appropriate tone
3. **Be conservative with changes** unless explicitly asked to be creative
4. **Always commit and push changes** to the appropriate branch
5. **Use markdown preview** mentally to ensure proper rendering
6. **Keep accessibility in mind** - use alt text for images
7. **Consider mobile viewers** - keep content scannable

## Questions to Ask Before Major Changes

1. What is the primary goal of your GitHub profile? (Job seeking, networking, showcasing projects)
2. What tone do you prefer? (Professional, casual, technical, creative)
3. What information do you want to highlight? (Skills, projects, experience, personality)
4. Are there any specific projects or achievements you want to feature?
5. Do you have preferred colors or themes for badges/stats?
6. Should I include links to other social media or professional profiles?

---

**Last Updated**: 2025-11-22
**Repository Owner**: mrhaste-pm (Roman)
**Maintained By**: AI Assistants following this guide
