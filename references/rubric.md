# CV Evaluation Rubric

Walk through each section in order. For each, score implicitly (good / weak / missing) and note specifics.

## 1. Header & contact info

**Required:**
- Full name (large, top of page)
- Email (professional, not example@example.com)
- Phone with country code
- LinkedIn URL (the actual URL, not "linkedin.com/in/myname" if it's broken)
- Location (city, country, full address is unnecessary and a privacy risk)

**Optional but valuable for tech roles:**
- GitHub URL, only if it has actual content and recent activity. An active GitHub can give a junior a competitive edge: recruiters might scan it to see which technologies you've worked with and whether you've been active recently. Recruiters typically don't read code; engineering teams or hiring managers may go deeper later. An empty or inactive GitHub is worse than no link.
- Portfolio URL, only if it works and looks current.

**Red flags:**
- Date of birth, marital status, nationality (not needed; can introduce bias)
- Nickname or unprofessional handle
- LinkedIn URL that 404s or is not customized (linkedin.com/in/abc123-xyz-456789)

A photo is **not** a red flag by default. Whether it helps or hurts depends on market and context, see the photo guidance in `SKILL.md`. Don't reflexively flag it.

## 2. Title / headline

This sits right under the name. It is the line recruiters sort by, and it takes one edit to change.

The title labels the CV; it doesn't carry the evidence. A precise title on a CV that never shows what the candidate delivered still doesn't get the call. Fix it as part of positioning the top of the page, not as the headline finding. See the scoring guidance at the end of this file for where it ranks.

**Good:** matches the role they're applying for or the role they want to be in.
- "Junior Software Developer"
- "Full-Stack Engineer | React + Node.js"
- "Aspiring Backend Developer | kood/Jõhvi student"

**Bad:**
- Their last job title when applying for a different role (e.g., "Logistics Coordinator" applying to dev)
- Vague self-descriptors ("Tech Enthusiast", "Problem Solver", "Creative Mind")
- Empty / missing

For career changers, the title must signal the destination, not the origin.

## 3. Summary / professional profile

2-4 lines, right below the title. This is the "why call me" pitch.

**Must answer:**
- What kind of role am I (or do I want to be in)?
- What's my strongest proof of capability?
- What value do I bring this specific employer?

**Good:** "Backend developer with 2 years of experience scaling Node.js services to 100k+ users. Strong in PostgreSQL performance tuning and AWS infrastructure. Looking to join a product team where engineering velocity matters."

**Bad:**
- "Hardworking and motivated individual seeking opportunities to grow."
- "Passionate about technology and team collaboration."
- Anything that could be on anyone's CV.

If you read the summary and it could fit any of 100 other candidates, it doesn't differentiate, and the recruiter has nothing to pitch forward.

**A separate "Key strengths" section, when the CV has one, has to be backed by the CV body.** Every claim needs a specific entry elsewhere on the page that proves it: "leadership experience" points to a role where they led people, "rapid prototyping" points to a hackathon or a shipped side project. Claims with nothing behind them read as filler and they weaken the ones that are earned. Check each line against the rest of the CV and name the ones the CV doesn't support.

## 4. Experience

Each role should have:
- Company name + role + dates (month + year, not just year)
- 3-6 bullets per recent role; fewer for older roles
- Each bullet uses STAR (see star-method.md): what was the situation, what did *you* specifically do, what was the result

**Quality check for each bullet:**
- Does it start with a strong action verb? ("Built", "Shipped", "Reduced", "Led")
- Does it say what *you* did vs what the team did?
- Does it show an outcome or impact, not just the task? A number sharpens it but isn't required; a qualitative result still counts.
- Could this exact bullet appear on a colleague's CV? If yes, it's not specific enough.

**Watch for:**
- "Responsible for X" → passive, weak. Replace with "Owned" / "Delivered".
- "Worked on Y" → vague. What did you *do* and what *happened*?
- Wall of text bullets, should be 1-2 lines each, scannable.

**Timeline continuity (whole CV, not per role):** combine work and education dates into one timeline and check where it ends. If the most recent dated entry ended 6+ months before today and nothing covers the time since, that is a blocking finding: the recruiter will ask "what has this person done since?" and the CV should answer it on the page. See SKILL.md Step 3 for how to raise it (ask what filled the period, recommend a truthful dated line, don't speculate about the cause). Gaps between older entries matter far less; leave them alone unless they are long and the candidate or posting makes them relevant. If the timeline reaches the present with no gap, note nothing: this check exists to catch a specific failure, not to produce a status update either way.

## 5. Skills

For tech roles, organize by category:
- Languages (Python, JavaScript, Go)
- Frameworks (React, Express, Django)
- Tools / infra (Docker, AWS, PostgreSQL, Git)
- Soft skills as a standalone list adds little value; recruiters discount unverified claims like "team player" or "great communicator". When suggesting fixes, recommend either trimming the list or showing the same trait through an experience bullet (e.g. "Built cohesive teams across multicultural environments while leading X" earns its place; "Collaborative team player" doesn't). Don't push for full removal as the only option; trim or back with evidence are both valid.

**Red flags:**
- Self-rated proficiency bars ("HTML ████████░░ 80%"), meaningless to recruiters
- Skill clouds / word art
- 50+ skills listed, looks unfocused; pick the 15-20 most relevant
- Including things every developer has (Microsoft Word, email, internet)

**Match against the job posting** (if available): the most-mentioned skills in the posting should appear in the candidate's skill list, and ideally also in experience bullets.

## 6. Education

- For students / fresh grads: above experience, with relevant coursework / projects
- For 3+ years experience: below experience, brief
- For 10+ years: one line, just school + degree + year

//kood students: list with the specific campus (kood/Jõhvi, kood/Võru, kood/Järva), program name, and dates as month + year. A short factual note about the program type (project-based, peer-learning, team projects) educates recruiters who don't know the school. Don't lean on the school name as a credential; the projects carry the weight. See `kood-context.md` for full guidance.

## 7. Projects

When this section is required:
- The candidate has **no relevant work experience in the target field** (typical for kood/Jõhvi students, bootcamp grads, and career switchers in transition). In this case the Projects section is the core of the CV; if it's missing entirely, that's the top-priority fix.
- The candidate has work experience but in a different field (career changers). Projects are still expected as proof of new-domain capability.

When this section is optional:
- The candidate has relevant work experience in the target field with demonstrable impact. Their experience carries the CV. Projects can supplement (open source, relevant side projects) but aren't required.

Each project should include:
- Name and a one-line description
- Tech stack used
- What the candidate specifically built (not "we built")
- Outcome: users, deployment, what was learned
- A link to source or a live demo when one exists. Links are valuable but not required: a project with no public repo is still worth listing. Recommend adding a link only if the candidate has one; don't treat a missing link as a gap to fix.
- Any external validation, in bold next to the project name: a placement ("3rd place, Global Game Jam 2025"), stars on a public repo, real users, selection into a program. On a junior CV this is the strongest single signal the section can carry, and candidates routinely leave it out because it feels like boasting.

**At least one project should articulate the problem it solves.** A recruiter reading one line should understand why the project exists, even if the problem is small or personal. A budget tracker built because shared flatmate expenses kept landing in unupdated spreadsheets is a problem statement; "built a budget tracker" alone isn't.

Technical exercises without real users are valid. Frame them around the technical problem (what made it interesting, what choices were made and why) rather than pretending real-world impact. A custom JS framework built to understand how React works under the hood is honest and signals depth.

**Where the projects sit on the page matters as much as what they say.** When the candidate has no paid work in the target field, these projects are the evidence, and a Projects section at the bottom of the page gets read last or not at all. Listing the school as an experience entry, with each project as a bullet under it (what it does, the stack, one notable feature), puts that work where the recruiter looks first. Recommend it when the Experience section would otherwise be empty or filled with unrelated jobs.

## 7b. Certifications

Certifications can support a CV when they are directly relevant and visibly applied (a candidate listing AWS Cloud Practitioner alongside AWS work bullets makes sense; a candidate with 8 unrelated certs and no applied work doesn't).

**Don't push candidates to add more certifications.** Beyond 3 to 4, a long cert list starts reading as "serial course-taker" (Estonian: *sarikoolituja*, with one *i*, not *sarjakoolituja*) rather than "applies what they learn". Quality matters more than quantity. When reviewing, recommend keeping certs that are:
- Directly relevant to the target role.
- Backed by something on the CV that shows the cert was applied (an experience bullet, a project, scripts written).
- Recent enough to be credible (5+ year old certs in fast-moving fields lose value).

When a previous CV had relevant certs that got dropped on revision, it can be worth bringing them back if they map to the candidate's direction. But keep the bar at "is this cert actually doing work for the CV" rather than "more certs is better".

## 8. Languages

List human languages with proficiency level (native, fluent, conversational, basic). Skip if only one language and it's the working language.

## 9. Length & layout

- 1 page: anyone with <5 years experience, or for entry-level applications
- 2 pages: 5+ years experience or relevant senior history
- Never 3+ pages outside academia

**For junior and entry-level applications, 2 pages is the ceiling.** A 3-page junior CV without a clear justification is a blocking finding: raise it under "What needs fixing" and in the action plan, not as polish. The fix is cutting by relevance to the target role, not evenly across sections: the material that proves the target direction keeps its detail, older or less related roles compress to one line each, trait lists compress to a skills line, and sections that add nothing (e.g. Interests) go. Frame the mechanism for the candidate: the reader's 30 to 60 seconds spread across three pages means nothing signals what matters most.

**Layout:**
- Single column scans faster than two-column for most ATS systems
- Sans-serif fonts (Inter, Helvetica, Arial) read better than serif on screen
- Consistent date format throughout
- Generous margins (≥1.5cm)
- No graphics that ATS can't parse (icons next to section headers are fine)

**Density:** a page can hold strong material and still overwhelm. If most sections are full paragraphs or multi-line bullets and nothing is visually differentiated, the reader can't tell what matters most, and the strongest points carry the same weight as the filler. Flag this as its own finding, not as a side note. The fix is cutting and hierarchy: 1-2 line bullets, fewer items per section, keywords bolded, the strongest material placed where the eye lands first. Don't fix density by adding more content or more sections.

## 10. ATS / keyword check

If a job posting was provided:
- Pull the posting's **full requirement set**, not just the tech stack. Postings list two kinds of criteria and you must map the CV against **both**:
  - **Technical / hard:** languages, frameworks, tools, methodologies, certifications, years of experience.
  - **Behavioural / soft:** the "we believe you have" / "to thrive in this role" traits, such as proactive attitude, curiosity and willingness to learn, teamwork, communication, ownership.
- For **each** requirement, check whether the CV evidences it, and address it explicitly:
  - Present → point to where it shows (a bullet, a project, a career move, a certification, a mentoring line) so the candidate knows it's landing.
  - Plausibly true but not visible → advise surfacing it through a concrete experience/project bullet, **never as a standalone "soft skills" list** (see the soft-skills guidance above). A career switch evidences willingness to learn; stakeholder work evidences communication; mentoring or self-started work evidences proactivity. Connect the trait to the proof already on the CV.
- Don't cover only the technical keywords and stop. If a posting names behavioural criteria and the feedback ignores them, the candidate loses the strongest part of their story.
- Don't recommend keyword stuffing; recommend integrating real ones into real bullets.
- **Rank the requirements before writing anything.** A posting names eight to fifteen things and they don't carry equal weight. Find the two or three the role actually turns on, usually the ones repeated across the duties and the requirements, and build the feedback around those. Everything else gets one line together, or nothing. Covering every requirement at the same depth produces a long response in which the deciding requirement carries no more weight than a nice-to-have, and it pushes the feedback past the three to five fixes the candidate can act on. When coverage and length pull against each other, length wins: cut the minor requirements, not the depth on the deciding ones.
- **Name the evidence; don't describe the category.** The rule for naming the exact keywords to bold applies here too. Say which line on the CV answers which expectation, and say which line should move up because of it. "Add a projects section with two or three pieces of work involving a database" names a category and leaves the candidate to work out what qualifies. "Your tutoring line is the troubleshooting evidence this role asks for, so it belongs first, and it needs the request volume and what happened to the bugs you reported" names the evidence. The candidate should never have to work out which of their own material answers the posting.
- **When the material isn't on the CV at all, ask for it by name.** A missing Projects section, or a requirement nothing on the page touches, leaves you nothing to point at. Don't fall back to naming the category and leaving the choice open ("add two or three projects involving a database"). Ask for the specific pieces: which //kood projects, what each one does, the stack, whether it's deployed and where, and which of them has the database work this role turns on. The candidate should finish reading knowing exactly what to go and write.

## Scoring guidance (internal, not shown to user)

When deciding what's worth flagging, prioritize:
1. **The CV doesn't answer "why this candidate for this role."** Nothing on the page maps to what the posting turns on, or the evidence is there but reads as a list of activities rather than things the candidate delivered. This outranks everything below it. See SKILL.md Step 1.
2. **The strongest evidence for this role isn't where the reader meets it first.** Entries ordered by date or by category instead of by weight for this posting, so the best match sits at the bottom of a list or under the wrong heading.
3. **Bullets that list responsibilities instead of what the candidate delivered** (most common issue, biggest impact, biggest space waster). The single most frequent CV problem: candidates describe what their role *covered* ("Manage warehouse budgets", "Process customs paperwork", "Responsible for X") instead of what they *achieved* ("Cut quarterly close time by 22% by introducing X process"). Outcomes do double work: they show the skill and the ownership. Push hard on this whenever you see it.
4. **The page's own signals fail the 30-second test:** an unexplained gap between the most recent dated entry and today, no contact info, a title or summary that doesn't state the direction. The gap is blocking (see SKILL.md Step 1). The title is a one-line wording fix: make it, and don't rank it above 1 to 3.
5. **Length and layout** (only if it actually hurts readability)
6. **Polish** (typos, formatting consistency), last priority unless severe

**Don't flag minor layout or rendering quirks** (a letter rendering oddly next to a date, slight kerning issues, etc.) unless they actively prevent the reader from understanding the CV. These are noise in the feedback and dilute the high-impact recommendations. Drop them rather than including them as fixes.

## On "scalable" and other filler buzzwords

Junior CVs frequently misuse words like "scalable", "robust", "complex", "advanced", "innovative", and "cutting-edge" as filler. These words signal capability the candidate hasn't yet earned. A recruiter or hiring manager who reads "built scalable web APIs" will ask "scaled to what?" in the interview, and the answer needs to be specific (concurrent users, RPS, data volume).

Watch the context rather than banning the words outright. "Scalable" is the clearest test: if the candidate hasn't built something with real users or measured load, nothing was actually scaled, so the claim isn't earned and should go. If they *can* back it with a number (handled N concurrent users, M requests/day), keep the fact and drop the adjective.

When reviewing, flag these usages and recommend either:
- Replacing the word with the concrete number or fact ("handles 50k req/day" instead of "scalable").
- Removing it entirely if there's nothing concrete behind it.

Never recommend the candidate keep a buzzword without backing.

## On junior positions

Junior CVs do not need pre-existing professional experience in the target field. That is the whole point of applying junior. Don't critique a junior CV for "not having SWE work history" or similar. The bar for a junior is:
- Clear direction in the title and summary.
- Some evidence of capability: projects, training, transferable skills.
- The "About Me" calibrated to what the CV actually shows (no overclaiming).

For career-changers applying junior, the previous-career experience is real signal, especially when bullets are reframed to outcomes that translate. Don't push them to claim industry SWE experience they don't have.

**When a posting states a minimum experience duration** (e.g. "at least 1 year as a developer") and the candidate's program/training time is close to but short of that bar, don't just flag the gap and note it's probably not disqualifying. Coach them to actively surface the practical, hands-on side of the training in their application (project-based work, real code shipped, team practices used) so the time reads as applied experience rather than classroom time. Give this as a suggestion, not just an observation.
