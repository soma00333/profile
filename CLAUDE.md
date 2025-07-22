# Project Guidelines for Soma's Profile Site

## Overview
This is a Jekyll-based professional profile website using the Just the Docs theme. The site showcases Soma Utsumi's professional experience, skills, and achievements.

## Project Structure
```
profile/
├── index.md                 # Home page with professional summary
├── docs/                    # Main documentation directory
│   ├── basic_info.md       # Personal information
│   ├── work_experience/    # Work history and projects
│   ├── skill.md            # Technical skills
│   ├── education.md        # Educational background
│   ├── certification.md    # Professional certifications
│   ├── oss.md             # Open source contributions
│   └── ...                 # Other sections
├── _config.yml             # Jekyll configuration
└── assets/                 # Stylesheets and static files
```

## Important Guidelines

### Content Updates
- **Always maintain consistency** between related sections
- **Use proper Jekyll front matter** with title, nav_order, and layout
- **Follow existing naming conventions** for new files
- **Preserve the navigation hierarchy** when adding new sections

### Formatting Standards
- **Dates**: Use YYYY-MM format (e.g., 2024-10)
- **Company names**: Use official full names
- **Project references**: Use format like CR1, EU2 (CompanyInitials + Number)
- **Skills**: Group by category and use consistent naming

### Writing Style
- **Professional tone**: Clear, concise, achievement-focused
- **Active voice**: "I developed..." not "Was responsible for..."
- **Quantify achievements**: Include metrics where possible
- **Technical accuracy**: Verify all technical terms and versions

### Build and Deploy
```bash
# Local development
bundle install
bundle exec jekyll serve

# The site is automatically deployed via GitHub Actions
```

## File-Specific Rules

### Work Experience Files
- Each company gets its own markdown file in `docs/work_experience/`
- Include company overview, role details, and key projects
- Link projects to the main work experience index

### Adding New Sections
1. Create new .md file in appropriate directory
2. Add proper front matter with nav_order
3. Update parent index if applicable
4. Test navigation locally before committing

## Maintenance Notes
- **Check broken links** regularly
- **Update skills and certifications** as they change
- **Review content accuracy** quarterly
- **Keep project descriptions current**