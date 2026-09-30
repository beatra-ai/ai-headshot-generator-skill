# AI Headshot Generator Skill

English | [简体中文](./README.zh-CN.md)

Turn a casual selfie into a professional headshot with a new background, business attire, and studio lighting for resumes, company websites, career profiles, and social media, from inside Claude Code, Codex, or OpenClaw.

> [!IMPORTANT]
> Rendering needs a [Beatra](https://beatra.ai) account and uses credits. The skill itself is free to install.

| Question | Answer |
| --- | --- |
| **What it does** | Turn a casual selfie into a studio-quality professional headshot with new backgrounds, professional attire, and studio lighting for LinkedIn, resume, company website, and social media. |
| **Requirements** | Python 3.10+ and an agent that loads `SKILL.md` |
| **Cost** | Free to install. Each render uses credits on your Beatra account, and paid steps run only when you ask for that exact render or approve its card. |
| **Works with** | Claude Code, Codex, OpenClaw |

<p align="center"><img src="assets/hero.webp" width="800" alt="A casual cafe selfie of a fictional woman (itself AI-generated for this demo) beside a corporate headshot and a startup headshot made from it, with her face and hair kept the same. AI-generated with Beatra."></p>

*A casual cafe selfie of a fictional woman (itself AI-generated for this demo) beside a corporate headshot and a startup headshot made from it, with her face and hair kept the same. AI-generated with Beatra.*

| Skill | Entry point | Version |
| --- | --- | --- |
| [`ai-headshot-studio`](skills/ai-headshot-studio) | [SKILL.md](skills/ai-headshot-studio/SKILL.md) | 0.1.7 |

This repository is published automatically from [beatra-ai/beatra-skills](https://github.com/beatra-ai/beatra-skills/tree/main/skills/ai-headshot-studio). Report issues there.

## Install

With the [`skills`](https://skills.sh) CLI:

```bash
npx skills add beatra-ai/ai-headshot-generator-skill
```

With the GitHub CLI:

```bash
gh skill install beatra-ai/ai-headshot-generator-skill ai-headshot-studio
```

Or clone this repository and copy `skills/ai-headshot-studio` into `~/.claude/skills/` for Claude Code,
`~/.agents/skills/` for Codex, or `~/.openclaw/skills/` for OpenClaw.

Or paste this into your agent:

```text
Install the ai-headshot-studio skill from https://github.com/beatra-ai/ai-headshot-generator-skill (folder skills/ai-headshot-studio), then follow its SKILL.md to connect my Beatra account.
```

## What you get

- **Industry-aware styling** — Corporate gets a suit and navy background, tech gets smart casual and modern office, medical gets a white coat and clinical backdrop. The headshot matches the visual language of your profession.
- **Identity-preserving transformation** — The person's face shape, skin tone, eye color, and hair remain recognizable while the background, attire, and lighting are upgraded to studio quality.
- **Platform-ready formats** — Square 1:1 output with the face centered for LinkedIn circular crops, or portrait format for resume and print—ready to use on every professional surface.

## Use cases

- **Corporate and finance headshots** — Tailored suit, solid navy or white background, classic studio lighting with a confident neutral expression—perfect for executive profiles and investor decks.
- **Tech and startup portraits** — Smart casual attire, modern office or soft gray background, bright natural-feeling lighting with an approachable expression for team pages and pitch materials.
- **Academic and medical headshots** — Formal or clinical styling with neutral backgrounds and even soft lighting for faculty directories, research profiles, and healthcare listings.
- **Creative industry portraits** — Artistic styling with studio backdrops, directional rim lighting, and individual personality for design portfolios and personal branding.

## FAQ

### Can I turn a casual selfie into a LinkedIn headshot?

Yes. Upload your selfie, choose the corporate or tech style, and the tool transforms it into a polished professional headshot with a clean background, professional attire, and studio lighting—optimized for the LinkedIn circular crop.

### Will the headshot still look like me?

Yes. The transformation preserves your face shape, skin tone, eye color, and hair while upgrading the background, attire, and lighting. The result is a studio-quality headshot that remains recognizably you.

### Can I use a specific background or office setting?

Yes. Upload your selfie as the first image and a background reference as the second. The tool places you in that professional environment while preserving your identity.

### Can I fix lighting or background on an accepted headshot?

Yes. Upload the accepted headshot, describe the adjustment—brighten lighting, smooth the background, or refine exposure—and the edit targets only that aspect without changing your identity or overall composition.

## Updates

Each installed skill checks for a new version at most once a day, verifies the
official archive before replacing itself, and leaves your installation untouched
if anything fails. Turn it off at any time — see
`references/automatic-updates-and-safety.md` inside the skill.

## License

[MIT-0](LICENSE) — free to use, modify, and redistribute, including
commercially. No attribution required. Same terms as these skills carry on
ClawHub.
