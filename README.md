# cv-review

A Claude skill that reads a CV like Karmen and includes insights from other tech recruiters.

Built at //kood for students and alumni applying to tech roles. It works on any CV, and it knows how to frame a //kood background for recruiters who have never heard of the school.

## What it does

- At first it runs the 30-second test on the whole page, not line by line.
- Then it walks the CV section by section against a rubric: header, title, summary, experience, skills, education, projects, length, keyword match.
- Names the fixes in priority order, quotes your own lines back, and shows the pattern to rewrite them with.
- Matches the CV against a specific job posting, both the technical requirements and the behavioural ones.
- You can use the skill to improve cover letter or CV. Make sure you share enough context to give accurate suggestions.

## Install

Pick the tool you use.

### Claude.ai or the Claude desktop app

Works on every plan, including Free.

1. Download **[cv-review.zip](https://github.com/karmenti/cv-review-skill/releases/latest/download/cv-review.zip)**. Keep it zipped.
2. In Claude, open **Settings > Capabilities** and turn on **Code execution and file creation**. Skills need it.
3. Open **Customize > Skills**, click **+**, then **Create skill**, then **Upload a skill**, and pick `cv-review.zip`.

That's it. Start a new chat and share your CV.

Use the zip from the link above, not GitHub's green **Code > Download ZIP** button. That one has a folder called `cv-review-skill-main` inside, and Claude needs the folder name to match the skill's name, `cv-review`.

### Claude Code

Type these two commands into Claude Code, one at a time:

```
/plugin marketplace add karmenti/cv-review-skill
```

```
/plugin install cv-review@cv-review-skill
```

The first tells Claude Code where to find the skill. The second installs it. If the skill doesn't show up right away, restart Claude Code.

To check it worked, type `/cv-review` and look for it in the suggestions. You can start a review that way, or just share your CV and ask for feedback.

<details>
<summary>Prefer a plain folder instead of a plugin?</summary>

Clone the repo into your personal skills folder:

```
git clone https://github.com/karmenti/cv-review-skill.git "$HOME/.claude/skills/cv-review"
```

</details>

### Codex, Cursor, Gemini CLI, GitHub Copilot and others

Open a terminal and run:

```
npx skills add karmenti/cv-review-skill -g
```

It detects which coding agents you have and installs the skill for them. If it asks you anything, the suggested answers are fine. `-g` installs it for your user account, so it works in every project. Restart your agent afterwards so it picks up the new skill.

This needs [Node.js](https://nodejs.org) 22.20 or newer. Run `node --version` to check.

<details>
<summary>No Node.js? Use git instead.</summary>

Codex, Cursor, Gemini CLI and GitHub Copilot all read skills from `~/.agents/skills`, so one clone covers all of them:

```
git clone https://github.com/karmenti/cv-review-skill.git "$HOME/.agents/skills/cv-review"
```

On Windows, run it in PowerShell or Git Bash. Claude Code doesn't read this folder; use the [Claude Code steps](#claude-code) for it.

Gemini CLI also has its own installer:

```
gemini skills install https://github.com/karmenti/cv-review-skill.git
```

</details>

To start a review, share your CV and ask for feedback. To call the skill by name:

| Tool | Type |
|---|---|
| Codex | `$cv-review` |
| Cursor | `/` in Agent chat, then pick `cv-review` |
| GitHub Copilot | Just ask; Copilot picks the skill up on its own. |
| Gemini CLI | Just ask. `/skills list` shows whether it's installed. |

### Any other AI chat

Open `SKILL.md`, copy its contents into the chat, attach your CV, and ask for a review. For better results, paste `references/rubric.md` and `references/star-method.md` too.

### Updating

If you installed it as a Claude Code plugin, run `/plugin marketplace update cv-review-skill` and then `/plugin update cv-review@cv-review-skill`. If you installed with `npx skills`, run `npx skills update cv-review -g`. If you installed with `git clone`, run `git pull` inside the skill folder. If you uploaded a zip, repeat the steps above with a fresh download.

## How to use it

Give it two things:

1. **Your CV.** A PDF, a Word file, or pasted text.
2. **The job posting.** Paste the full text of the posting, not only the link. Some tools cannot open links, and a LinkedIn page often needs a login, so the AI may never see what the job asks for. If you have not picked a role yet, name the direction instead: junior backend, QA, frontend.

A first message can be as short as:

> Here is my CV and the posting for a junior backend role at a logistics company. What should I fix before I apply?

You get back a short verdict, a numbered list of fixes ranked by impact, and an action plan.

The feedback comes in the language your CV is written in. The skill is tested in English and Estonian.

**Your data.** The skill stores nothing and sends nothing anywhere. Your CV goes to whichever AI tool you run it in, under that tool's privacy terms, same as any other chat.

## Which model to use

Pick the strongest model your plan offers and turn on extended thinking if the tool has that setting. In our testing, Claude Opus gives consistently good reviews.

A faster, lighter model still works. Its review tends to be longer and flatter, with every point at the same weight, so you have to decide yourself what matters most.

## What is in the repo

| File | Contents |
|---|---|
| `SKILL.md` | The review process, output structure, tone, and the special cases (career changers, juniors, seniors, long search with no callbacks) |
| `references/rubric.md` | Section-by-section evaluation criteria and the order findings are ranked in |
| `references/star-method.md` | Turning responsibility bullets into outcome bullets |
| `references/action-verbs.md` | Weak to strong verb replacements |
| `references/feedback-template.md` | The response template, with a worked example |
| `references/kood-context.md` | What //kood is and how to put it on a CV |
| `references/cover-letter.md` | Cover letter guidance, used only when asked |
| `references/templates.md` | CV template recommendations, used only when asked |

## A note on examples

Every example in this repo is invented. No real CV, name, or contact detail is used anywhere in it, including the git history.

## License

MIT, see `LICENSE`.

`//kood`, `kood/Jõhvi`, `kood/Võru` and `kood/Järva` are the school's names. Naming the school on your own CV is, of course, fine. The MIT license covers the text in this repository; it does not make a fork or a derived tool a //kood product.
