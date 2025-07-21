# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a Jekyll-based personal profile website for Soma Utsumi, deployed to GitHub Pages. The site uses the "Just the Docs" theme and showcases professional experience, skills, certifications, and behavioral interview responses.

## Common Development Commands

### Local Development
```bash
# Install dependencies
bundle install

# Run local development server (accessible at http://localhost:4000/profile)
bundle exec jekyll serve

# Build the site without serving
bundle exec jekyll build

# Clean build artifacts and cache
bundle exec jekyll clean
```

### Dependency Management
```bash
# Update Gemfile.lock with latest compatible versions
bundle update

# Check for outdated gems
bundle outdated
```

## High-Level Architecture

### Jekyll Configuration
The site is configured in `_config.yml` with:
- **Theme**: just-the-docs (v0.10.1) with dark color scheme
- **Base URL**: `/profile` for GitHub Pages deployment
- **Site Title**: "Soma Utsumi"
- **Jekyll Version**: 4.4.1 with Ruby 3.3

### Content Structure and Navigation
Jekyll front matter controls navigation hierarchy:
```yaml
---
layout: default
title: "Page Title"
nav_order: 1  # Controls position in navigation
parent: "Parent Page"  # For nested pages
has_children: true  # For parent pages
---
```

### Key Directories
- **docs/**: Main content directory
  - `work_experience/`: Company-specific pages (zscaler.md, microsoft.md, etc.)
  - Root level files: basic_info.md, skill.md, certification.md, education.md, oss.md, behavioral_questions.md
- **_includes/**: Custom Jekyll includes for template modifications
- **assets/css/custom.css**: Site-specific styling overrides
- **3c3096f9-9144-475b-ba18-c6e1609e8f51_Export-*/**: Notion export data (source material)

### Work Experience Coding System
Work experience uses a consistent project coding format:
- **CR**: Cloud/Infrastructure projects
- **EU**: End User/Client-facing projects  
- **IT**: Internal IT/Development projects
- **ML**: Machine Learning projects
- **Example**: CR1 (first cloud project), EU2 (second end user project)

### GitHub Actions Deployment Pipeline
1. **CI Workflow** (`ci.yml`): 
   - Triggers: Push to main, all PRs
   - Validates Jekyll build succeeds
   
2. **Pages Workflow** (`pages.yml`):
   - Triggers: Push to main only
   - Builds and deploys to GitHub Pages
   - Uses GitHub's pages environment with URL protection

### Content Development Workflow
1. Edit markdown files in `docs/` directory
2. Test locally with `bundle exec jekyll serve`
3. Push to feature branch and create PR
4. CI validates build on PR
5. Merge to main triggers automatic deployment

### Important Development Notes
- **CLAUDE.md** is gitignored and not committed to the repository
- **todo.md** tracks incomplete behavioral questions (also gitignored)
- All URLs must be relative due to `/profile` base path
- Custom CSS changes go in `assets/css/custom.css`
- The Notion export directory contains reference material but is not directly used by Jekyll