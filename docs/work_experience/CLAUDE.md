# CLAUDE.md - Work Experience Directory

This file provides guidance to Claude Code when working with work experience documentation in the `/docs/work_experience` directory.

## Directory Overview

This directory contains detailed work history documentation organized by company. Each file represents a different employer and follows a consistent structure.

## File Organization

### Current Files
- **cybereason.md**: Cybereason (2025-01 to present) - Software Engineer
- **algomatic.md**: Algomatic (2024-11 to 2024-12) - Software Engineer
- **eukarya.md**: Eukarya (2024-04 to 2024-10) - Software Engineer
- **gunosy.md**: Gunosy (2023-11 to 2024-03) - Software Engineer
- **alpaca.md**: Alpaca (2023-08 to 2023-10) - Software Engineer  
- **enechain.md**: enechain (2023-04 to 2023-07) - Software Engineer
- **zuu.md**: Zuu (2022-11 to 2023-03) - Software Engineer
- **layerx.md**: LayerX (2022-04 to 2022-10) - Software Engineer
- **industry_technology.md**: Industry & Technology (2020-06 to 2022-03) - Software Engineer

## Content Structure

Each work experience file should include:

1. **Front Matter**:
   ```yaml
   ---
   layout: default
   title: "Company Name"
   parent: Work Experience
   nav_order: [number]  # Lower numbers appear first
   ---
   ```

2. **Company Header**: Company name and role(s)

3. **Project Sections**: Using the consistent coding system:
   - **CR**: Cloud/Infrastructure projects
   - **EU**: End User/Client-facing projects
   - **IT**: Internal IT/Development projects
   - **ML**: Machine Learning projects

4. **Project Details**: For each project include:
   - Project code and title
   - Duration
   - Technologies/Languages used
   - Architecture description
   - Key responsibilities and achievements

## Formatting Guidelines

### Project Headers
Use consistent format: `### [CODE][NUMBER]: Project Title`
Example: `### CR1: Azure Sentinel Development`

### Technology Lists
- Use bold for "Technologies:" or "Languages:" labels
- List technologies in a comma-separated format
- Group related technologies logically

### Architecture Sections
- Use "Architecture:" as a subheading
- Provide clear, technical descriptions
- Focus on components and data flow

## Common Tasks

### Adding a New Company
1. Create new file: `company_name.md`
2. Add appropriate front matter with correct nav_order
3. Follow the established project coding system
4. Maintain chronological order (most recent first)

### Adding a New Project
1. Determine correct project code (CR, EU, IT, or ML)
2. Assign next available number in that category
3. Follow the standard project structure
4. Include all relevant technical details

### Updating Existing Content
1. Maintain consistent formatting with other entries
2. Preserve the project coding system
3. Keep dates in YYYY-MM format
4. Ensure technical accuracy

## Important Notes

- **Navigation Order**: Companies are ordered by end date (most recent first)
- **Project Order**: Within each company, projects are numbered sequentially by category
- **Technical Detail**: Include specific technologies, frameworks, and methodologies
- **Consistency**: Follow the established pattern from existing files
- **No Emojis**: Professional documentation style only