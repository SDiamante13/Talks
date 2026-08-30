# Forcing AI Agents to Write Quality Code

## Abstract

Coding agents write more code in an afternoon than a team can read in a week. Code review doesn't scale to that volume, and it arrives too late to change what the agent does next. So we write rules files and ask for clean code, and the agent hands back something we'd be embarrassed to ship. By the time we've argued it into shape, we're worn out and wondering why we didn't write the thing ourselves.

AI-generated code fails in three ways: it breaks the rules, it breaks behaviors, or it rots the design over time. I'll walk through three automated quality sensors that feed the agent that information while it still has the file open:

- Structural Sensor: strict linting rules, paired with guides that tell the agent why a rule exists and how to satisfy it
- Behavioral Sensor: mutation testing. Coverage is a number the agent can game, and a surviving mutant names a test that passes without protecting anything
- Design Sensor: frozen architectural boundaries, automated documentation updates, and computed design rules that catch coupling as it creeps in between prompts

Put a sensor in a hook the agent has to run and it changes what the agent writes. Put it in a rules file and the agent skims past it. I'll show you which checks belong on every edit, which ones to save for the commit, and what an agent does when it can't pass a check and decides to delete the check instead.

Examples are in TypeScript. The concepts and the libraries port to any stack.

By the end of this session, you'll be able to:

- identify which of the three failure modes your codebase is blind to
- execute an automated system of triggers that guide your agent to write maintainable software
- pick the one check worth adding to your repo first, and wire it where the agent can't ignore it

## Submissions

* CodeMash 2027 — 1 hour general session

## Talk Resources

* ### [Code](https://github.com/SDiamante13/katacombs-kata-ts)
