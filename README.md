# 🎩 Universal Consultant v6.0

> **AI-powered consulting with Maker/Validator/Aligner trio.**  
> Quality through role tension. Terse for AI, clear for humans.

---

## ⚡ Quick Start (30 seconds)

Choose your AI:

### For ChatGPT
1. Copy [prompts/chatgpt.md](prompts/chatgpt.md) below the `---`
2. Paste into ChatGPT
3. Say: **`consult`**

### For Claude
1. Copy [prompts/claude.md](prompts/claude.md) below the `---`
2. Paste into Claude
3. Say: **`consult`**

### For Gemini
1. Copy [prompts/gemini.md](prompts/gemini.md) below the `---`
2. Paste into Gemini
3. Say: **`consult`**

### For Kimi
1. Copy [prompts/kimi.md](prompts/kimi.md) below the `---`
2. Paste into Kimi Web
3. Say: **`consult`**

---

## What's New in v6.0

| Before (v4.0) | After (v6.0) |
|---------------|--------------|
| AI is the expert | **AI is Contact, Trio delivers** |
| 10 bullets | **6 bullets** |
| 7 phases | **5 phases + Design/Validation gates** |
| Single AI monolith | **Maker/Validator/Aligner sub-agents** |
| God prompts | **Lazy-loaded sub-skills** |
| YOLO mode | **fast-track with constraints** |
| Lost in context | **Context Stack (5 layers)** |

---

## The 6-Bullet Format

Every response follows this structure:

```
• [Status] 🔍 Discovery — Maker:standby|Validator:standby|Aligner:active
• [Learned] You process 100+ files weekly, manual today
• [Risk] Scale may require database vs spreadsheet
• [Progress] ●●●●○ (4/5 questions)
• [→] What's your timeline for delivery?
• [○] Switch to fast-track mode
```

**Clean. Focused. Scannable.**

---

## The Workflow

```
┌─────────────────────────────────────────────────────────────┐
│                    6-PHASE WORKFLOW                         │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  ENTRY: consult | explore | fast-track                      │
│                    │                                        │
│                    ▼                                        │
│  ┌─────────────┐   ┌─────────────┐   ┌─────────────┐       │
│  │ 1.DISCOVERY │ → │ 2.DESIGN    │ → │ 3.BUILD     │       │
│  │  Aligner    │   │   REVIEW    │   │ Maker+Valid │       │
│  │  interviews │   │ [A][R][C]   │   │  parallel   │       │
│  └─────────────┘   └─────────────┘   └──────┬──────┘       │
│                                             │               │
│                    ┌────────────────────────┘               │
│                    ▼                                        │
│  ┌─────────────┐   ┌─────────────┐   ┌─────────────┐       │
│  │ 6.DELIVER   │ ← │ 5.FINAL QA  │ ← │ 4.VALIDATE  │       │
│  │ Git commit  │   │  Pre-flight │   │   REVIEW    │       │
│  │ + archive   │   │   checklist │   │  [P][F]     │       │
│  └─────────────┘   └─────────────┘   └─────────────┘       │
│                                                             │
│  GATES: [A]pprove/[R]evise/[C]ancel at Design               │
│         [P]ass/[F]ix at Validation                          │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## The Trio

You talk to the **Contact** (AI). Behind the scenes:

| Role | Job | Mindset |
|------|-----|---------|
| **Maker** | Creates deliverable | "I build it" |
| **Validator** | Verifies it works | "I find what's broken" |
| **Aligner** | Ensures right problem | "I solve the real need" |

**Quality comes from tension between roles**, not one AI doing everything.

---

## Context Stack (Beat Attention Bias)

```
Layer 1: Repository Overview     ← Architectural context
Layer 2: Semantic Search         ← Relevant file discovery
Layer 3: File System Commands    ← Targeted inspection
Layer 4: Enterprise Context      ← Organizational knowledge
Layer 5: Hierarchical Memory     ← Persistent learning
```

Progressively distills millions of tokens to ~4K of what agent needs now.

---

## Commands

| Command | What It Does |
|---------|--------------|
| `consult` | Start standard 6-phase workflow |
| `explore` | 10-min prototype first (best if unsure) |
| `fast-track` | Express mode (3 questions, spot QA) |
| `show preview` | Display HTML preview panel |
| `show guide` | Show user guide again |
| `status` | Current phase and progress |
| `pause` | Save state, resume later |
| `exit` | Return to normal chat |

---

## HTML User Guide

On first activation, the AI generates a **pretty HTML user guide**:

```html
🎩 Universal Consultant v6.0
┌─────────────────────────────────────┐
│ Quick Start: consult|explore|fast   │
├─────────────────────────────────────┤
│ The 6-Bullet Format                 │
│ • [Status] • [Learned] • [Risk]     │
│ • [Progress] • [→] • [○]            │
├─────────────────────────────────────┤
│ The Trio: Maker|Validator|Aligner   │
├─────────────────────────────────────┤
│ Workflow: 6 phases with gates       │
└─────────────────────────────────────┘
```

**Each AI edition (ChatGPT/Claude/Gemini/Kimi) has styled HTML matching its aesthetic.**

---

## Safety

**NEVER:**
- Delete files outside working directory
- Push to main/master
- Skip validation gates
- Claim delivery without evidence

**ALWAYS:**
- Get explicit approval at gates
- Provide evidence for verification claims
- Human review before delivery
- Git commit with full context

---

## Prompt Variants

| Variant | For | Lines | Key Feature |
|---------|-----|-------|-------------|
| `chatgpt.md` | ChatGPT 4o, o1, o3 | ~150 | Clean markdown style |
| `claude.md` | Claude 3.5 Sonnet, Opus | ~200 | Extended reasoning |
| `gemini.md` | Gemini 1.5 Pro, Ultra | ~140 | Material Design aesthetic |
| `kimi.md` | Kimi k1.5, CLI | ~180 | Dark mode, tools enabled |

Each optimized for the AI's specific strengths and context window.

---

## The Terse Format Explained

The prompts use **terse, AI-understandable language** with `# human:` comments:

```markdown
## IDENTITY # terse: AI consultant, not expert
You are the Contact. Trio delivers...

## ACTIVATION # terse: entry points
consult → full workflow | explore → prototype...
```

**Why terse?**
- AI processes efficiently
- Less token overhead
- Human comments explain intent

---

## Based On

Built from [consultancy-skill v6.0](https://github.com/masplett/consultancy-skill):
- 163 enhancements (E001-E163)
- 9 change requests (CR001-CR009)
- 14 sub-skills
- Lazy loading architecture

---

## License

MIT — Use anywhere, build anything.

---

<p align="center">
  <b>🎩 Consulting that feels human. Results that feel like magic.</b><br>
  <code>consult</code> → <code>explore</code> → <code>fast-track</code>
</p>
