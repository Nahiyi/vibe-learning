# vibe-learning.skill

An AI-powered programming mentor skill designed to help developers build real technical expertise while using AI-assisted coding (vibe coding) as a learning tool, not a crutch.

## What is this?

This is a Claude Code skill that transforms how you learn programming with AI. Instead of letting AI write code for you while you copy-paste, this skill makes you the driver -- AI becomes your mentor who guides you through understanding, not just completion.

## Core Teaching Approach

**Control Variable Method** -- When you write code that doesn't work, or when you see AI-generated "best practice" code, this skill breaks down the differences one variable at a time, explains the underlying mechanism, and helps you truly understand why the change matters.

**Cognitive Load Management** -- Not every topic deserves the same depth. This skill classifies knowledge into:
- **Principles** -- core concepts worth deeply understanding (e.g. lifecycle, state isolation, concurrency safety)
- **Memorization** -- configuration details and API spellings that you can safely delegate to AI

**Socratic Guidance** -- Uses leading questions rather than direct answers. Instead of "you should use useState", it asks "why do you think the UI didn't update?"

**No Code Machine** -- Will never give you a complete runnable block of code upfront. Always requires your pseudo-code or thoughts first, then builds on your foundation.

## When to Use

Activate this skill when you want to:
- Learn a new technology or framework deeply
- Debug your own code and understand why it breaks
- Understand AI-generated code rather than blindly copying it
- Build projects while actually mastering the techniques involved

## Installation

Take the `vibe-learning` folder (the one containing `SKILL.md`) from the repo and place it into your Claude Code skills directory:

```
~/.claude/skills/vibe-learning/
```

Then load it in your conversation with `/vibe-learning`.

## Skill Structure

```
vibe-learning/
└── SKILL.md       -- The skill definition (required)
```

## Key Principles

1. **Teach to Fish** -- Give a man a fish and you feed him for a day; teach him to fish and you feed him for a lifetime
2. **Learn by Doing** -- You write code, AI guides your understanding
3. **Know When to Dig Deep** -- Principles deserve depth; configs deserve acceptance
4. **Test Before Claiming Mastery** -- Optional micro-tests verify real understanding

## For Whom

Developers with computer science fundamentals who want to level up through real understanding, not just AI-assisted copy-pasting. Works across the full stack: JavaScript, Vue3, React, Java, Spring, Go, and more.
