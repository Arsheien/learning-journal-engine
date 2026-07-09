# Learning Journal Engine - Learning Engine Structure

> Status: Accepted
>
> Version: 1.0
>
> Last Updated: 2026-07-09

---

# Purpose

This document defines the official learning engine structure of the Learning Journal Engine (LJE).

The purpose of this structure is to ensure that every learning module remains consistent, extensible, and independent of any specific subject or software.

This document is considered one of the core architectural documents of the project.

---

# Design Philosophy

Learning Journal Engine is **not a workbook**.

It is **a reusable learning engine** capable of supporting multiple learning domains.

Examples include:

- Character Artist
- Programming
- Japanese
- School Librarian Examination
- UI/UX Design

Every module should follow the same learning architecture.

---

# Core Principles

## Principle 01 — Concept First

Learning progresses through **Concepts**, not time.

A Concept represents one meaningful learning objective.

Examples:

- Line Control
- Basic Forms
- Perspective
- Lighting
- Head Construction

A Concept must be completed before moving to the next Concept.

---

## Principle 02 — Week as an Operating Unit

Weeks manage learning.

Weeks do **not** define learning.

Example

Concept 01

↓

Week 1 (40%)

↓

Week 2 (80%)

↓

Week 3 (100%)

↓

Concept 02

Missing a week never changes the curriculum.

---

## Principle 03 — Daily as an Execution Unit

Every study session follows the same structure.

```
Today's Concept

↓

Learning

↓

Practice

↓

Reflection
```

Daily pages exist to execute Concepts.

They never define Concepts.

---

## Principle 04 — Four-Stage Mastery

Every Concept progresses through four stages.

```
Learn

↓

Practice

↓

Apply

↓

Master
```

### Learn

Understand the concept.

Examples

- Read
- Watch
- Observe

---

### Practice

Repeat intentionally.

Examples

- Exercises
- Sketches
- Primitive modeling

---

### Apply

Use the concept in a real task.

Examples

- Character head
- Prop
- Environment
- Coding project

---

### Master

Demonstrate independent execution.

Requirements may include:

- Consistent quality
- Independent completion
- Confidence
- Readiness for the next Concept

---

## Principle 05 — Curriculum Stability

The curriculum is fixed.

Only the execution environment may change.

Allowed

- Software
- Device
- Study location
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

Anatomy

Not Allowed.

---

## Principle 06 — Separation of Curriculum and Environment

Curriculum defines **what** is learned.

Environment defines **how** it is practiced.

Example

Curriculum

- Primitive Forms

Environment

Tuesday–Saturday

- Nomad Sculpt

Sunday

- Blender

The learning objective remains identical.

---

# Learning Hierarchy

```
Master Plan

↓

Concept

↓

Week

↓

Daily

↓

Week Review

↓

Concept Review

↓

Portfolio

↓

Professional Work
```

Every learning module follows this hierarchy.

---

# Workbook Architecture

Each workbook contains

```
Master Plan

↓

Concept

↓

Week

↓

Daily

↓

Review
```

No workbook should violate this order.

---

# Why This Structure Exists

Traditional learning plans are time-based.

```
Week 1

↓

Week 2

↓

Week 3
```

This approach creates several problems.

- Missing one week delays everything.
- Learning speed varies between individuals.
- Progress is measured by time instead of mastery.
- Long-term consistency is difficult.

Learning Journal Engine instead uses **Concept-based progression**.

```
Concept

↓

Practice

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

Every learning module behaves the same way.

---

## Scalability

New modules can reuse the same engine.

Examples

- Drawing
- Programming
- Language Learning
- Exam Preparation

---

## Flexibility

Different learners progress at different speeds without breaking the curriculum.

---

## Sustainability

Long-term learning remains manageable.

Missing a week affects only progress speed.

It never changes the roadmap.

---

## Software Independence

The engine is independent of software.

Example

```
Blender

↓

Nomad Sculpt
```

The software changes.

The curriculum does not.

---

# Example

Character Artist

```
Master Plan

↓

Concept 01
(Line Control)

↓

Week 01

↓

Daily Pages

↓

Concept Review

↓

Concept 02
(Basic Forms)
```

Programming

```
Master Plan

↓

Concept 01
(Variables)

↓

Week 01

↓

Daily Pages

↓

Concept Review

↓

Concept 02
(Control Flow)
```

Different subjects.

Same engine.

---

# Architectural Goal

Learning Journal Engine should become a reusable learning framework that can support any long-term learning project while maintaining consistent learning quality.

The engine prioritizes mastery, sustainability, and extensibility over speed.

---

# Future Extensions

This architecture is designed to support:

- PDF Workbook
- GoodNotes Planner
- Notion Database
- Web Application
- Mobile Application
- AI-assisted Learning

No future extension should violate the core principles defined in this document.

---

# Status

This document defines the official learning architecture of the Learning Journal Engine.

All future modules, templates, and applications should conform to this specification.
