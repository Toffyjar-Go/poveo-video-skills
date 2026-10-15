# Poveo video skills

A free skill and prompt pack for planning a short video: a Reel, an ad, an explainer or a product demo. Use it with Claude (as a skill) or paste the prompts into any AI assistant.

It takes you from an idea to a plan you can hand to anyone who makes the video:

1. **Brief**: who it is for, the one thing they should remember, and what they should do next.
2. **Hook**: three openings for the first two seconds, and why each works.
3. **Script in scenes**: the words to say and the words on screen, timed to the length you picked.
4. **Shot list**: what the viewer sees in each scene.
5. **Brand voice**: how your brand sounds, and the words it never uses.
6. **Checklist**: the things to check before you make it.

Made by the team behind [Poveo](https://poveo.app), which turns a plan like this into a finished, on-brand video. You do not need Poveo to use this pack.

## Use it with Claude

Copy `skills/video-planner` into your skills folder (for Claude Code, `~/.claude/skills/`; in the Claude app, upload it as a skill). Then ask, for example:

> Plan a 30-second Reel for our new oat-milk latte. We are a small café in Pune; our customers are students and people working nearby.

The skill asks what it is missing, then works through the six steps and gives you one plan.

## Use the prompts anywhere

Each file in `prompts/` is one step you can paste into any assistant, in order. Fill in the parts in square brackets.

| Prompt | What you get |
|---|---|
| [`prompts/1-brief.md`](prompts/1-brief.md) | A one-page brief |
| [`prompts/2-hooks.md`](prompts/2-hooks.md) | Three hooks to pick from |
| [`prompts/3-script.md`](prompts/3-script.md) | The script in scenes, timed |
| [`prompts/4-shot-list.md`](prompts/4-shot-list.md) | What each scene shows |
| [`prompts/5-brand-voice.md`](prompts/5-brand-voice.md) | A short brand voice guide |
| [`prompts/6-checklist.md`](prompts/6-checklist.md) | A review before you make it |

## Examples

- [A 30-second Reel for a café](examples/reel-30s-cafe.md)
- [A 60-second explainer for a billing app](examples/explainer-60s-app.md)

Both are made-up businesses.

## How long is your script?

Natural voiceover runs at about 2 to 2.5 words a second. Leave room for the opening and the logo at the end.

| Video length | Spoken words |
|---|---|
| 15 seconds | 30–38 |
| 30 seconds | 60–75 |
| 45 seconds | 90–112 |
| 60 seconds | 120–150 |
| 90 seconds | 180–225 |
| 120 seconds | 240–300 |

## Make the video

When the plan is ready, you can make the video in [Poveo](https://studio.poveo.app/start): paste the idea, approve the script, voice and storyboard, and render it in your brand. The first 15 seconds are free.

## Licence

MIT. Use it, change it, share it. See [LICENSE](LICENSE).
