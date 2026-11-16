# Authority Triangle (משולש הסמכות)

🇮🇱 [עברית](README.he.md)

**A Claude skill that writes a LinkedIn post in one of three structures, using only the material you give it.**

Works in Hebrew and English. No API keys, and nothing to install beyond copying a folder.

Built by [OctaLoom](https://octaloom.com). Free to use and adapt.

---

## The three sides

| Structure | What the reader sees | What it builds |
|---|---|---|
| **Showing the work** (הצגת עבודה) | how you got to a result, including the decisions and what went wrong | trust |
| **The professional guide** (המדריך המקצועי) | a method you use, step by step, in first person | expertise |
| **The convention-breaker** (שובר המוסכמות) | accepted advice you disagree with, argued from a case in your own work | differentiation |

All three rest on one idea: people trust a professional once they have seen how that person thinks. A result on its own shows little of that, and generic advice is a search away.

## How it works

1. **It asks before it writes.** Six questions that pull out the material: what happened, with which number, what went wrong. A general answer such as "the client was happy" gets a request for one concrete instance.
2. **It writes only from what it received.** A number, client or quote you did not supply will not appear. A missing detail is marked `[חסר: ...]`.
3. **It runs a gate on the draft.** Fifteen checks for the patterns that make Hebrew read machine-written: runs of short sentences, filler triads, "it's not X, it's Y", faceless crowds, a closing line fit for a poster. A line that fails is rewritten.
4. **It returns the post and two alternative first lines.**

One finished post per structure is in `examples/`.

## Install

**Claude Code**

```bash
git clone https://github.com/octaloom-bit/authority-triangle.git ~/.claude/skills/authority-triangle
```

Then, in a new conversation: "write me a showing-the-work post about my last project".

**Claude in the browser or app**

Download the repo as a ZIP (green Code button, then Download ZIP) and upload it under Settings, Capabilities, Skills.

**ChatGPT, Gemini or any other chat**

Nothing to install. `prompts/` holds three standalone prompts, one per structure. Copy a file's contents and paste them at the start of a new chat. The prompts are written in Hebrew.

## What is in the folder

```
SKILL.md                     the flow: pick a structure, interview, write, gate
references/structures.md     interview questions and skeleton per structure
references/hebrew-gate.md    the gate, with examples
prompts/                     the three standalone prompts
examples/                    one finished post per structure
```

## What it does not do

It checks for machine-writing patterns; it does not learn your voice in depth. For that, pair it with hebrew-writer by Amir Baldiga, or with [linkedin-bestie](https://github.com/octaloom-bit/linkedin-bestie), which builds a voice profile and plans a full content loop.

## License

MIT. See `LICENSE`.
