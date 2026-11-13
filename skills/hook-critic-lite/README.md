# Hook critic lite

Checks a reel hook, a reel script or a caption before it goes out, and gives PASS or REVISE with the one main reason, judged against your own business file.

## When to use this skill

- Before you film a reel, to check the first line will make your audience stay.
- Before you post a caption, to catch a promise you cannot stand behind (earnings, results by a date).
- When you have several hook ideas and want to know which ones are ready.

## What this skill does

1. **Reads your business file**: `business-context.md` (audience, offers and prices, voice, rules, no-go topics, call to action). If it is missing, it asks for it.
2. **Judges each piece** on hook, retention, clarity with sound off, call to action and accuracy.
3. **Gives a verdict**: PASS only if every part is strong; otherwise REVISE, with the main reason in plain words.

It never rewrites your piece and never posts, sends or deletes anything.

## How to use

Add `SKILL.md` to Claude as a skill (or install the free plugin from the link below), save your `business-context.md` in your Project's context or working folder, then ask:

```
Check this hook: "Paint a loose rose in five minutes, even if you haven't picked up a brush since school."
```

You can paste several hooks, a full script or a caption in one message.

## Example

From a test run on a made-up watercolour class business:

**User**: check these: "Granulation versus blooms but make it wet-on-damp energy." and "Paint a loose rose in five minutes, even if you haven't picked up a brush since school."

**Output**:
```
### Piece 1: Hook: "Granulation versus blooms but make it wet-on-damp energy."
VERDICT: REVISE
WHY: Your audience is returning beginners who want a calm hobby back, and "granulation", "blooms" and "wet-on-damp energy" are jargon they would have to decode. It names a topic rather than something they want to be able to do.

### Piece 2: Hook: "Paint a loose rose in five minutes, even if you haven't picked up a brush since school."
VERDICT: PASS
WHY: It speaks straight to women who painted as kids and want to come back, and it promises a clear, doable payoff that leads naturally into "comment PAPER" for the supplies list. The five minutes describes the painting, not a promised result, so it stays within your rules.
```

## Tips

- The more your business file says about who your audience is, the sharper the verdict.
- A caption whose first line is your call to action is fine: the hook is judged on the next line.
- Promises of money, results by a date or sure-fire outcomes always get REVISE.

## Free version and full version

- Free download with Caption writer and a 1-page setup guide (business file template included): https://hookandhello.gumroad.com/l/phjcip
- The full Hook critic, with word-for-word fixes and the five scores, comes in Hook and Hello (10 skills, $29): https://hookandhello.gumroad.com/l/bmjjrb

Not affiliated with or endorsed by Anthropic.
