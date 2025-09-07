# Sample AI Prompts Library for Students

**Reality Note:** AI responses will reflect certain biases (favoring Western, male, older authors for poems) and may occasionally provide incorrect information. Always verify important details and push back if suggestions seem overly complex.

## Pro tip: Start fresh conversations

AI doesn't remember everything from long conversations. For each phase, consider starting a fresh chat to avoid confusion.

## Remember: Trust but verify
- Always search online to confirm your poem exists and is truly public domain
- If AI's suggestions seem complex, ask for simpler alternatives
- When something feels wrong, trust your instinct and push back

**Purpose:** This document provides example prompts to help students understand effective AI collaboration techniques. Use these as starting points, but personalize them with your specific context and needs.

## Phase 1: Poem discovery prompts

### Initial context-building prompt template

``` text
I'm a web development student working on a Poetry Interpretation website project that has specific technical requirements:

Technical Requirements:
- Must use HTML5 semantic elements (header, main, article/section, footer)
- Responsive design supporting 320px to 1920px viewports
- WCAG AA accessibility compliance (4.5:1 contrast ratios)
- Typography using 2+ different font families
- CSS-only styling (no frameworks)
- Professional deployment to Netlify

Personal Context:
- My interests include [your interests, hobbies, themes you connect with]
- My aesthetic preferences lean toward [modern/classic/minimalist/bold/warm/cool/etc.]
- I'm drawn to [specific themes, emotions, or literary styles]
- For poem length, I prefer [short/medium/long poems] because [reason]

CRITICAL CONSTRAINTS:
- MUST be PUBLIC DOMAIN (no copyright restrictions)
- This means poems by authors who died over 70 years ago, or poems explicitly released to public domain
- Must be appropriate for academic display
- Needs to work well with semantic HTML structure
- Should have clear stanza/line break structure for CSS styling

Can you suggest 5-7 PUBLIC DOMAIN poems that would work well for this project, considering both my personal preferences and the technical requirements? For each suggestion, briefly explain why it matches my criteria AND confirm the public domain status.
``` text

### Follow-up refinement prompts

**To narrow down by theme:**
``` text
Of the PUBLIC DOMAIN poems you suggested, I'm most drawn to [specific theme/mood]. Can you suggest 2-3 additional PUBLIC DOMAIN poems that explore [specific theme] but might offer different structural or visual opportunities for web design? Please confirm these are also public domain.
``` text

**To understand technical implications:**
``` text
For the poem "[Title]" by [Author], can you help me understand:
1. How many stanzas and what's the typical line length?
2. Are there any unique structural elements (refrains, unusual line breaks, etc.)?
3. What semantic HTML challenges might this poem present?
4. What opportunities does this structure create for interesting CSS design?
``` text

**To explore creative connections:**
``` text
I'm interested in "[Title]" by [Author]. What visual design elements (colors, typography styles, layout approaches) would complement this poem's mood and meaning? Consider both the emotional tone and any imagery or themes in the text.
``` text

## Phase 2: HTML structure planning prompts

### Initial semantic structure prompt

``` text
I've selected "[Poem Title]" by [Author] for my poetry website project. Here's the poem:

[Include the full poem text]

I need to plan the HTML5 semantic structure for this poem. The technical requirements are:
- Use proper semantic elements (header, main, article, section, footer)
- Support responsive design across all viewport sizes
- Meet WCAG AA accessibility standards
- Create a logical heading hierarchy
- Handle stanzas and line breaks semantically

Can you help me plan:
1. The overall document structure using semantic HTML5 elements
2. How to handle the poem's stanzas (separate sections, divs, or paragraphs?)
3. Line break strategy (br tags vs. separate p elements)
4. Where and how to include author attribution
5. What heading levels would create the best accessibility and SEO structure

Please provide a basic HTML structure outline with explanations for your choices.
``` text

### Accessibility analysis prompt

``` text
Here's my planned HTML structure for my poetry website:

[Paste your HTML structure]

Can you review this structure for WCAG AA accessibility compliance? Specifically:
1. Is my heading hierarchy logical (no skipped levels)?
2. Are there any missing semantic elements that would help screen readers?
3. How should I handle author attribution for maximum accessibility?
4. Are there any ARIA labels or roles I should consider?
5. What alt text considerations do I need for any visual elements?
6. How can I ensure keyboard navigation works well?

Also, what accessibility testing should I plan to do when I implement this?
``` text

### Responsive structure prompt

``` text
My poem has [number] stanzas with varying line lengths. I need the HTML structure to support responsive design from 320px to 1920px viewports.

Questions:
1. Should my HTML structure change at different breakpoints, or should CSS handle all adaptation?
2. How can I structure the stanzas to support flexible layout options?
3. Are there HTML attributes I should include to support responsive images or typography?
4. What viewport meta tag settings are best for a poetry site?
5. How should I structure any navigation elements to work across all screen sizes?

Can you suggest specific HTML patterns that will give me maximum flexibility for responsive CSS design?
``` text

## Phase 3: CSS design strategy prompts

### Design philosophy development prompt

``` text
I've chosen "[Poem Title]" by [Author] for my website project. Here's what the poem is about:

[Brief description of poem's themes, mood, imagery, and emotional tone]

I need to develop a design philosophy that connects the poem's meaning to visual design choices. Help me think through:

1. What emotions or moods does this poem evoke, and how could those translate to visual design elements?
2. Are there specific images, colors, or textures mentioned in the poem that could inspire a color palette?
3. What kind of typography personality would match this poem's voice (elegant, bold, playful, serious, etc.)?
4. Should the layout feel spacious and contemplative, or intimate and cozy?
5. How can I balance honoring the poem's character with meeting modern web accessibility standards?

Can you help me draft a 2-3 paragraph design philosophy that connects these literary elements to specific visual design decisions?
``` text

### Typography planning prompt

``` text
Based on my design philosophy for "[Poem Title]":

[Include your design philosophy from previous conversation]

I need to select two font families - one for headings and one for body text (including the poem). Requirements:
- Must load reliably across all browsers
- Should support the poem's emotional tone and my design philosophy
- Heading font can be more distinctive, body font must prioritize readability
- Need to work well together as a pairing
- Should meet accessibility requirements (good contrast, readable at small sizes)

Can you suggest 3-4 font pairing options with:
1. Specific font names (preferably Google Fonts)
2. Explanation of how each pairing supports my design philosophy
3. Technical considerations (loading, fallbacks, performance)
4. How to establish proper typographic hierarchy with these fonts

Also, what font sizes and line heights would work best for poetry display?
``` text

### Color palette development prompt

``` text
I need to develop a color palette for my poetry website based on this design philosophy:

[Include your design philosophy]

Requirements:
- Must meet WCAG AA contrast standards (4.5:1 for body text)
- Need colors for: background, primary text, headings, and 1-2 accent colors
- Should support the poem's mood while remaining professional
- Must work across all device types and lighting conditions

Can you suggest 2-3 different color palette options with:
1. Specific hex codes for each color
2. Explanation of how each palette connects to my design philosophy
3. Contrast ratio calculations to ensure accessibility
4. Suggestions for how to use each color in the design
5. Any seasonal or cultural considerations I should be aware of

Also, what tools should I use to verify color accessibility before implementing?
``` text

### Layout and responsive strategy prompt

``` text
I need to plan the CSS layout for my poetry website. Here are my constraints:

Technical Requirements:
- Content max-width: 600-800px
- Must be centered in viewport
- Responsive across 320px-1920px viewports
- No horizontal scroll at any size
- Typography must scale appropriately

Poem Structure:
- [Number] stanzas with [description of line lengths/structure]
- Author attribution needs prominent but not overwhelming placement
- [Any special structural elements]

Design Philosophy:
[Brief summary of your design approach]

Can you help me plan:
1. The overall page layout strategy (flexbox, grid, or traditional block?)
2. How to handle responsive typography scaling
3. Spacing system between stanzas and around headings
4. Mobile-first breakpoint strategy
5. How to maintain visual hierarchy across all screen sizes
6. Performance considerations for responsive design

What specific CSS techniques would work best for this poetry layout?
``` text

## Conversation improvement techniques

### Getting better AI responses

**Add specific context:**
- Instead of: "Help me pick a poem"
- Try: "Help me pick a poem that fits my technical constraints and personal aesthetic preferences: [specific details]"

**Ask for multiple options:**
- Instead of: "What's the best approach?"
- Try: "What are 2-3 different approaches I could take, with pros and cons of each?"

**Request explanations:**
- Instead of: "Give me a color palette"
- Try: "Give me a color palette with explanations of how each color supports my design philosophy"

**Iterate and refine:**
- "That's helpful, but can you refine the typography suggestions to be more [specific characteristic]?"
- "I like option 2, but how would it change if I wanted to emphasize [specific aspect] more?"

### When AI responses aren't helpful

**If AI suggests something too generic:**
``` text
That suggestion feels too generic for my specific poem. Can you give me more targeted advice that specifically addresses [your poem's unique characteristics]?
``` text

**If AI misses your constraints:**
``` text
I notice your suggestion doesn't account for [specific constraint]. Can you revise your recommendation considering that I need to [specific requirement]?
``` text

**If you need more technical detail:**
``` text
Can you provide more specific implementation guidance? I need concrete details about [colors/fonts/measurements/etc.] rather than general principles.
``` text

### Follow-up question patterns

- "What would happen if I modified that approach by [specific change]?"
- "How would that work differently on mobile vs. desktop?"
- "What accessibility considerations should I keep in mind with that approach?"
- "Can you suggest 2-3 alternatives that would create a different mood?"
- "What are the potential challenges with implementing that suggestion?"

## Common pitfalls to avoid

**Too vague:** "Help me design a website" → Be specific about your poem, requirements, and goals

**No context:** Starting without explaining your project requirements and constraints

**Accepting first response:** Always ask follow-up questions to refine and improve suggestions

**Not personalizing:** Using AI suggestions without adapting them to your specific needs and vision

**Skipping the "why":** Ask AI to explain reasoning behind suggestions so you can evaluate them

Remember: AI is most helpful when you provide rich context and engage in iterative conversation to refine ideas!
