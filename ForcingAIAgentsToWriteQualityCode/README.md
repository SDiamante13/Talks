# Forcing AI Agents to Write Quality Code

## Abstract

Coding agents write more code in an afternoon than a team can read in a week. The old safety net of code review doesn't scale to that volume, and it arrives too late to change what the agent does next. We write rules files and ask the agent to write clean code, but it's still not good enough. And even when we finally brute force it into writing the kind of code we'd be proud to ship, we're exhausted and have a feeling we could have just written the code ourselves.

AI-generated code fails in three ways: it breaks the rules, it breaks behavior, or it quietly rots the design. I'll walk through three automated quality sensors that give the agent real-time feedback while it's working: 

- Structural
- Behavioral
- Design 

Linting rules, test coverage, and telling the agent to write clean code isn't enough anymore. We need an automated system that can force an agent to have good coding habits.

Examples are TypeScript, but the concepts and libraries used are transferrable to any tech stack.

By the end of this session, you'll be able to:

- identify which of the three failure modes your codebase is currently blind to
- execute an automated system of triggers that guide your agent to write maintainable software
- pick the one check worth adding to your repo first, and wire it where the agent can't ignore it

## Submissions

* CodeMash 2027 — 1 hour general session

## Talk Resources

* ### [Code](https://github.com/SDiamante13/katacombs-kata-ts)
