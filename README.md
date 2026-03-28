# Your Knowledge Hub

This repo stores knowledge captured by [Mnemos](https://github.com/Soph20/mnemos-capture).

## How it works

1. You paste a resource into Mnemos (article, thread, notes, transcript)
2. Claude extracts insights and commits them to `inbox/`
3. When you're ready, process the inbox in Claude Code to route captures to the right context

## Structure

```
inbox/        ← Unprocessed captures (auto-populated by Mnemos)
career/       ← Career-related insights
work/         ← Work-related insights
founder/      ← Founder-related insights
INDEX.md      ← Master index (auto-maintained)
```

## Get started

1. Deploy [Mnemos](https://github.com/Soph20/mnemos-capture) and point `GITHUB_REPO` to this repo
2. Paste anything into Mnemos — captures appear here automatically
3. In Claude Code, say `process inbox` to route insights to your workflow
