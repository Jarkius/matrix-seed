# matrix-seed

> *"The seed contains the DNA. The environment determines the growth."*

The **philosophical core** of The Matrix — a minimal framework for building your own AI-augmented development environment.

## What is This?

matrix-seed is the **philosophy and structure** of The Matrix, without the operational features. It's for builders who want to understand the principles and grow their own system.

```
matrix-seed (Philosophy)     vs     matrix-reloaded (Full Power)
─────────────────────────           ─────────────────────────────
244KB, 53 files                     1.2MB, 180+ files
5 core workflows                    39 workflows
No voice                            Full TTS voice system
Grow your own                       Enter immediately
```

## Quick Start

```bash
git clone https://github.com/Jarkius/matrix-seed.git
cd matrix-seed
claude   # Start Claude Code CLI
/oracle  # Begin
```

## What's Included

### The Source (Philosophy)

Core chapters that define how human and AI collaborate:

| Chapter | Topic |
|---------|-------|
| 01 | Self Knowledge |
| 02 | Bilateral Collaboration |
| 03 | Claude DNA |
| 04 | Multi-Agent Patterns |
| 05 | Retrospectives |
| 06 | Matrix Architecture |
| 07 | Browser Automation |
| 08 | Communication Protocol |
| 09 | Knowledge Flow |

### Core Workflows

| Command | Purpose |
|---------|---------|
| `/oracle` | Start here. Analyze state, receive guidance |
| `/rrr` | Retrospective. Record what happened |
| `/learn` | Gather knowledge from research |
| `/wisdom` | Retrieve stored learnings |
| `/commit` | Git workflow with co-authorship |

### Structure

```
matrix-seed/
├── CLAUDE.md              # AI DNA - how the system thinks
├── PARENT.md              # Origin tracking
├── psi/                   # AI Brain ("External Memory")
│   ├── The_Source/        # Philosophy chapters
│   ├── memory/            # Learnings, retrospectives, ADRs
│   │   ├── learnings/     # Distilled wisdom
│   │   ├── retrospectives/# Session records
│   │   └── adr/           # Architecture decisions
│   └── learn/             # Knowledge gathering
│       ├── inbox.md       # Quick capture
│       ├── active/        # Current research
│       └── archive/       # Completed research
└── .agent/workflows/      # Command definitions
```

## The Council (Agent Roles)

The Matrix uses a multi-agent mental model:

| Agent | Role | Purpose |
|-------|------|---------|
| **Oracle** | Orchestrator | Align with mission, dispatch to agents |
| **Neo** | Developer | Write code, implement features |
| **Trinity** | Designer | Design systems, UI/UX guidance |
| **Morpheus** | Researcher | External research, web search |
| **Architect** | System Design | ADRs, architecture decisions |
| **Smith** | Debugger | Bugs, security, anomalies |
| **Tank** | Operator | Internal search, git, dependencies |
| **Scribe** | Chronicler | Retrospectives, documentation |

In the seed, these are concepts. In [matrix-reloaded](https://github.com/Jarkius/matrix-reloaded), they have full personalities and voices.

## Prime Directives

1. **Nothing is Deleted** — Archive, don't destroy
2. **Patterns > Intentions** — Document what *is*, not what *should be*
3. **Knowledge Loop** — `/learn` to gather, `/wisdom` to retrieve
4. **Proactive Care** — If it's important, do it. Don't wait to be asked.

## Growing Your Matrix

The seed is minimal by design. To grow:

1. **Document sessions** with `/rrr` — Record what happened, what you learned
2. **Capture learnings** with `/learn` — Turn research into knowledge
3. **Add new workflows** — Create `.agent/workflows/your-command.md`
4. **Develop your own Source chapters** — Add to `psi/The_Source/`

### Upgrade Path

When you want full power:

```bash
# Option A: Clone reloaded separately
git clone https://github.com/Jarkius/matrix-reloaded.git

# Option B: Copy features from reloaded to your grown seed
cp -r matrix-reloaded/psi/matrix ./psi/                       # Voice system
cp -r matrix-reloaded/.agent/workflows/* ./.agent/workflows/  # All commands
cp -r matrix-reloaded/.claude/agents/* ./.claude/agents/      # Personalities
```

## Contributing Back

Discovered something universal? Return it to the seed:

1. Fork this repository
2. Add your learning to `psi/memory/learnings/`
3. If it's truly universal, add to The Source
4. Submit a pull request

See `PARENT.md` for reunion guidelines.

## Related

| Repository | Description |
|------------|-------------|
| [matrix-reloaded](https://github.com/Jarkius/matrix-reloaded) | Full operational Matrix with voice |
| [The-Oracle-Construct](https://github.com/Jarkius/The-Oracle-Construct) | Living source of truth |

## Origin

Extracted from The-Oracle-Construct.
See `PARENT.md` for version tracking.

---

*"Know Thyself." — The Oracle*
