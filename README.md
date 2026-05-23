# Ali Rahim · Hina Jamelle · CAP — Perspective Skill

> A "mean-but-fair" thinking-advisor skill that lets you frame architecture / studio / pedagogy questions through the **Rahim–Jamelle / Contemporary Architecture Practice / UPenn MSD-AAD** lens.
>
> Generated with [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill).

---

## What this is

A portable AI skill (a `SKILL.md` file plus structured research notes) that gives any compatible agent — Claude Code, Codex, Cursor, etc. — a working model of how Ali Rahim and Hina Jamelle frame architectural problems through their joint practice (Contemporary Architecture Practice, "CAP") and their joint role at the University of Pennsylvania's MSD-AAD program.

It is built to be **useful for thinking**, not flattering. The source material (Penn faculty pages, CAP website, AAD program website, Wikipedia) is heavily self-promotional, so the skill is constructed as a *critical reading* of that material — naming its rhetorical moves, its commercial pipeline, its post-critical politics, and its honest limits. It is also explicit about what the lens cannot see: climate, race, labor, decolonial questions, vernacular practice.

The skill captures:

- **7 mental models** — Catalytic Formation, Elegance, Asset Architecture, Fabrication-as-Verification, Disciplinary Autonomy, Future-Orientation, Urban Housing as Operational Floor
- **3 voices** — partnership default, Rahim-only mode, Jamelle-only mode
- **7 decision heuristics** — actionable rules-of-thumb for studio crits / portfolio choices
- **A structural reading of the partnership** — Rahim does the concept/brand axis, Jamelle does the housing/operations axis, both since 2003

---

## Installation

### Quick install (one-line)

In any compatible AI agent (Claude Code, Codex, Cursor, …) with the [nuwa-skill](https://github.com/alchaincyf/nuwa-skill) framework installed, just say:

```
帮我安装这个 skill：https://github.com/CoconaLiu/CyberAli
```

(Replace the URL with the repository you push this to.)

### Manual install

Clone the repo into your agent's skills directory:

| Runtime | Path |
|---------|------|
| Claude Code | `~/.claude/skills/ali-rahim-perspective/` |
| Codex CLI | `~/.codex/skills/ali-rahim-perspective/` |
| Cursor | `~/.cursor/skills/ali-rahim-perspective/` |
| Other | The skills directory the runtime reads from |

```bash
git clone https://github.com/CoconaLiu/CyberAli.git ~/.claude/skills/ali-rahim-perspective
```

(On Windows PowerShell: `git clone <url> $env:USERPROFILE\.claude\skills\ali-rahim-perspective`)

Restart your agent. The skill should auto-load.

### Direct copy

If your agent doesn't support auto-loading, paste the contents of [`SKILL.md`](SKILL.md) directly into the agent's system instructions or open it as a working file.

---

## Usage

Once installed, you can invoke the skill in any conversation by:

**Direct invocation**
```
/ali-rahim-perspective
```

**Triggered by phrasing**
```
用 Rahim 视角评一下我的 thesis
How would CAP critique this project?
Jamelle 会怎么看这个 urban housing 方案？
Rate this through the AAD lens
Run a CAP studio crit on my portfolio piece
```

**Asking for both voices' productive disagreement**
```
How would Rahim and Jamelle disagree about [project / firm / school]?
What would Rahim emphasize, and what would Jamelle handle differently?
```

The skill will respond in Rahim/Jamelle voice (English by default, but it will answer questions posed in Chinese in Chinese), apply mental models to specifics, and explicitly flag when a question lands outside the lens — e.g. social/ecological/labor critique, where it will recommend switching lenses rather than fake competence.

---

## What's inside

```
ali-rahim-perspective/
├── SKILL.md                     # main skill file (the lens)
├── README.md                    # this file
├── LICENSE                      # MIT
└── references/
    ├── research/                # per-dimension research notes
    │   ├── 01-writings.md       # books, AD issues, terms
    │   ├── 02-conversations.md  # lectures / interviews (mostly gap)
    │   ├── 03-expression-dna.md # verified quotes + vocabulary
    │   ├── 04-external-views.md # endorsements + group-level critique
    │   ├── 05-decisions.md      # career and CAP project trajectory
    │   ├── 06-timeline.md       # chronology
    │   ├── 07-aad-program.md    # AAD as Rahim's pedagogical "project"
    │   └── 08-jamelle-cap.md    # Hina Jamelle + CAP as a structured partnership
    └── sources/                 # empty — drop first-hand PDFs/transcripts here to update
```

---

## Sources

Primary sources used to build this skill — all publicly accessible:

| Source | URL |
|--------|-----|
| Ali Rahim — UPenn Weitzman faculty page | <https://www.design.upenn.edu/people/ali-rahim> |
| Hina Jamelle — UPenn Weitzman faculty page | <https://www.design.upenn.edu/people/hina-jamelle> |
| Contemporary Architecture Practice (CAP) | <https://www.c-a-p.net/> |
| CAP — About page | <https://www.c-a-p.net/about> |
| UPenn MSD-AAD program (Weitzman) | <https://www.design.upenn.edu/architecture/graduate/post-professional-program-msd-aad> |
| UPenn AAD program — standalone website | <https://www.upenn-weitzman-aad.com/> |
| Wikipedia — Ali Rahim | <https://en.wikipedia.org/wiki/Ali_Rahim> |

Several sources (Routledge book pages, Wiley AD issue tables of contents, Architectural Record articles, ArchDaily project pages, Google Scholar, YouTube structured search) were not retrievable during construction. Those gaps are marked as **"信息不足" / "information gap"** throughout the research files. The skill is honest about what it does not know.

---

## ⚠️ Disclaimer

Please read this section. It matters.

### Not an authorized profile

This skill is an **independent, fan-made interpretive model** of two living architects and their practice. It is **not affiliated with, endorsed by, or reviewed by** Ali Rahim, Hina Jamelle, Contemporary Architecture Practice (CAP), the University of Pennsylvania, the Stuart Weitzman School of Design, the MSD-AAD program, or any related institution.

The subjects of the skill have not authored, approved, or contributed to it.

### "Mean-but-fair" critical framing

The skill was generated at the user's explicit request as a **critical reading** of self-promotional source materials, rather than as a reproduction of those materials' own voice. As a result, the "mental models" section makes interpretive judgments, names rhetorical moves, and surfaces tensions that the subjects' own public discourse does not foreground. These are **the author's readings**, not the subjects' positions. Where the skill speaks "as" Rahim or Jamelle, it is simulating a voice based on public materials — it is **not quoting either person**.

### Likely inaccuracies

The following categories of content in the skill are inferred and may be wrong:

- **Internal division of labor inside CAP** — inferred from job titles, single-author book signatures, and pre-firm biographies; CAP itself does not publish this split
- **Project attributions** (which director "led" which project) — inferred, not confirmed
- **Specific dates and years** — corroborated where possible across sources, but year discrepancies exist between Penn faculty page and AAD program website (e.g. *Impact* AD issue listed as 2020 on one page, 2021 on another)
- **Original arguments of books and AD editorial introductions** — the actual prose of *Catalytic Formations*, *Turbulence*, *Catalytic Forms*, *Under Pressure*, and the AD editorial introductions was **not retrieved** during construction; arguments are reconstructed from titles, course names, marketing copy, and the surrounding discourse
- **Lecture / interview content** — no transcripts were retrieved; the skill models the subjects' *written* voice, not how they speak in conversation
- **Critical reception** — no independent book reviews, student evaluations, or critical articles responding to Rahim or Jamelle specifically were retrieved; critical material here is generalized from broader post-critical / digital-architecture debates (Aureli, Spencer, Martin, etc.)

### Personal relationship claim

The skill's source materials do not state any personal/family relationship between Ali Rahim and Hina Jamelle. The skill's frontmatter notes "they are also life partners (per user)" — this is a **user-supplied claim**, not independently verified. The skill is built primarily on the **public professional partnership** (CAP, AAD), which is fully documented. Users running the skill with their own agents may treat the personal claim as unverified context.

### Blind spots by design

The skill is built to not see what its subjects' frame is built to not see:

- Climate, carbon, labor conditions on Asian construction sites
- Race, decolonial discourse
- Tenant experience of urban housing
- Vernacular / in-situ / slow / local design practice
- Equity in pedagogical access

For those questions, **switch lenses**. Do not run the Rahim–Jamelle/CAP skill against them and treat the output as serious engagement.

### Use responsibly

- Do not present skill outputs as **quotations from** or **positions of** Ali Rahim, Hina Jamelle, CAP, UPenn, or AAD
- Do not use skill outputs as a substitute for reading the subjects' actual books, articles, and project documentation
- Update the skill when new material becomes available — both the named individuals' practice and the discourse around them evolve
- If you are one of the named subjects and you'd like the skill modified or removed, please open an issue on the repository

### Takedown / correction policy

If the subjects of this skill, or their institutions, request modification or removal, the repository will respond promptly. Open a GitHub issue or contact the repository owner directly.

---

## Credits

- **Lens design framework**: [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill) by [花叔](https://x.com/AlchainHust)
- **Skill construction**: generated through the nuwa-skill workflow with a user-directed "mean-but-fair" framing pass
- **Sources**: see Sources table above; all publicly accessible at the time of generation (2026-05-23)

---

## License

[MIT](LICENSE) — see `LICENSE` file. You are free to use, modify, and redistribute, including for commercial purposes, provided the copyright notice is retained.

The license covers the skill *file* (this code/text). It does not grant any rights to the underlying source material owned by the named individuals or institutions, which remain their property.
