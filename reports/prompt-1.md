I need you to modify the GitHub issue specification files in this poetry project repository. Here are the Phase 1 critical changes needed:

## Context

- Location: /Users/cynthiateeters/Documents/Teaching/Fall-2025/WDII-Fall-2025/poem-starter/.github/issue-specs/
- Files to modify: 01-core-tooling.md, 02-core-html.md, 03-core-css.md, 04-core-documentation.md
- Students will use GitHub Copilot Agent (with @workspace) not generic AI
- Students already have a project-goals.md from a previous assignment

## Changes Required

### 1. Simplify ALL Four Specs

- Reduce each spec to 5-7 checkboxes maximum (currently 10-15)
- Remove ALL evidence requirements except for TWO total screenshots across entire project:
  1. W3C validation (0 errors) - in spec 2
  2. Live Netlify site - in spec 4
- Add as FIRST checkbox in each spec: "[ ] project-goals.md exists and addresses this spec area"
- Change all "ai-process-log.md" references to "copilot-collaboration.md"

### 2. Evidence Approach

- Remove ALL mentions of evidence folders/subfolders
- Replace with: "The repository itself is the evidence"
- Only keep two screenshot requirements total (W3C in spec 2, Netlify in spec 4)
- These go in a simple "evidence/" folder, not subfolders

### 3. Specific File Changes

**01-core-tooling.md:**

- Simplify to: project-goals check, package.json exists, prettier config, one npm script works, copilot-collaboration started
- Remove: all linting requirements, all screenshot requirements

**02-core-html.md:**

- Simplify to: project-goals check, semantic HTML used, poem structured, W3C validates (ONE screenshot here), @workspace used for review
- Remove: excessive accessibility requirements, detailed element checklists

**03-core-css.md:**

- Simplify to: project-goals check, external CSS, typography readable, responsive, colors accessible, @workspace helped with design
- Remove: all screenshot requirements, specific pixel requirements

**04-core-documentation.md:**

- Simplify to: project-goals check, deployed to Netlify (ONE screenshot here), copilot-collaboration.md complete, meaningful commits
- Remove: "8+ commits" requirement, git log screenshots, excessive documentation requirements

### 4. Update Focus

- Each spec should reference using "@workspace" for help
- Emphasize "Agent vs Chatbot" distinction in copilot-collaboration.md
- Make it clear the repository and live site ARE the main evidence

Please modify all four specification files with these changes, keeping the same YAML frontmatter but dramatically simplifying the requirements.

### 5. Also Update README.md

- Change all "ai-process-log.md" to "copilot-collaboration.md"
- Simplify evidence folder structure to just "evidence/" (no subfolders)
- Add project-goals.md to required files list
- Change evidence requirements to: "Only 2 screenshots required: W3C validation and live Netlify site"
- Add note: "Your repository and live site are your primary evidence"
- Update "Using AI Assistance" section to mention GitHub Copilot Agent and @workspace
- Remove emphasis on linting tools (make them optional)
