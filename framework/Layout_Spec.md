# Layout Specification

Version: 1.0

---

# Introduction

This document defines every slide layout available in Master_Template.pptx.

Rules

- AI MUST only use layouts defined here.
- AI MUST NOT create new layouts.
- If content exceeds a layout, duplicate the same layout.
- Every layout is assembled from Component Library components.

---

# L01 - Cover

Purpose

Presentation cover page.

Components

- C001 Header
- C003 Page Title
- C004 Subtitle
- C018 Image Block
- C002 Footer

Input

{{title}}

{{subtitle}}

{{date}}

{{department}}

{{author}}

---

# L02 - Agenda

Purpose

Presentation agenda.

Components

- Header
- Agenda List
- Footer

Maximum

8 agenda items.

Overflow

Create another Agenda slide.

---

# L03 - Section Divider

Purpose

Separate major topics.

Components

- Section Banner
- Large Title
- Subtitle

Used before every new chapter.

---

# L04 - Dashboard

Purpose

Executive summary.

Components

- Header
- KPI Cards ×4
- Issue Card
- Action Card
- Footer

Input

KPI

Issue

Action

Owner

Used for

Weekly Report

Monthly Report

Factory Dashboard

---

# L05 - KPI Summary

Purpose

Display KPI only.

Components

- Header
- KPI Cards

Maximum

6 KPI.

Overflow

Create another slide.

---

# L06 - Timeline

Purpose

Display project schedule.

Components

- Header
- Timeline
- Information Card
- Footer

Maximum

8 milestones.

---

# L07 - Process Flow

Purpose

Display workflow.

Components

- Header
- Chevron Process
- Process Description
- Footer

Example

Receive

↓

Inspect

↓

Assemble

↓

Test

↓

Ship

---

# L08 - SIPOC

Purpose

Supplier Input Process Output Customer.

Components

- Header
- SIPOC Table
- Footer

Columns

Supplier

Input

Process

Output

Customer

---

# L09 - Circular Process

Purpose

Display cyclic process.

Components

- Header
- Circular Process Diagram
- Footer

Maximum

10 nodes.

---

# L10 - Roles & Responsibilities

Purpose

Display responsibility matrix.

Components

- Circular Process Diagram
- Information Cards

Used for

Operation Quality

Training

Workshop

---

# L11 - Standard Table

Purpose

Structured data.

Components

- Header
- Standard Table
- Footer

Maximum

10 rows.

Overflow

Create another slide.

---

# L12 - Action Plan

Purpose

Track actions.

Components

- Header
- Action Table
- Footer

Columns

Action

Owner

Due Date

Status

---

# L13 - Risk Assessment

Purpose

Display project risks.

Components

- Header
- Risk Cards
- Footer

Maximum

6 risks.

---

# L14 - Before After

Purpose

Compare improvements.

Components

- Header
- Before Image
- After Image
- Footer

---

# L15 - Image Gallery

Purpose

Display production photos.

Components

- Header
- Gallery
- Footer

Maximum

6 photos.

---

# L16 - Training Program

Purpose

Training agenda.

Components

- Header
- Number Step
- Information Cards
- Footer

Maximum

6 activities.

---

# L17 - Workshop

Purpose

Interactive activities.

Components

- Header
- Activity Cards
- Icons
- Footer

Used for

Group Discussion

Workshop

Kaizen

---

# L18 - Summary

Purpose

Presentation summary.

Components

- Header
- Summary Box
- Footer

Sections

Achievements

Issues

Next Steps

---

# L19 - Closing

Purpose

Last slide.

Components

- Header
- Thank You
- Footer

---

# Layout Selection Rules

If content contains

Timeline

↓

Use L06

--------------------------------

If content contains

Supplier

Input

Output

Customer

↓

Use L08

--------------------------------

If content contains

KPI

Yield

PPM

OEE

↓

Use L04

or

L05

--------------------------------

If content contains

Action

Owner

Due Date

↓

Use L12

--------------------------------

If content contains

Risk

Severity

Mitigation

↓

Use L13

--------------------------------

If content contains

Before

After

↓

Use L14

--------------------------------

If content contains

Training

Agenda

Session

↓

Use L16

--------------------------------

If content contains

Workshop

Activity

Discussion

↓

Use L17

--------------------------------

If content contains

Summary

Conclusion

↓

Use L18

--------------------------------

Default Layout

If no rule matches

↓

Use L11 Standard Table.
