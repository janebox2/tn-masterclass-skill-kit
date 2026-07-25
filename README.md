# Masterclass Build System — Claude Code Skill Kit

Three Claude Code skills that take you from a blank page to a finished, high-converting masterclass — **in your own voice, for your own audience.**

1. **`setup`** — run this once. It interviews you for your voice, your ideal client, and your offer, and saves a small calibration layer the other two skills read every time. It refuses to build from nothing and ends with a short dress rehearsal so you see it work in your words.
2. **`build-icp`** — turns that sketch into a full ideal-client profile with real Voice-of-Customer research from the web.
3. **`build-masterclass`** — writes the whole class: Phase 1 the full spoken script (17-part spine), Phase 2 a slide-by-slide deck map, Phase 3 (optional) an actual Canva deck.

---

## The four steps

You need to do four things. Everything technical happens on Claude's side.

1. **Download** this kit (the zip).
2. **Unzip** it.
3. **Drag** the `.claude` folder into your business folder (the folder you open in Claude Code).
4. **Paste** this one message into Claude Code:

   > Run the setup skill to get me set up for the Masterclass Build System.

That's it. Claude takes over from there — it interviews you, builds your calibration files, and shows you a dress rehearsal. When setup is done, you run `/build-icp` then `/build-masterclass`.

---

## Don't have Claude Code yet?

Get the **Claude desktop app** (Mac or Windows) — it's the non-technical-friendly version, no terminal required. Sign in, open your business folder, and paste the message above. If you prefer the command line, the CLI works identically.

---

## Where the skills live

The kit puts them here:

```
your-business-folder/
└── .claude/
    └── skills/
        ├── setup/            └── SKILL.md
        ├── build-icp/        └── SKILL.md
        └── build-masterclass/└── SKILL.md
```

Skills in a project's `.claude/skills/` load whenever you open that folder in Claude Code. To make them available in *every* project on your machine instead, drag the three skill folders into `~/.claude/skills/`.

---

## What you'll need

- **Claude Code** (desktop app is easiest, or the CLI / IDE extension).
- **Real writing of your own** — a couple of published emails, captions, or a sales page. `setup` will not calibrate to a voice that isn't on the page yet.
- **Web access** for the research phase (optional — it'll build from your interview alone if web isn't available).
- **A Canva connection** only if you want Phase 3 to build the actual deck. The Phase 2 slide map is a human-buildable deliverable on its own.

---

## Notes

- **Your voice and your audience are different from anyone else's** — that's the entire reason `setup` exists. You don't inherit someone else's calibrations; you build your own in about fifteen minutes.
- The **17-part spine is fixed** — that's the proven structure. The skills change the words inside it for each audience, never the order.
- The governing law never changes: **sell the emotion, not the thing.**
