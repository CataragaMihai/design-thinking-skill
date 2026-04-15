# Design Thinking Skill for Claude

This is a Claude Code skill that transforms Claude into a senior IDEO design engineer, guiding you through David and Tom Kelley's human-centered design process, described in their book "Creative Confidence" with structured facilitation, Six Thinking Hats method integration, and concrete output artifacts at every phase.

## What it does

This skill runs you through five design thinking phases: **Empathize -> Define -> Ideate -> Prototype -> Test**. This is not a rigid checklist, but  a living, non-linear facilitation framework grounded in empathy and creative confidence.

**Core features:**

- **Phase tracking** — Claude announces the current phase and explains transitions and loops
- **Quick Assessment Mode** — Get a rapid, structured check on any idea without running the full process
- **Six Thinking Hats integration** — The hats represent a thinking framework, where each hat represents a core mentality you have to adopt. The framework is deployed at the right moments in each phase
- **The Reframe Trigger** — Mandatory problem reframing before committing to a direction
- **Concrete artifacts** — Every phase produces a specific output (Empathy Maps, Personas, POV statements, "How might we" questions, Idea Inventories, Prototype Briefs, Learning Captures)
- **Filled examples** — Real worked examples for every artifact, so Claude knows what good output looks like

## Who it's for

Anyone using Claude to think through product ideas, apps, startup concepts, service design challenges, or innovation problems. Works for:

- Solo founders validating and working through an idea
- Product teams running lightweight design sprints
- Students learning human-centered design methodology
- Anyone who has an idea and wants to stress-test it rigorously and get a deeper understanding, going beyond surface level

## Installation

### Claude Code CLI

Copy the `SKILL.md` file into your Claude skills directory:

```bash
# Global installation (available in all projects)
mkdir -p ~/.claude/skills/design-thinking
cp SKILL.md ~/.claude/skills/design-thinking/SKILL.md

# Project-level installation
mkdir -p .claude/skills/design-thinking
cp SKILL.md .claude/skills/design-thinking/SKILL.md
```

### Claude.ai Web Interface

1. Go to **Settings > Capabilities**
2. Enable Skills
3. Upload the `SKILL.md` file

## Usage

The skill activates when you describe a problem to solve or an idea to explore. You don't need to say "design thinking" explicitly.

**Full process:**
```
I have an idea for a meal planning app that helps busy parents.
Help me think this through.
```

**Quick assessment:**
```
Quick take — is a neighborhood tool-sharing app a good idea?
```

**Jump to a specific phase:**
```
I've already done user interviews. Here's what I found: [findings].
Help me define the problem and generate ideas.
```

## What's inside

| Section | What it covers |
|---------|---------------|
| Phase Tracking | Automatic phase indicators and transition announcements |
| Quick Assessment Mode | Structured rapid feedback template for fast gut-checks |
| 8 Design Abilities | Kelley's behavioral principles applied throughout |
| 5-Phase Toolkit | Full tools, questions, traps, and exit criteria per phase |
| Worked Examples | Filled-in Empathy Map, POV + HMW, Idea Inventory, Prototype Brief, and Learning Capture |
| Six Thinking Hats Map | Which hat to deploy at which moment in each phase, with facilitator scripts |
| Reframe Trigger | Mandatory problem reframing protocol |

## Methodology

Based on:
- **David Kelley's** Creative Confidence and the Stanford d.school curriculum
- **IDEO's** human-centered design process
- **Edward de Bono's** Six Thinking Hats parallel thinking framework

## License

MIT License — see [LICENSE](LICENSE).

## Contributing

Found a way to improve the skill? PRs welcome. The best contributions come from people who've actually used this skill on a real project and noticed where it falls short.
