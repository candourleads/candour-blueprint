# Installing Your Blueprint

Your Blueprint only works if it's present in every conversation. Pick your platform below. Each install takes about five minutes. If you use more than one AI, install it on all of them — that's the point.

One rule before anything: **the full Blueprint goes only on accounts you control.** For work or shared accounts, use the trimmed shared-account version the synthesis offered you.

---

## ChatGPT

**Best: a Project.**
1. Create a Project — call it your name plus "OS" (e.g. "Sam OS").
2. Upload your Blueprint as a project file.
3. In the project instructions, paste:
   > Before responding to anything substantive, consult my Blueprint file — it is the source of truth for who I am, how I sound, and how to work with me. Apply its Operating Protocol in every exchange and its voice rules to anything written as me. Its Boundaries section is non-negotiable.
4. Do your real work inside this Project.

**Also: Custom Instructions** (applies to every chat, even outside the Project). Settings → Personalisation → Custom Instructions. In "What should ChatGPT know about you", paste a condensed cut of Sections 1–2. In "How should ChatGPT respond", paste your Operating Protocol (Section 5) and the core voice rules. If you hit the character limit, keep the protocol and cut the biography — the protocol is what changes behaviour.

## Claude

**Best: a Project.**
1. Create a Project, add your Blueprint to the project knowledge.
2. Paste the same project instruction as above into the Project's custom instructions.

**Also: personal preferences.** Settings → Profile → preferences. Paste your Operating Protocol and voice rules — this applies across all chats.

**Claude Code / desktop:** put a pointer in `~/.claude/CLAUDE.md`:
```
My Blueprint lives at [path to your Blueprint file]. Read it at the start of
any substantive task and apply its Operating Protocol and voice rules.
```

## Gemini

1. Create a Gem — name it your name plus "OS".
2. Paste the entire Blueprint into the Gem's instructions. It fits.
3. Use the Gem for your real work. For everyday chats outside the Gem, add your Operating Protocol to Gemini's saved info (Settings → Saved info).

## Microsoft Copilot, or any AI without memory

Keep your Blueprint somewhere one keystroke away. Start sessions with:

> The document below is my persistent context. Ingest it fully before responding. Apply its Operating Protocol to how you engage with me, its voice rules to anything you write as me, and its Boundaries without exception. Confirm in one sentence, then ask what we're working on.

Then paste the Blueprint.

## If you build with APIs

Use the Blueprint verbatim as the system prompt. It was written to work that way.

---

## The one-week test

A few days after installing, check three things:

1. **Did it challenge you yet?** If your AI hasn't pushed back on anything in a week, the protocol isn't landing — reinstall, or strengthen Section 5's challenge instruction.
2. **Does the writing sound like you?** Ask it to draft something real, then read it aloud. If it drifts generic, your Section 3 needs more banned words or another verbatim sample.
3. **Did it catch you circling?** If you looped on a decision and the AI stayed polite about it, tighten the circling response in your protocol.

The Blueprint is a working document. When it misses, fix the document — not just the conversation.
