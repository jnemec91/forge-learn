# Levels

Your AI journey in seven steps. Each level introduces new capabilities. Type `/Progress` to see where you are and what to try next.

All skills work at every level — the levels guide your learning, not restrict your access.

---

## Level 1: Discover — Run a skill, read its source, change one line

Every skill is a text file. Run one, then open the file and see how it works.

**Skills**: /Explain

- [ ] Ran /Explain on any file in the project
- [ ] Opened `skills/Explain/SKILL.md` and read the instructions
- [ ] Changed one line (e.g., the explanation style), re-ran, and saw the behavior change

---

## Level 2: Personalize — Edit identity files, run Tour

Edit your identity files so the AI adapts to you.

**Skills**: /Tour, /Explain

- [ ] Edited steering/Identity.md with your real name and preferences
- [ ] Edited steering/Goals.md with your actual goals
- [ ] Ran /Tour and received a personalized greeting

---

## Level 3: Navigate — Work with files and save your progress

Use the AI to understand files and save your work with git.

**Skills**: /GitHelp

> **Privacy tip**: Your `steering/` files contain personal info (name, goals). If you push to a public repository, this becomes visible. Consider keeping your fork private or reviewing these files before pushing.

- [ ] Used /Explain on a file in your project
- [ ] Made your first git commit (try: /GitHelp save my progress)
- [ ] Used /GitHelp to check what changed or review your history

---

## Level 4: Build — Create something from an idea

Go from "I want to build X" to a working project.

**Skills**: /Kickstart, /FixIt

- [ ] Used /Kickstart to plan a project from an idea
- [ ] Built at least one working project with files you created
- [ ] Used /FixIt to recover from a problem

---

## Level 5: Author — Write custom rules, skills, and agents

You already edited Identity.md to change how the AI talks to you. Now write custom rules, skills, and tune agents.

A skill tells the AI what to do. An agent tells the AI who to be — a character it stays in for the whole conversation. Look at `agents/CodeHelper.md` to see how one works.

**Skills**: /Progress (to track your journey)

- [ ] Created a custom rule file in steering/ (e.g., `steering/MyRules.md` with "always use British spelling")
- [ ] Edited the starter agent in `agents/` (change its persona, or create a new one for something you need)
- [ ] Created your own skill in skills/ (a SKILL.md file — look at existing skills for the pattern)

---

## Level 6: Connect — Expand with modules

Install optional forge modules to give your AI new capabilities.

- [ ] Installed forge-text: `git clone https://github.com/N4M3Z/forge-text.git modules/forge-text`
- [ ] Ran `make install` in forge-text and used a skill from it
- [ ] Installed a second module (try forge-council, forge-avatar, or forge-steering)

---

## Level 7: Forge — Enhance the ecosystem

Everything you've learned comes together. Improve a module that others use.

- [ ] Read an existing module's source code and understood its skills
- [ ] Identified an improvement — better wording, a missing edge case, a new skill idea
- [ ] Shared your enhancement with the module author (PR, issue, or direct message)
