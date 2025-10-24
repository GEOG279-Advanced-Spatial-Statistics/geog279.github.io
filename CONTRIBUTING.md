# Contributing to GEOG 279 Course Website

Thank you for your interest in contributing to the GEOG 279 course website! This guide will help you understand how to make updates and improvements to the site.

## 📋 Overview

This website is built using R Markdown and Distill, but contributors work with the built HTML files in the `docs/` directory. The source files are maintained by the repository administrator.

## 🚀 Getting Started

### Prerequisites
- Basic knowledge of HTML and CSS
- Git installed on your system
- GitHub account with repository access

### Setup
1. Fork the repository
2. Clone your fork locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/geog279.github.io.git
   cd geog279.github.io
   ```

## ✅ What You Can Contribute

### Content Updates
- **Assignment information**: Due dates, instructions, links
- **Course schedule**: Topics, readings, deadlines
- **Course materials**: PDFs, slides, syllabus
- **Resources**: Books, articles, external links
- **Images and assets**: Logos, diagrams, photos

### Styling and Design
- **CSS improvements**: Colors, fonts, layout
- **Responsive design**: Mobile-friendly updates
- **Visual enhancements**: Icons, formatting

### Documentation
- **README updates**: Course information, instructions
- **Contributing guidelines**: Process improvements
- **Help documentation**: User guides

## ❌ What You Cannot Modify

- Source R Markdown files (`.Rmd`) - these are protected
- Site configuration files (`_site.yml`)
- Build system files
- Repository structure changes

## 🔄 Contribution Workflow

### 1. Create a Branch
```bash
git checkout -b feature/update-assignments
# or
git checkout -b fix/schedule-typo
```

### 2. Make Your Changes
Edit files in the `docs/` directory:
- `docs/assignments.html` - Assignment information
- `docs/course_schedule.html` - Course schedule
- `docs/index.html` - Homepage content
- `docs/css/theme.css` - Styling
- `docs/slides/` - Course slides
- `docs/books/` - Reading materials

### 3. Test Your Changes
```bash
# Open the website locally
open docs/index.html
# or
python -m http.server 8000
# Then visit http://localhost:8000/docs/
```

### 4. Commit Your Changes
```bash
git add .
git commit -m "Update assignment due dates for Week 4"
```

### 5. Push and Create Pull Request
```bash
git push origin feature/update-assignments
```
Then create a pull request on GitHub.

## 📝 Common Update Scenarios

### Updating Assignment Due Dates
1. Edit `docs/assignments.html`
2. Find the assignment table
3. Update the due date in the appropriate row
4. Test the changes locally
5. Commit and create pull request

### Adding New Course Materials
1. Add PDF files to `docs/slides/` or `docs/books/`
2. Update the relevant HTML page to include links
3. Test that links work correctly
4. Commit and create pull request

### Updating Course Schedule
1. Edit `docs/course_schedule.html`
2. Modify the schedule table
3. Update any related content
4. Test the changes
5. Commit and create pull request

### Styling Changes
1. Edit `docs/css/theme.css`
2. Make your CSS changes
3. Test across different pages
4. Ensure responsive design
5. Commit and create pull request

## 🎨 Code Style Guidelines

### HTML
- Use semantic HTML elements
- Maintain proper indentation (2 spaces)
- Include alt text for images
- Ensure accessibility compliance

### CSS
- Use consistent naming conventions
- Comment complex styles
- Maintain responsive design principles
- Follow existing code patterns

### Git Commits
- Use clear, descriptive commit messages
- Follow the format: "Update [specific content]"
- Examples:
  - "Update assignment due dates for Week 4"
  - "Fix typo in course schedule"
  - "Add new reading material to resources"

## 🧪 Testing Guidelines

### Before Submitting
- [ ] Test all links work correctly
- [ ] Verify responsive design on mobile
- [ ] Check for typos and formatting
- [ ] Ensure consistent styling
- [ ] Validate HTML structure

### Testing Checklist
- [ ] Homepage loads correctly
- [ ] Navigation works properly
- [ ] All course materials accessible
- [ ] Assignment links functional
- [ ] Schedule displays correctly

## 🆘 Getting Help

### For Minor Updates
- Check existing documentation
- Review similar changes in the repository
- Test changes thoroughly

### For Major Changes
- Contact the repository maintainer
- Discuss significant structural changes
- Coordinate with other contributors

### Contact Information
- **Repository Issues**: Use GitHub issues for bug reports
- **Email**: baylis@ucsb.edu for course-related questions
- **Pull Requests**: Use GitHub PRs for all changes

## 📚 Resources

### Learning Materials
- [HTML Tutorial](https://www.w3schools.com/html/)
- [CSS Tutorial](https://www.w3schools.com/css/)
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)

### Repository Structure
```
docs/
├── index.html          # Homepage
├── assignments.html    # Assignment information
├── course_schedule.html # Course schedule
├── css/
│   └── theme.css      # Styling
├── slides/            # Course slides
├── books/             # Reading materials
├── journals/          # Journal articles
└── syllabus/          # Course syllabus
```

## 🤝 Code of Conduct

- Be respectful and professional
- Provide constructive feedback
- Help others learn and improve
- Follow the established workflow
- Maintain the quality of the course website

## 📄 License

Contributions to this project are subject to the same license as the main repository.

---

Thank you for contributing to the GEOG 279 course website! Your efforts help create a better learning experience for all students.
