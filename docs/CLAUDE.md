# Documentation Guidelines for Profile Site

## Overview
This directory contains all main content pages for Soma's professional profile site. Each section follows specific formatting and content standards.

## Documentation Structure
```
docs/
├── basic_info.md           # Personal and contact information
├── work_experience/        # Employment history and projects
├── skill.md               # Technical skills matrix
├── education.md           # Academic background
├── certification.md       # Professional certifications
├── oss.md                # Open source contributions
├── behavioral_questions/  # Interview preparation
└── projects/             # Detailed project descriptions
```

## Content Standards

### Front Matter Requirements
Every markdown file must include:
```yaml
---
title: "Page Title"
nav_order: [number]
parent: "Parent Page" (if applicable)
layout: default
---
```

### Formatting Guidelines
- **Headers**: Use proper hierarchy (# > ## > ###)
- **Lists**: Use consistent bullet styles
- **Tables**: Use HTML tables for complex layouts
- **Links**: Relative links for internal navigation

### Section-Specific Rules

#### Basic Info
- Professional summary in 3-4 sentences
- Contact methods clearly listed
- Location and availability status

#### Skills
- Group by category (Languages, Cloud, Tools, etc.)
- Include proficiency levels where relevant
- Keep technology names consistent

#### Work Experience
- Chronological order (newest first)
- STAR method for project descriptions
- Quantifiable achievements emphasized

#### OSS Contributions
- Link to actual PRs/issues
- Describe impact of contributions
- Include repository statistics

## Content Review Checklist
- [ ] All dates use YYYY-MM format
- [ ] Technical terms are accurate
- [ ] Links are working
- [ ] Navigation order is logical
- [ ] Content is achievement-focused