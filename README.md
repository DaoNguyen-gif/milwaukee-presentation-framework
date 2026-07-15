# AI Presentation Framework

Version: 1.0

---

# Objective

This project provides a standardized framework for generating PowerPoint presentations from structured content.

Instead of designing slides every time, AI selects predefined layouts from a single Master Template and fills them with user content.

The objective is to ensure:

- Consistent branding
- Consistent layout
- Consistent typography
- Consistent icon usage
- Fully editable PowerPoint output

---

# Repository Structure

```
presentation-framework/

│
├── framework/
│   ├── Framework.md
│   ├── Component_Library.md
│   ├── Layout_Spec.md
│   ├── Master_Template_Spec.md
│   └── Icon_Dictionary.json
│
├── templates/
│   └── Master_Template.pptx
│
├── source_templates/
│
└── examples/
```

---

# Workflow

```
User Content
      │
      ▼
Framework.md
      │
      ▼
Layout Selection
      │
      ▼
Master_Template.pptx
      │
      ▼
Placeholder Mapping
      │
      ▼
Icon Selection
      │
      ▼
Editable PPTX
```

---

# Framework Files

## Framework.md

Defines how AI thinks.

Responsibilities

- Analyze content
- Select layout
- Populate placeholders
- Validate output

---

## Component_Library.md

Defines reusable design components.

Examples

- Header
- Footer
- KPI Card
- Timeline
- SIPOC Table
- Process Flow
- Gallery

---

## Layout_Spec.md

Defines every available slide layout.

AI MUST only use these layouts.

---

## Master_Template_Spec.md

Defines the complete structure of Master_Template.pptx.

---

## Icon_Dictionary.json

Maps keywords to icons.

Example

Quality

↓

Shield

Inspection

↓

Clipboard Check

Supplier

↓

Factory

Training

↓

Graduation Cap

---

# Master Template

Master_Template.pptx is the ONLY PowerPoint template used by AI.

AI is NOT allowed to redesign slides.

AI only

- Selects layouts
- Replaces placeholders
- Chooses icons
- Formats content

---

# Design Principles

- Simple
- Clean
- Professional
- Consistent
- Minimal
- White Space First

---

# Layout Rules

Never create new layouts.

Never move logos.

Never change theme colors.

Never change typography.

Never redesign components.

Duplicate layouts when content exceeds available space.

---

# Output Rules

Output format

PowerPoint (.pptx)

Requirements

Editable

Consistent

Corporate style

Placeholder replaced

Correct icon

Correct layout

---

# Roadmap

Phase 1

Repository

✅

---

Phase 2

Framework

✅

---

Phase 3

Master Template

⬜

---

Phase 4

AI Testing

⬜

---

Phase 5

Optimization

⬜

---

End of README
