# Statistical Analysis Project Template

A clean, organized template for statistical analysis projects using Git version control.

## Quick Start

1. Clone or download this template
2. Rename the folder to your project name
3. Initialize Git (if not already done): `git init`
4. Update this README with your project details
5. Start adding your code and documentation

## Directory Structure

```
project-name/
├── Code/           # Analysis scripts (R, SAS, Python, etc.)
├── Data/           # Data files (not tracked by Git)
├── Documents/      # Project documentation and reports
├── Figures/        # Generated plots and visualizations
├── Tables/         # Generated tables and results
├── .gitignore      # Specifies files Git should ignore
└── README.md       # This file - update with project info
```

## Getting Started with Your Project

### 1. Update This README

Replace this template content with:
- Project title and description
- Team members and contact information
- Data sources and requirements
- Software dependencies (R packages, SAS version, etc.)
- Instructions for running the analysis

### 2. Set Up Your Environment

Install required software and packages for your analysis.

### 3. Add Your Data

- Place data files in the `Data/` folder
- Data files are automatically ignored by Git (see `.gitignore`)
- Document your data sources in `Documents/`

### 4. Write Your Code

- Add analysis scripts to the `Code/` folder
- Use numbered prefixes for scripts that run in sequence
- See `Code/README.md` for suggestions

### 5. Generate Outputs

- Save figures to the `Figures/` folder
- Save tables to the `Tables/` folder
- These outputs can be tracked in Git

## Git Workflow

```bash
# Check what has changed
git status

# Add files to staging
git add Code/01_my_script.R

# Commit with a descriptive message
git commit -m "Add initial data cleaning script"

# Push to GitHub (if using remote repository)
git push
```

## What Gets Tracked?

✅ **Tracked by Git:**
- Code files
- Documentation
- Generated figures and tables
- This README and other configuration files

❌ **Ignored by Git:**
- Data files (entire `Data/` folder)
- Temporary files (.log, .lst, .RData)
- System files

See `.gitignore` for the complete list.

## Tips for Success

1. **Commit early and often** - Small, focused commits are easier to understand
2. **Write clear commit messages** - Describe what changed and why
3. **Document your work** - Future you will thank present you
4. **Never commit sensitive data** - Data folder is ignored for a reason
5. **Review changes before committing** - Use `git diff` to see what changed

## Need Help?

- [Git Basics](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
- [GitHub Guides](https://guides.github.com/)
- Ask a colleague who uses Git!

---

## Project Information

**Replace this section with your project details:**

### Project Title
[Your project name here]

### Description
[Brief description of the analysis]

### Team
- [Name] - [Role]
- [Name] - [Role]

### Prerequisites
- R version X.X or higher
  - Required packages: [list packages]
- SAS version X.X (if applicable)

### Data Sources
[Describe where the data comes from]

### Running the Analysis
[Step-by-step instructions for running your analysis]
