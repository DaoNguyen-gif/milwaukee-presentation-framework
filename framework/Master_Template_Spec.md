# Master Template Specification

Version: 1.0

---

# Objective

This document defines the complete structure of Master_Template.pptx.

Master_Template.pptx is the ONLY PowerPoint template used by the AI.

The AI MUST NOT create new layouts.

The AI MUST reuse layouts defined in this document.

---

# Theme

## Slide Size

16:9 Widescreen

13.333 × 7.5 inch

---

## Theme Colors

Primary

Milwaukee Red

Usage

- Section Banner
- Highlight
- Important Text

Secondary

Black

Usage

- Title
- Subtitle

Background

White

Border

Light Gray

Accent

Gray

Status

Green

Warning

Orange

Danger

Red

---

## Typography

Presentation Title

Segoe UI Semibold

32 pt

Uppercase

--------------------------------

Section Title

Segoe UI Semibold

26 pt

--------------------------------

Subtitle

Segoe UI

18 pt

--------------------------------

Body

Segoe UI

14 pt

--------------------------------

Caption

Segoe UI

10 pt

---

## Logo

Position

Top Left

Always visible

Never resized.

---

## Header

Contains

- Milwaukee Logo
- Page Title

Fixed position.

---

## Footer

Contains

- Confidential
- Page Number

Always visible.

---

# Layout Library

Master_Template.pptx contains ONLY the following layouts.

---

L01

Cover

Purpose

Presentation Cover

Contains

Header

Title

Subtitle

Hero Image

Footer

---

L02

Agenda

Purpose

Presentation Agenda

Contains

Header

Agenda List

Footer

---

L03

Section Divider

Purpose

Separate Sections

Contains

Red Banner

Section Title

Subtitle

---

L04

Dashboard

Purpose

Weekly Report

Contains

Header

4 KPI Cards

Issue Summary

Action Summary

Footer

---

L05

KPI Summary

Purpose

Display KPI

Contains

Header

6 KPI Cards

Footer

---

L06

Timeline

Purpose

Project Schedule

Contains

Header

Timeline

Milestone

Footer

---

L07

Process Flow

Purpose

Workflow

Contains

Header

Chevron Process

Description

Footer

---

L08

SIPOC

Purpose

Supplier Input Process Output Customer

Contains

Header

SIPOC Table

Footer

---

L09

Circular Process

Purpose

Relationship Diagram

Contains

Header

Circular Diagram

Footer

---

L10

Table Report

Purpose

Structured Data

Contains

Header

Table

Footer

---

L11

Action Plan

Purpose

Track Actions

Contains

Header

Action Table

Footer

---

L12

Risk

Purpose

Risk Assessment

Contains

Header

Risk Cards

Footer

---

L13

Before After

Purpose

Compare

Contains

Header

Before Image

After Image

Footer

---

L14

Gallery

Purpose

Photo Report

Contains

Header

Image Grid

Footer

---

L15

Summary

Purpose

Presentation Summary

Contains

Header

Achievement

Issue

Next Step

Footer

---

L16

Closing

Purpose

End Presentation

Contains

Header

Thank You

Footer

---

# Placeholder Rules

All layouts MUST use editable placeholders.

Example

{{title}}

{{subtitle}}

{{date}}

{{department}}

{{owner}}

{{author}}

{{kpi_1}}

{{kpi_2}}

{{kpi_3}}

{{kpi_4}}

{{timeline}}

{{issue_table}}

{{action_table}}

{{risk}}

{{photo}}

{{summary}}

---

# Layout Selection Mapping

If content contains

Yield

PPM

OEE

KPI

↓

Dashboard

--------------------------------

Supplier

Input

Output

Customer

↓

SIPOC

--------------------------------

Timeline

Milestone

↓

Timeline

--------------------------------

Action

Owner

Due Date

↓

Action Plan

--------------------------------

Risk

Mitigation

Severity

↓

Risk

--------------------------------

Workflow

Inspection

Production

↓

Process Flow

--------------------------------

Before

After

↓

Before After

--------------------------------

Photo

Image

↓

Gallery

--------------------------------

Achievement

Summary

Next Step

↓

Summary

---

# Global Rules

AI must never

- Create new layouts
- Move logo
- Change fonts
- Change colors
- Change margins
- Change spacing

If content exceeds one slide

↓

Duplicate the same layout.

Never shrink fonts.

Never redesign components.

Always preserve Milwaukee branding.

---

End of Master Template Specification
