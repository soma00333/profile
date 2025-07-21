# CLAUDE.md - Documentation Directory

This file provides guidance to Claude Code when working with documentation in the `/docs` directory of the profile repository.

## Directory Overview

This `/docs` directory contains all the Jekyll content for the personal profile website. The structure is organized as follows:

### Content Organization
- **Root Level Pages**: Main navigation items (basic_info.md, skill.md, certification.md, etc.)
- **work_experience/**: Detailed work history organized by company
- **behavioral_questions.md**: Interview preparation responses

### Working with Documentation

When editing documentation in this directory:

1. **Markdown Format**: All content uses Jekyll-compatible markdown with YAML front matter
2. **Navigation Order**: Controlled by `nav_order` in front matter
3. **Parent-Child Relationships**: Use `parent` and `has_children` properties for nested navigation

### Common Tasks

#### Adding New Work Experience
1. Create new file in `work_experience/` directory
2. Follow existing naming convention: `company_name.md`
3. Use consistent project coding (CR, EU, IT, ML)

#### Updating Skills or Certifications
1. Edit the respective markdown file directly
2. Maintain consistent formatting with existing entries
3. Keep dates in ISO format (YYYY-MM)

#### Behavioral Questions
- Located in `behavioral_questions.md`
- Organized by question categories
- Follow STAR method format for responses

### Important Notes
- Test changes locally with `bundle exec jekyll serve` before committing
- All URLs should be relative due to `/profile` base path
- Custom styling changes belong in `/assets/css/custom.css`, not in markdown files