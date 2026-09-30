# Danny Sheehan

I like to use coding agents to build small tools. Most of them start because I run into something I don't understand, something that annoys me, or something I wish worked differently.

My background is in customer-facing software work. I learn best by doing, and that has turned into building things I actually use.

## In use and still changing

**[invader](https://github.com/dan-sheehan/invader)** &rightarrow;
My daily workspace for building with AI coding tools: my real files, a map of how they connect, and a terminal running Claude Code or Codex, all in one window. It grew out of cockpit and alabs.

**[cockpit](https://github.com/dan-sheehan/cockpit)** &rightarrow;
When I started using Codex alongside Claude Code, I wanted one view of both: how they're set up, what they're doing, and a way to have Claude write a change while Codex reviews it.

**[stray](https://github.com/dan-sheehan/stray)** &rightarrow;
I wanted a Productboard for one person. A hotkey saves a thought to one Markdown file so I can come back to it later. Keeping it as small as possible is where my agent rules file started.

## Done

**[coding-inspector](https://github.com/dan-sheehan/coding-inspector)** &rightarrow;
I didn't understand what the hidden .claude files were doing, so I built a read-only viewer for Claude Code and Codex configuration, instructions, hooks, and environment state.

**[defiance](https://github.com/dan-sheehan/defiance)** &rightarrow;
Answers questions about the 2017 San Diego State baseball season. I played on that team, and it's named after the street one of our baseball houses was on. Every answer links to an archived source, and when it can't answer, it says so instead of guessing.

**[gtm-first-touch](https://github.com/dan-sheehan/gtm-first-touch)** &rightarrow;
A prompt pack that takes one target account from fit scoring to a first-touch email and discovery prep. It started as a Flask and SQLite app. I went back to a simpler, portable version on purpose.

## How I work with agents

I changed how I work after realizing that autonomous output could look finished without being well understood.

* I write the scope down first, including what the project won't do.
* Each repo has one rules file for agents. Claude Code reads CLAUDE.md and other agents read AGENTS.md, so both point to the same file.
* Agents can suggest. I decide. The decisions get written down.
* I write the core product and decision docs myself.

## If you only read three files

* **[invader/decisions.md](https://github.com/dan-sheehan/invader/blob/main/decisions.md)** &rightarrow; what invader is for, what must stay true, and the decisions behind it.
* **[cockpit/docs/why-harness.md](https://github.com/dan-sheehan/cockpit/blob/main/docs/why-harness.md)** &rightarrow; why I separate product documentation, plumbing, agent rules, and entry points. **(currently evolving again :cyclone:)**
* **[stray/v1.md](https://github.com/dan-sheehan/stray/blob/main/v1.md)** &rightarrow; what a small tool does, won't do, and when it's done.


## About the history

I built most of these for myself, not planning to publish them. When I did publish, I started each repo from a fresh commit because the private history contains data from my own machine.
