# CLAUDE.md

This file provides guidance to AI assistants (Claude Code, GitHub Copilot, etc.) when working with code in this repository.

## Project Overview

This is a **Poetry Interpretation Page** project for students learning professional web development through GitHub Issues-based specifications. Students build a single-page website displaying a poem while learning AI agent collaboration, modern tooling, and deployment workflows.

## Student Context

### Prior Work

Students have already completed:

1. **Sarah Jones Learning Site Study** - Understanding AI agents vs chatbots
2. **Project Goals Documentation** - Created `project-goals.md` with their vision
3. **GitHub Copilot Setup** - Have access to Copilot Pro with Agent capabilities

### Current Focus

Students are learning to:

- Use GitHub Copilot's @workspace for context-aware assistance
- Distinguish between chatbot mode (isolated questions) and agent mode (project-aware help)
- Build a website that matches their documented vision in project-goals.md
- Deploy to production using professional workflows

## Simplified Workflow Architecture

### Issue-Driven Development

- 4 streamlined specifications tracked as GitHub Issues
- Each spec has 5-7 clear requirements (pass/fail)
- Progress tracked through issue labels: `status:todo` → `status:ready-for-review`
- Repository and live site serve as primary evidence

### Four Core Specifications

1. **Foundation** - Setup with AI Agent assistance
   - project-goals.md alignment
   - Basic package.json and tooling
   - Copilot collaboration started

2. **Structure** - HTML following the vision
   - Semantic HTML implementation
   - W3C validation (only screenshot #1)
   - @workspace review of structure

3. **Style** - CSS bringing the poem to life
   - Design matching project-goals.md
   - Responsive and accessible
   - @workspace assistance with styling

4. **Ship It** - Deploy and reflect
   - Netlify deployment (only screenshot #2)
   - Copilot collaboration reflection
   - Vision achievement assessment

## Required Project Structure (Simplified)

```
├── index.html              # Main poem page
├── css/styles.css          # External stylesheet
├── package.json            # NPM configuration
├── .prettierrc             # Prettier config
├── project-goals.md        # Student's project vision
├── docs/
│   ├── copilot-collaboration.md # AI interaction documentation
│   └── evidence/           # Only 2 screenshots required
│       ├── w3c-validation.png
│       └── netlify-deployment.png
```

## Student Resources

### Getting started with GitHub Copilot Agent

- **copilot-prompts.md** - Starter prompts for each specification with examples using @workspace
- **copilot-collaboration-template.md** - Template for documenting your AI collaboration process
- **Sarah Jones Learning Site** - Understanding the difference between AI agents and chatbots

### Key Learning Focus

Students should understand and practice the distinction between:
- **Agent mode** (@workspace): Context-aware assistance that can see project-goals.md and entire project
- **Chatbot mode**: Quick syntax/definition questions without project context

The @workspace feature allows Copilot to provide suggestions that align with the student's documented vision in project-goals.md, making the AI assistance more valuable and targeted.
