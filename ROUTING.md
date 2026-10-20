# Routing

One job, one tool. If two could do it, use the one that already has the files open.

## Claude Code
Use when a repo is open and the result is a file change.

- Portfolio copy and layout — `architecture-portfolio-site`
- A post pack on disk — `social-pack-kit`
- Rules and skills — `claude-code-hq`
- This guide — `free-ai-workflow`

Start of session: paste `prompts/claude-code-session.md`, then the task in one line.

### Motion graphics
Video rendered from code, on this machine. Skills: [Barty-Bart/motion-graphics](https://github.com/Barty-Bart/motion-graphics) (MIT).

Install once into the repo that holds the footage or the post pack, not this one:

```
npx skills add Barty-Bart/motion-graphics
```

Or copy a folder from its `skills/` into `.claude/skills/`. Needs Node, Python and ffmpeg. No API key.

| Job | Skill |
|-----|-------|
| B-roll cut to a talking-head transcript | `motion-broll` |
| Cut a person or product out of a clip | `object-separation` (SAM 2, local; slow on CPU, trim the clip first) |
| 12–20 s launch sting or reel teaser | `explainer-high-energy` |
| 45–90 s calm walkthrough or demo | `explainer-default` |
| 10–30 s one-take, loopable story | `explainer-engaging` |
| Sound pass on any of the above | `sound-effects` (bundled CC0 kit) |

Music: synthesised by the skill, or a track you already own. Skip the paid libraries listed in its `MUSIC.md` and the course link in its README.

## Grok
Use when the work needs an account that is already connected.

- Create or update GitHub repos
- Wix or Netlify changes
- Canva briefs
- A morning brief or a weekly GitHub pass on a schedule

Grok drafts. It does not post in public until you approve.

## Claude chat or ChatGPT
Use when there is no repo and the result is words.

- A long caption set you will paste by hand
- A site outline before it becomes HTML
- A second read on a draft Claude Code already wrote

Paste `alex-os/PROMPTS/alex-system.md` first so the rules match.

## Gemini
Use when the input is visual or wide.

- Several reference images at once
- A research sweep you will fact-check
- A rough cut of a short, described in words (rendering the motion graphics is Claude Code)

## Never
- A sixth AI subscription
- Putting unfiled technical work in any of these repos
- Letting a tool post, deploy, or force-push without a yes
