---
title: "Spec 3: CSS Typography & Layout"
labels: required, css, status:todo
---

## Pass Requirements (All must be checked)

### CSS Setup
- [ ] External stylesheet linked in HTML `<head>`
- [ ] CSS file in css/ folder (css/styles.css)
- [ ] No inline styles in HTML (style attributes)

### Typography (Measurable Requirements)
- [ ] Body text font-size between 16px and 20px (or 1rem to 1.25rem)
- [ ] Line-height between 1.4 and 1.8 for readability
- [ ] At least 2 different font-families used purposefully
- [ ] Poem text is NOT in default browser fonts (Times, Arial)

### Layout Requirements  
- [ ] Content has max-width between 600px and 800px
- [ ] Content is centered using margin: auto OR flexbox/grid
- [ ] Padding prevents text from touching viewport edges
- [ ] No horizontal scroll at any viewport width (320px to 1920px)

### Visual Hierarchy
- [ ] Poem title is visually distinct from body (size, weight, or color)
- [ ] Stanzas have visual separation (margin or padding)
- [ ] Color contrast passes WCAG AA (4.5:1 for body text)
- [ ] Evidence: Screenshot from contrast checker tool

### Responsive Design
- [ ] Readable on mobile (375px width)
- [ ] Readable on desktop (1440px width)  
- [ ] At least one @media query adjusts layout or typography

### Evidence Location
- [ ] Save contrast checker screenshot to: `docs/evidence/design/`
- [ ] Save mobile view screenshot to: `docs/evidence/design/`
- [ ] Save desktop view screenshot to: `docs/evidence/design/`

### Status Signal
When ALL boxes are checked, change label from `status:todo` to `status:ready-for-review`

---
⚠️ **This is PASS/FAIL** - All boxes must be checked for credit