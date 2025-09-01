---
title: "Spec 1: Professional Tooling Setup"
labels: required, setup, status:todo
---

## Pass Requirements (All must be checked)

### NPM Setup
- [ ] package.json exists with name, version, and description fields
- [ ] node_modules/ is in .gitignore file

### Prettier Configuration  
- [ ] .prettierrc file exists with at least 2 configuration options
- [ ] npm run format command works and formats all HTML/CSS files
- [ ] Evidence: Run command and paste output showing files formatted

### Linting Setup
- [ ] HTMLHint installed with .htmlhintrc configuration file
- [ ] Stylelint installed with .stylelintrc.json configuration file  
- [ ] npm run lint command works and checks both HTML and CSS
- [ ] Evidence: Run command and paste output (warnings OK, errors must be fixed)

### AI Documentation
- [ ] ai-process-log.md exists in docs/ folder with at least 2 prompts used for setup
- [ ] Each prompt entry includes: the prompt, AI response summary, what you modified

### Evidence Location
- [ ] Save screenshot of successful npm commands to: `docs/evidence/tooling/`

### Status Signal
When ALL boxes are checked, change label from `status:todo` to `status:ready-for-review`

---
⚠️ **This is PASS/FAIL** - All boxes must be checked for credit