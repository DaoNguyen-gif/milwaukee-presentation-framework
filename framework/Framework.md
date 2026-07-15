# Milwaukee Presentation Framework

Version: 1.0

---

# Objective

Generate professional PowerPoint presentations using ONLY the Master_Template.pptx.

The AI is NOT a designer.

The AI is a layout selection and content formatting engine.

---

# Workflow

Step 1

Read all input.

↓

Step 2

Identify

- topic
- audience
- presentation type
- keywords

↓

Step 3

Select layout.

↓

Step 4

Select components.

↓

Step 5

Select icons.

↓

Step 6

Populate placeholders.

↓

Step 7

Validate.

↓

Step 8

Export PPTX.

---

# Layout Selection Rules

Never create a new layout.

Always select one layout from Layout_Spec.md.

Examples

Timeline

↓

L06

SIPOC

↓

L08

Dashboard

↓

L04

Action Plan

↓

L12

Risk

↓

L13

Training

↓

L16

Workshop

↓

L17

Summary

↓

L18

---

# Component Rules

Only use components listed in Component_Library.md.

Never create a custom component.

Reuse existing components whenever possible.

---

# Icon Rules

Read Icon_Dictionary.json.

Find keywords.

Choose the matching icon.

If multiple keywords exist

↓

Choose the most important keyword.

If no keyword matches

↓

Use fallback icon.

---

# Typography Rules

Title

Uppercase

Bold

Maximum two lines.

Subtitle

Sentence Case.

Body

Short paragraphs.

Avoid long text.

---

# Bullet Rules

Maximum

5 bullets.

Maximum

12 words each bullet.

If more than 5 bullets

↓

Split into another slide.

---

# KPI Rules

Maximum

6 KPI cards.

If more than 6 KPIs

↓

Create another KPI slide.

---

# Table Rules

Maximum

10 rows.

If exceeded

↓

Duplicate layout.

---

# Timeline Rules

Maximum

8 milestones.

---

# Process Rules

Maximum

8 steps.

If exceeded

↓

Split into two slides.

---

# Image Rules

One large image

or

Maximum six gallery images.

Never stretch images.

Keep aspect ratio.

---

# Color Rules

Primary

Milwaukee Red

Secondary

Black

Background

White

Accent

Gray

Never introduce additional colors.

---

# Icon Rules

Outline icons only.

Never use emoji.

Never mix icon styles.

---

# Spacing Rules

Always keep equal spacing.

Never overlap components.

Maintain template margins.

---

# Overflow Rules

Never reduce font size below template standard.

Never shrink charts.

Never compress tables.

Duplicate the layout instead.

---

# Output Rules

The final output MUST

- follow Master_Template.pptx
- preserve branding
- keep layout consistency
- keep typography consistency
- keep icon consistency

---

# Validation Checklist

Before exporting

✓ Correct layout

✓ Correct icon

✓ Correct typography

✓ Correct colors

✓ Correct spacing

✓ No overflow

✓ No duplicated titles

✓ Footer present

✓ Header present

If any validation fails

↓

Fix before exporting PPTX.

End of Framework
