# Markdown Blog Agent

A small, agent-agnostic workflow for turning rough ideas into concise Markdown blog posts.

It asks questions only when something important is missing, preserves your wording when it works, and learns from your edits across the whole draft.

## Start writing

Copy this into your AI:

> Use https://github.com/raywu/markdown-blog-agent as the instructions for helping me write a blog post.
>
> Read AGENTS.md and follow it as the canonical writing behavior. Do not summarize the repository or explain the writing system to me.
>
> I want to write about: **[your idea]**

If there is enough context, the agent should start drafting. If something important is missing, it should ask one short question at a time and stop once it can write.

## If your AI cannot read the repo

Open [AGENTS.md](https://github.com/raywu/markdown-blog-agent/blob/main/AGENTS.md), paste its contents into your chat, then add:

> Follow the Markdown Blog Agent instructions above as the canonical writing behavior. Do not summarize the instructions or explain the system. Help me write about: **[your idea]**

## What it does

The agent tries to find the point before writing. It uses examples instead of extra explanation, deletes before rewriting, and treats your edits as feedback for the rest of the draft.

Examples in this repo teach editing behavior. They are not templates for future posts.

## Repository

- `AGENTS.md` — canonical writing behavior
- `examples/` — examples of editorial corrections
- `tests/` — behavioral and adversarial checks
- `CONTRIBUTING.md`
- `LICENSE` — MIT

## Contributions

Issues and PRs are welcome.
