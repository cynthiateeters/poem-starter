---
title: "Spec 2: Semantic HTML Structure"
labels: required, html, status:todo
---

## Pass Requirements (All must be checked)

### Document Structure
- [ ] Valid HTML5 doctype declaration: `<!DOCTYPE html>`
- [ ] Language attribute set: `<html lang="en">`
- [ ] Character encoding set: `<meta charset="UTF-8">`
- [ ] Viewport meta tag for responsive design

### Semantic Elements (All Required)
- [ ] `<header>` contains site title or poem title
- [ ] `<main>` wraps the primary poem content
- [ ] `<article>` OR `<section>` contains the poem itself
- [ ] `<footer>` includes attribution or copyright

### Poem Structure
- [ ] Poem title in an `<h1>` or `<h2>` tag
- [ ] Author attribution present (can use `<cite>` or `<p>`)
- [ ] Each stanza in its own container (div, section, or p)
- [ ] Line breaks preserved using `<br>` OR separate `<p>` tags

### Accessibility Requirements
- [ ] Descriptive `<title>` tag (not "Document" or "Untitled")
- [ ] All images have alt attributes (if images used)
- [ ] Heading hierarchy is logical (no skipped levels)
- [ ] W3C Validator shows 0 errors (warnings acceptable)
- [ ] Evidence: Screenshot or link to W3C validation results

### Evidence Location
- [ ] Save W3C validation screenshot to: `docs/evidence/validation/`

### Status Signal
When ALL boxes are checked, change label from `status:todo` to `status:ready-for-review`

---
⚠️ **This is PASS/FAIL** - All boxes must be checked for credit