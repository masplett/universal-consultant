# 🎩 Universal Consultant

> **AI-powered consulting that feels human, delivers superhuman thoroughness.**  
> Choose your AI below. Copy. Paste. Experience the upgrade.

---

## ⚡ Quick Start (30 seconds)

### For ChatGPT
1. Open [ChatGPT](https://chat.openai.com)
2. Copy [prompts/chatgpt.md](prompts/chatgpt.md)
3. Paste and say: **`consult`**

### For Claude
1. Open [Claude](https://claude.ai)
2. Copy [prompts/claude.md](prompts/claude.md)
3. Paste and say: **`consult`**

### For Gemini
1. Open [Gemini](https://gemini.google.com)
2. Copy [prompts/gemini.md](prompts/gemini.md)
3. Paste and say: **`consult`**

### For Kimi
1. Use [Kimi CLI](https://github.com/MoonshotAI/kimi-cli) with the [consulting-core skill](../consulting-core)
2. Or copy [prompts/kimi.md](prompts/kimi.md) into [Kimi Web](https://kimi.moonshot.cn)
3. Say: **`consult`**

---

## What's New (The Upgrade)

| Old Way | New Way |
|---------|---------|
| 10 bullets, 7 phases | **6 bullets, 5 phases** + exploration |
| 4 phases before code | **Prototype in Phase 1** |
| Text only | **Optional HTML preview panel** |
| [A/B/C/D] syntax | **Conversational choices** |
| Orchestrator/PM/Subagents | **Single "I" — your consultant** |
| "YOLO mode" | **"Fast-Track mode"** |

---

## The Hybrid Workflow

```
ENTRY POINTS:
┌─────────────┐  ┌─────────────┐  ┌─────────────┐
│  🚀 Explore │  │  🔍 Consult │  │  ⚡ Fast    │
│  (Agile)    │  │  (Standard) │  │  (Express)  │
└──────┬──────┘  └──────┬──────┘  └──────┬──────┘
       │                │                │
       └────────────────┴────────────────┘
                          │
       ┌──────────────────┼──────────────────┐
       │                  │                  │
       ▼                  ▼                  ▼
┌─────────────┐    ┌─────────────┐    ┌─────────────┐
│  Quick      │    │  Full       │    │  Assumptions│
│  prototype  │ →  │  waterfall  │    │  + build    │
│  or spike   │    │  execution  │    │             │
└─────────────┘    └─────────────┘    └─────────────┘
       │
       └──── "Yes! Build this for real" ────→ Full process
```

---

## Commands

| Command | What It Does |
|---------|--------------|
| `consult` | Start standard consulting workflow |
| `explore` | Start with quick prototype/spike |
| `fast-track` | Skip ahead with smart defaults |
| `show preview` | Display HTML preview panel |
| `status` | See current phase and progress |
| `pause` | Save state, resume later |
| `exit` | Return to normal chat |

---

## The 6-Bullet Format

Every response follows this clean structure:

```
• [Status] 🔍 Discovery — Understanding your automation needs
• [Learned] You process 100+ files weekly, currently manual
• [Risk] Scale may require database vs spreadsheet  
• [Progress] ●●●●○ (4/5)
• [→] What's your timeline for this project?
• [○] Skip to Fast-Track mode
```

**Clean. Focused. Human.**

---

## Preview Panel (Optional Luxury)

For visual projects, you'll see an elegant HTML preview:

```
[Preview Panel: 🎨 Design Mockup]
┌─────────────────────────────────────┐
│ Concept A  │  Concept B  │  Concept C│
│   [Img]    │   [Img]     │   [Img]   │
│ Minimal    │  Vintage    │  Modern   │
└─────────────────────────────────────┘
[Download] [Iterate] [Approve]
```

Available for:
- 🎨 Design mockups
- 🔧 Code output  
- 📊 Data visualizations
- 📝 Rich documents

---

## Prompt Variants

| Variant | Best For | Size |
|---------|----------|------|
| **chatgpt.md** | ChatGPT 4o, o1, o3 | ~300 lines |
| **claude.md** | Claude 3.5 Sonnet, Opus | ~280 lines |
| **gemini.md** | Gemini 1.5 Pro, Ultra | ~290 lines |
| **kimi.md** | Kimi k1.5, Moonshot | ~270 lines |

Each optimized for the AI's specific strengths and context window.

---

## Why This Works

### 1. **Human Speed**
- Start with a prototype in minutes, not hours
- 6 bullets, not 10 — less cognitive load
- Conversational, not bureaucratic

### 2. **Superhuman Thoroughness**  
- Phase gates ensure nothing proceeds without your OK
- Verification before delivery
- Evidence, not assumptions

### 3. **Flexible Entry**
- Explore → Prototype → Decide
- Or fast-track if you know what you want
- Or full process for complex projects

---

## Examples

### Scenario: Photo Renamer Script

**Old way:** 8 questions → 3 phases → code at phase 5  
**New way:**

```
You: consult
AI:  • 🔍 Discovery — Understanding your file automation needs
    • Learned: You rename vacation photos by date taken
    • Risk: Different cameras use different date formats
    • Progress: ●○ (1/2)
    • [→] What photo formats? (JPG, RAW, etc.)
    • [○] Fast-track — I'll assume JPG/PNG

You: Fast-track
AI:  [Preview Panel: 🔧 Code Preview]
    ┌─────────────────────────────────┐
    │ Python script • 42 lines        │
    │ • Reads EXIF dates              │
    │ • Renames: YYYY-MM-DD_photo.jpg │
    │ • Handles duplicates            │
    └─────────────────────────────────┘
    [Copy] [Run] [Edit]
    
    Here's your script. Try it — want me to refine anything?
```

**Time to working code: 2 minutes, not 20.**

---

## Contributing

These prompts are generated from [consulting-core](../consulting-core).  
To suggest improvements, open an issue with:
- Which AI you used
- What felt fast/slow
- Where you got confused

---

## License

MIT — Use anywhere, build anything.

---

<p align="center">
  <b>Consulting that feels human. Results that feel like magic.</b><br>
  <code>consult</code> → <code>explore</code> → <code>fast-track</code>
</p>
