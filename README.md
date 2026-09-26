# Danny Sheehan

I like to use coding agents to build small tools. My background is in customer-facing work, first as a BDR, then as a CSM, and then as a Founding CSM. I learn best by doing, and that has turned into building things I actually use.

What I'm good at is deciding what a tool should and shouldn't do, documenting that behavior, and then holding the agents to it, even while I'm still learning the engineering underneath.

## How I work with agents

For a while, I started letting AI do way too much. Newer models could take a short prompt, run autonomously, and finish, and I accepted that output without reviewing it in depth. The work was done, but it wasn't that good.

That ultimately changed how I work.

- I write the scope down first, including what the project won't do.
- Each repo has one rules file for agents. Claude Code reads `CLAUDE.md` and other agents read `AGENTS.md`, so both point to the same file.
- Agents can suggest. I decide. The decisions get written down.
- I write the docs myself. Every doc in stray, plus the documentation rewrites for cockpit and invader.

## If you only read three files

- [stray/v1.md](https://github.com/dan-sheehan/stray/blob/main/v1.md): what a small tool does, won't do, and when it's done.
- [stray/harness.md](https://github.com/dan-sheehan/stray/blob/main/harness.md): the rules agents follow when they work on it.
- [invader/decisions.md](https://github.com/dan-sheehan/invader/blob/main/decisions.md): what I decided for my main project and why, including what earlier projects taught me.

## In use and still changing

**[invader](https://github.com/dan-sheehan/invader)**
My daily workspace for building with AI coding tools: my real files, a map of how they connect, and a terminal running Claude Code or Codex, all in one window. It grew out of cockpit and alabs.

**[cockpit](https://github.com/dan-sheehan/cockpit)**
When I started using Codex alongside Claude Code, I wanted one view of both: how they're set up, what they're doing, and a way to have Claude write a change while Codex reviews it. I'm proudest of this one because I didn't know I could build it.

**[stray](https://github.com/dan-sheehan/stray)**
I wanted a Productboard for one person. A hotkey saves a thought to one Markdown file so I can come back to it later. Keeping it as small as possible is where my agent rules file started.

## Done

**[coding-inspector](https://github.com/dan-sheehan/coding-inspector)**
Where my agent tools started. I didn't understand what the hidden `.claude` files were doing, so I built a read-only viewer for them. It came before stray, so it doesn't use the rules file setup.

**[defiance](https://github.com/dan-sheehan/defiance)**
Answers questions about the 2017 San Diego State baseball season. I played on that team, and it's named after the street one of our baseball houses was on. Every answer links to an archived source, and when it can't answer, it says so instead of guessing.

**[gtm-first-touch](https://github.com/dan-sheehan/gtm-first-touch)**
A prompt pack that takes one target account from fit scoring to a first-touch email and discovery prep. It started as a Flask and SQLite app. I went back to a simpler, portable version on purpose.

## About the history

I built most of these for myself, not planning to publish them. When I did publish, I started each repo from a fresh commit because the private history contains data from my own machine.

## What I'm looking for

I'm looking for customer-facing work where this way of thinking is useful: understanding how a system works, explaining it clearly, documenting what matters, and figuring out where AI actually helps.
