# product-sense

A Claude Code skill that acts as a product sense coach. Describe a real product challenge, answer a few short questions, and get direct guidance from the world's best PMs — specific frameworks, verbatim quotes, conflicting perspectives, and concrete next steps.

Powered by 303 transcripts from [Lenny's Podcast](https://www.lennysnewsletter.com/podcast) — interviews with PMs from Stripe, Airbnb, Figma, Calendly, Confluent, and more.

## Install

```bash
npx skills add code-hugo/product-sense
```

## Usage

```
/product-sense
/product-sense I need to decide between retention and acquisition investment
```

Run it when you are stuck on a decision, working through a blocker, or want to pressure-test your thinking before committing to a direction.

The skill runs a short adaptive wizard (up to 4 questions) to understand your challenge, then searches the transcript archive for what the best PMs have actually said about your situation. It surfaces frameworks, direct quotes, and where smart people disagree — then applies all of it to your specific context.

## What you get

- **The situation** — your challenge restated with your exact context
- **What the best PMs say** — 3-5 insights with verbatim quotes and timestamps
- **Where they disagree** — genuine tension in the archive, attributed and explained
- **What this means for your situation** — concrete synthesis, not a summary
- **Three things to do next** — specific, ordered, actionable
- **One question to sit with** — the kind a great PM mentor leaves you with

## Requirements

No external dependencies. The skill uses the transcript archive hosted at [ChatPRD/lennys-podcast-transcripts](https://github.com/ChatPRD/lennys-podcast-transcripts), which it pulls automatically on each invocation.

## Version

`1.1.0`

## Credits

Built by [Hugo Hodinka](https://github.com/Code-Hugo).
