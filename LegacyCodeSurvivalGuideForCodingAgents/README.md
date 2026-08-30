# The Legacy Code Survival Guide for Coding Agents

## Abstract

You point a coding agent at your legacy system and it happily rewrites a 400-line method in nine seconds. Do you merge it? Nobody knows what that method actually does. There are no tests. The names lie. You are one confident agent away from a production incident.

Agents are not the problem. The missing safety net is. The practices that made legacy code survivable for humans — characterization tests, approval tests, mutation testing, naming as a process, tiny refactorings over a long horizon — are exactly what make an agent trustworthy in a brownfield codebase. Mutation testing tells you whether your tests would actually catch the agent when it changes behavior. Approval tests pin down code you don't understand yet. Signposts like agent instruction files placed throughout the tree give the agent the context your codebase never wrote down.

I'll show you how to build that harness and then let agents work inside it — including slow loops that refactor continuously in your pipeline nightly and a swarm of agents each refactoring through a single narrow lens.

By the end of this session, you'll be able to

- pin down untested legacy behavior with characterization and approval tests
- use mutation testing to prove your safety net would catch an agent's mistakes
- signpost a brownfield codebase so agents refactor with context instead of guessing

## Talk Resources

* ### Slides
* ### Code
* ### [Agent Skills](https://github.com/SDiamante13/dotfiles/tree/main/claude/skills)
* ### [The Java Legacy Code Survival Guide](../TheJavaLegacyCodeSurvivialGuide/README.md)
* ### [Naming as a Process](https://www.digdeeproots.com/articles/on/naming-process/)
