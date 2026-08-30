# Letting Coding Agents Loose on Legacy Code (Responsibly)

## Abstract

A coding agent will rewrite a 400-line method in nine seconds and tell you behavior is preserved. It doesn't know that. Neither do you: there are no tests, the method name stopped being true years ago, and the person who wrote it left in 2019. So you don't merge it. You keep agents away from the parts of your codebase that need the most help.

The safety net that made legacy code survivable before agents is the one that makes agents useful now. Characterization and approval tests pin down what the code does today, bugs included. Mutation testing proves the safety net works. Once your tests do that, an agent's mistakes get caught the same way yours do. Agent instruction files placed throughout your complex codebase carry the tribal knowledge that never made it into the repo, so the agent has the context it needs to make the change confidently.

I'll show you how to build that safety net and orchestrate refactoring agents to improve the design before you add the next feature. The agent skills I use for characterization testing and swarm refactoring are open source so you can point them at your own codebase after the session's over. The examples are in Java, but the principles and libraries are portable to any tech stack.

By the end of this session, you'll be able to

- pin down untested legacy behavior with characterization tests before an agent touches it
- use mutation testing to prove your tests would catch an agent that changed behavior
- run a refactoring swarm against your own brownfield code

## Talk Resources

* ### Slides
* ### Code
* ### [Agent Skills](https://github.com/SDiamante13/dotfiles/tree/main/claude/skills)
* ### [The Java Legacy Code Survival Guide](../TheJavaLegacyCodeSurvivialGuide/README.md)
* ### [Naming as a Process](https://www.digdeeproots.com/articles/on/naming-process/)
