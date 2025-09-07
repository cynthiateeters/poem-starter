# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **Poetry Interpretation Page** project template for students learning web development through GitHub Issues-based specifications. The project follows a structured learning approach where students complete 4 required specifications tracked as GitHub Issues.

## Workflow Architecture

### Issue-Driven Development
- Project requirements are defined as GitHub Issue specifications in `.github/issue-specs/`
- Students initialize specs by creating an "Initialize Specifications" issue
- GitHub Actions automatically creates 4 specification issues with `status:todo` labels
- Each spec must be completed in full (pass/fail) and marked `status:ready-for-review`
- Progress tracking through issue labels is essential to the workflow

### Four Core Specifications
1. **Professional Tooling Setup** (`01-core-tooling.md`)
   - NPM package.json with scripts
   - Prettier formatting with `.prettierrc`
   - HTMLHint and Stylelint with configuration files
   - Evidence screenshots in `docs/evidence/tooling/`

2. **Semantic HTML Structure** (`02-core-html.md`)
   - HTML5 semantic elements (header, main, article/section, footer)
   - W3C validation (0 errors required)
   - Accessibility compliance
   - Evidence screenshots in `docs/evidence/validation/`

3. **CSS Typography & Layout** (`03-core-css.md`)
   - External stylesheet in `css/styles.css`
   - Typography requirements (16-20px body text, 1.4-1.8 line-height)
   - Responsive layout (max-width 600-800px, centered)
   - WCAG AA contrast compliance (4.5:1)
   - Evidence screenshots in `docs/evidence/design/`

4. **Documentation & Deployment** (`04-core-documentation.md`)
   - Git commit history (8+ meaningful commits)
   - Netlify deployment with custom domain name
   - AI process documentation
   - Evidence screenshots in `docs/evidence/deployment/`

## Required Project Structure

```
├── index.html              # Main poem page
├── css/styles.css          # External stylesheet
├── package.json            # NPM configuration
├── .prettierrc             # Prettier config
├── .htmlhintrc             # HTMLHint config
├── .stylelintrc.json       # Stylelint config
├── docs/
│   ├── ai-process-log.md   # AI interaction documentation
│   └── evidence/           # Screenshot evidence
│       ├── tooling/        # NPM & linting screenshots
│       ├── validation/     # W3C validator screenshots
│       ├── design/         # Contrast & responsive screenshots
│       └── deployment/     # Git log & Netlify screenshots
```

## Common NPM Scripts (When Setup)

```json
{
  "scripts": {
    "format": "prettier --write *.html css/*.css",
    "lint": "htmlhint *.html && stylelint css/*.css"
  }
}
```

## Development Commands

- `npm run format` - Format HTML and CSS files with Prettier
- `npm run lint` - Check HTML and CSS for errors/warnings
- Students must document ALL AI interactions in `docs/ai-process-log.md`
- Evidence screenshots required for each specification completion

## Key Educational Requirements

### AI Documentation
- Every AI interaction must be logged in `docs/ai-process-log.md`
- Format: Date (YYYY-MM-DD), Context, Tool Used, Prompt, Response Summary, Modifications, Learning Notes
- Minimum 5+ documented interactions required
- Final reflection paragraph required

### Evidence Collection
- Screenshots required for each specification
- Must be saved in appropriate `docs/evidence/` subdirectories
- Evidence is part of pass/fail grading - missing evidence = incomplete spec

### Pass/Fail Criteria
- ALL checkboxes in ALL specifications must be completed
- No partial credit - each spec is complete or incomplete
- Issue labels must be updated from `status:todo` to `status:ready-for-review`

## Deployment Notes

- Netlify deployment required
- Custom site name (not random generated)
- All assets must load correctly on live site
- No console errors in deployed version

## Important Constraints

- No package.json exists initially - students create it as part of Spec 1
- No build tools or frameworks - pure HTML/CSS project
- Focus is on professional workflow and tooling, not advanced features
- All specifications are pass/fail with complete requirements