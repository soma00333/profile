# Documentation Guidelines

## Overview
This directory contains all documentation sections for Soma's professional profile. Each section focuses on a specific aspect of professional experience and qualifications.

## Section Organization

### Current Sections
- **basic_info.md**: Contact information and personal details
- **work_experience/**: Detailed work history and projects
- **skill.md**: Technical skills categorized by type
- **education.md**: Academic background and coursework
- **certification.md**: Professional certifications and credentials
- **oss.md**: Open source contributions
- **behavioral_questions.md**: Interview preparation content
- **activity.md**: Professional activities and achievements
- **language.md**: Language proficiencies
- **contact.md**: Contact methods and availability

## Content Guidelines

### Writing Standards
- **Clarity first**: Write for both technical and non-technical audiences
- **Consistency**: Use the same terminology throughout all sections
- **Completeness**: Ensure each section tells a complete story
- **Currency**: Keep all information up-to-date

### Formatting Conventions
- **Headers**: Use proper markdown hierarchy (# for title, ## for main sections)
- **Lists**: Use bullets for unordered items, numbers for sequential items
- **Tables**: Use markdown tables for structured data
- **Links**: Prefer internal links between related sections

### Section-Specific Rules

#### Basic Info
- Include only professional-relevant information
- Maintain privacy while being accessible
- Update location and availability status

#### Skills
- Group by category (Languages, Frameworks, Tools, etc.)
- Order by proficiency or relevance
- Include version numbers for specific technologies

#### Education
- List in reverse chronological order
- Include relevant coursework and projects
- Highlight academic achievements

#### Certifications
- Include certification numbers and dates
- Link to verification when possible
- Note expiration dates

## Adding New Sections

1. **Plan the content structure** before creating the file
2. **Use descriptive filenames** (lowercase, underscores for spaces)
3. **Set appropriate nav_order** to maintain logical flow
4. **Add to parent navigation** if creating subsections
5. **Cross-reference** with related sections

## Maintenance Checklist

### Regular Updates
- [ ] Verify all dates are current
- [ ] Check external links still work
- [ ] Update skill versions
- [ ] Add recent projects and achievements
- [ ] Review and refresh descriptions

### Quality Checks
- [ ] Consistent formatting across sections
- [ ] No duplicate information
- [ ] Clear navigation structure
- [ ] Mobile-friendly content
- [ ] Accessible language

## Navigation Structure
```
docs/
├── basic_info.md (nav_order: 10)
├── work_experience/ (nav_order: 2)
│   ├── index.md
│   └── [company].md files
├── skill.md (nav_order: 20)
├── education.md (nav_order: 30)
├── certification.md (nav_order: 40)
├── oss.md (nav_order: 50)
└── ... other sections
```

## Best Practices
- **Test locally** before pushing changes
- **Review in different browsers** for compatibility
- **Get feedback** on major content changes
- **Archive outdated content** rather than deleting
- **Document significant changes** in commit messages