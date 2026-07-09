# Learning Journal Engine Workbook Standard

> Status: Accepted  
> Version: 2.0  
> Last Updated: 2026-07-09

---

# Purpose

This document defines the official workbook architecture and learning workflow of the Learning Journal Engine (LJE).

Every learning module in this repository must follow this specification.

The purpose of this standard is to ensure that every workbook remains:

- Consistent
- Scalable
- Reusable
- Software-independent
- Suitable for long-term learning

---

# Design Philosophy

Learning Journal Engine is **not** a collection of study notes.

It is a reusable learning framework designed to support long-term mastery across multiple domains.

Examples include:

- Character Artist
- Programming
- JavaScript
- React
- Japanese
- School Librarian Examination
- UI / UX Design

Every module follows the same engine.

Only the curriculum changes.

---

# Official Learning Hierarchy

Every learning module must follow this hierarchy.

```
Module
    ↓
Master Plan
    ↓
Concept Book
    ↓
Week Workbook
    ↓
Daily Pages
    ↓
Week Review
    ↓
Concept Review
```

This hierarchy is mandatory.

---

# Module

A Module represents one complete learning domain.

Examples

- Character Artist
- Programming
- Japanese
- School Librarian Examination

Each Module owns its own:

- Master Plan
- Concepts
- Workbooks
- Journals

---

# Master Plan

Purpose

The Master Plan defines the long-term roadmap.

It answers:

- Why am I learning this?
- What is the final goal?
- What Concepts exist?
- In what order are they learned?

Each Module contains exactly one Master Plan.

---

# Concept Book

Purpose

The Concept Book explains one learning concept.

Concepts never depend on weeks or dates.

Each Concept contains:

- Cover
- Purpose
- Learning Objectives
- Why This Concept Exists
- Prerequisites
- Theory
- Learn
- Practice
- Apply
- Master
- Common Mistakes
- Reference Guide
- Self Check
- Concept Review

A Concept is considered complete only after reaching the Master stage.

---

# Week Workbook

Purpose

A Week Workbook manages learning execution.

Weeks never define learning.

They only manage progress.

Example

Concept 01

↓

Week 1

40%

↓

Week 2

80%

↓

Week 3

100%

↓

Concept 02

Missing a week never changes the curriculum.

---

# Daily Page

Purpose

Daily Pages execute the current Concept.

Every Daily Page follows the same structure.

```
Today's Concept

↓

Drawing / Practice

↓

3D / Implementation

↓

Reflection
```

Each Daily Page contains:

- Today's Goal
- Practice
- Reference Study
- Journal
- Difficulty
- Achievement
- Tomorrow's Focus

---

# Week Review

Purpose

Review one week's execution.

Contents

- Progress
- Strengths
- Weaknesses
- Problems
- Solutions
- Next Week Plan

---

# Concept Review

Purpose

Determine whether the learner is ready to move to the next Concept.

Every Concept is evaluated using the same criteria.

---

# Official Mastery System

Every Concept must follow these four stages.

```
Learn

↓

Practice

↓

Apply

↓

Master
```

---

## Learn

Understand the concept.

Examples

- Reading
- Observation
- Video lesson

---

## Practice

Repeat intentionally.

Examples

- Sketches
- Exercises
- Primitive Modeling

---

## Apply

Use the concept in a real project.

Examples

- Character Head
- Environment
- Coding Project
- Language Conversation

---

## Master

Demonstrate independent execution.

Requirements

- Consistent quality
- Independent completion
- Confidence
- Ready for the next Concept

---

# Curriculum Stability Rule

The curriculum never changes.

Only the execution environment may change.

Allowed

- Software
- Device
- Workspace
- Journal format

Not Allowed

- Reordering Concepts
- Skipping Concepts
- Changing learning objectives

Example

Blender

↓

Nomad Sculpt

Allowed.

Perspective

↓

Head

↓

Anatomy

Not Allowed.

---

# Separation of Curriculum and Environment

Curriculum answers:

"What should be learned?"

Environment answers:

"How should it be practiced?"

Example

Curriculum

Basic Forms

Execution Environment

Tuesday–Saturday

Nomad Sculpt

Sunday

Blender

The learning objective remains identical.

---

# Character Artist Module Standard

Tuesday–Saturday

- Clip Studio Paint (iPad)
- Nomad Sculpt
- Journal

Sunday

- Clip Studio Paint (Desktop)
- Blender
- Learning Journal Engine

---

# Why This Architecture Exists

Traditional learning systems are time-based.

```
Week 1

↓

Week 2

↓

Week 3
```

Problems

- Missing one week delays everything.
- Progress is measured by time.
- Learning quality varies.
- Long-term consistency is difficult.

Learning Journal Engine instead measures progress by mastery.

```
Concept

↓

Learn

↓

Practice

↓

Apply

↓

Master

↓

Next Concept
```

Time becomes flexible.

Learning quality remains consistent.

---

# Benefits

## Consistency

Every Module behaves identically.

---

## Scalability

New Modules require only new Concepts.

The engine remains unchanged.

---

## Sustainability

Learners progress at their own speed.

Missing a week only changes progress speed.

It never changes the roadmap.

---

## Software Independence

The learning engine is independent of tools.

Only the execution environment changes.

---

## Cross-Platform Compatibility

This architecture is designed to support

- Markdown
- PDF
- GoodNotes
- Notion
- Web Application
- Mobile Application

without changing the learning structure.

---

# Official Principle

Learning Journal Engine is

**a Concept-based mastery engine, not a time-based study planner.**

The engine prioritizes

- Mastery
- Consistency
- Sustainability
- Extensibility

over learning speed.

---

# Compliance

All future Modules, Templates, Workbooks and Applications must conform to this specification.

No future feature should violate the architecture defined in this document.
