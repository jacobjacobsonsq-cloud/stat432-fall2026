---
id: w03-jacobjacobsonsq-cloud-skill-validator-dependency
title: "When a Skill Validator Lacks a Dependency"
author: "Jacob Jacobson (jacobjacobsonsq-cloud)"
---

I asked my agent to “create, install, and test an `explain-to-me` skill for Homework 3.” It created a short `SKILL.md`, but the official validation command stopped with `ModuleNotFoundError: No module named 'yaml'` before inspecting the skill. The traceback showed that the failure occurred on the validator's import, not while parsing my file. I therefore checked the required frontmatter fields, folder/name agreement, and absence of scaffold placeholders manually, then installed the skill and tested its explanation-only behavior on Question 2. Should an agent install the missing validator dependency, use a separate environment, or treat manual structural checks as sufficient when the dependency belongs to the validation tool rather than the submitted skill?
