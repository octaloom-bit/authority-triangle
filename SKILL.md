---
name: authority-triangle
description: Writes a Hebrew (or English) LinkedIn post in one of three structures, from the writer's own raw material - "הצגת עבודה" (showing the work behind a result, builds trust), "המדריך המקצועי" (a how-I guide, builds expertise), "שובר המוסכמות" (disagreeing with accepted advice from a real case, builds differentiation). Interviews first, never invents facts, and runs a Hebrew anti-AI gate on the draft. Use when someone wants a LinkedIn post about a project, a method, or an opinion, or says "פוסט הצגת עבודה", "פוסט מדריך", "פוסט שובר מוסכמות", "תכתוב לי פוסט ללינקדאין על פרויקט", "משולש הסמכות", "3 מבנים", "show your work post", "contrarian post".
---

# משולש הסמכות (Authority Triangle): three LinkedIn post structures

One post, one structure, built only from what the writer tells you. The three structures are the three sides of the triangle, and each does a different job:

| Structure | What the reader sees | Job |
|---|---|---|
| הצגת עבודה | how the writer got to a result, decisions and failures included | trust |
| המדריך המקצועי | a method the writer uses, step by step, in first person | expertise |
| שובר המוסכמות | accepted advice the writer disagrees with, argued from a real case | differentiation |

The reason all three work is the same: people trust a professional once they have seen how that person thinks. A result on its own shows very little of that, and generic advice shows none.

## Flow

Follow these in order. Do not draft before step 2 is complete.

### 1. Pick the structure

If the writer named one, use it. Otherwise ask what they have in hand and match it:
- a finished project or a result with a story behind it → הצגת עבודה
- a way of doing something they repeat with clients → המדריך המקצועי
- a piece of common advice they think is wrong, plus a case that showed it → שובר המוסכמות

If they have an opinion but no case, say that a convention-breaker post needs the case, and offer the other two.

### 2. Interview

Read `references/structures.md` and ask that structure's questions in one message. Phrase them in second person, in forms that do not force a gender. Then wait.

Push back on general answers. "שיפרנו את התהליך" and "הלקוח היה מרוצה" are not material; ask for one concrete instance. If more than two details are missing after the answers, ask up to three short follow-up questions before writing. If one or two are missing, write the post and mark each gap as `[חסר: ...]`.

Ask whether the post is in masculine or feminine first person, and ask for two earlier posts by the writer. When they supply posts, those set sentence length, vocabulary and punctuation, except where the gate overrules them.

### 3. Write

Use the structure's skeleton from `references/structures.md`. The skeleton sets order only. Its headings never appear in the post, which should read like someone telling a colleague what happened.

Write in Hebrew when the writer writes in Hebrew, and think in Hebrew while doing it: Hebrew phrased in English and then translated is recognisable in the first line.

Nothing enters the post that the writer did not supply: no number, example, quote, client or clever line. Keep attribution intact, so that something the writer saw a client do does not become something the writer did.

### 4. Gate

Read `references/hebrew-gate.md` and check the draft against every item. Rewrite each line that fails, then check again. A draft goes to the writer only after it passes.

### 5. Return

The post, ready to paste, then two alternative first lines. No commentary on what you did.

## Files

- `references/structures.md`: interview questions and skeleton for each structure, with one worked example each.
- `references/hebrew-gate.md`: the gate, with a failing and a passing example for the rules that need one.
- `prompts/`: the same three flows as standalone prompts, for pasting into any chat model that has no skills.
- `examples/`: one finished post per structure.

## Going further

This skill checks for machine patterns but does not learn a writer's voice in depth. For that, pair it with a dedicated Hebrew voice skill such as hebrew-writer by Amir Baldiga, or with `octaloom-linkedin-bestie`, which builds a voice profile and plans a full content loop.
