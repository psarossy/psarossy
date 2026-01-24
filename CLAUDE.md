# CLAUDE.md - AI Assistant Guidelines

## Repository Overview

This is a **GitHub Profile README repository** - a special repository where the repository name matches the GitHub username (`psarossy`). The README.md content is automatically displayed on the owner's GitHub profile page at https://github.com/psarossy.

## Repository Structure

```
psarossy/
├── README.md      # Profile content displayed on GitHub profile page
└── CLAUDE.md      # This file - AI assistant guidelines
```

## Purpose

This repository serves as Peter Sarossy's public GitHub profile, showcasing:
- Current role at Google (Data Center, Media and Information Security)
- Professional expertise areas (hyperscaler data centers, scalable media security)
- Social links (LinkedIn, Google Scholar)
- GitHub statistics widget

## Content Conventions

### README.md Format
- Uses GitHub-flavored Markdown
- Includes emoji for visual appeal (standard for profile READMEs)
- Contains badge images from shields.io for professional links
- Uses external widget from github-readme-stats.vercel.app for stats display

### Key Elements
1. **Greeting section** - Introduction with current work
2. **Professional links** - LinkedIn badge with clickable link
3. **Expertise areas** - Topics the owner can discuss
4. **Personal info** - Pronouns and fun facts
5. **Academic profile** - Google Scholar link
6. **GitHub stats** - Dynamic statistics widget

## Development Guidelines

### When Making Changes
1. Keep the profile professional and concise
2. Maintain the existing emoji style for consistency
3. Verify all external links are functional
4. Test badge URLs work correctly before committing
5. The stats widget URL should not be modified unless changing themes

### External Dependencies
- **shields.io** - Generates the LinkedIn badge
- **github-readme-stats.vercel.app** - Generates GitHub statistics card
  - Current theme: `gotham`
  - Shows private contribution counts

### Testing Changes
Since this is a profile README, changes can be previewed:
1. Use GitHub's markdown preview when editing
2. After pushing, view the profile at https://github.com/psarossy

## AI Assistant Instructions

### Do's
- Keep changes minimal and purposeful
- Preserve the existing tone and style
- Maintain all working external links
- Use proper markdown syntax
- Commit with clear, descriptive messages

### Don'ts
- Don't remove or break existing badge/widget URLs
- Don't drastically change the layout without explicit request
- Don't add excessive content - profile READMEs should be scannable
- Don't modify personal information without explicit instruction

### Common Tasks
1. **Adding new badges**: Use shields.io format, match existing style
2. **Updating stats widget**: Refer to github-readme-stats documentation
3. **Adding new sections**: Follow the emoji + bullet point pattern
4. **Fixing typos**: Simple correction, maintain formatting

## Git Workflow

- **Main branch**: All changes go directly to main
- **Commit style**: Brief, descriptive messages (e.g., "Update README.md", "add Google Scholar profile")
- **No build process**: Changes are live immediately upon push
