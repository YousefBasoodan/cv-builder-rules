# CV Builder Rules

A drop-in method and prompt set for anyone using an AI assistant (Claude, ChatGPT, Gemini, Copilot, etc.) to build or fix a CV that actually earns interviews.

Most CV advice tells you to "use strong verbs" and "add numbers" and stops there. This goes further: it treats the AI as a blunt, honest recruiter that interrogates you section by section, forces you to pick one clear identity, and converts vague tasks into provable achievements. The result reads like a candidate who knows exactly what they are, not a list of everything they have ever touched.

## The core idea

A great CV isn't about better words, it's about sharper focus. Lock one identity, build everything around it, and replace vague tasks with measurable results that prove what you can actually do.

## What's inside

- **`prompts/cv-builder.md`** — the main prompt. Paste it as the first message to any capable AI, and it becomes a professional recruiter that builds your CV with you, one section at a time, asking before it writes and never inventing anything.
- **`prompts/job-tailoring.md`** — the per-application prompt. Paste it with a job description and your CV, and it tells you the small, smart edits to make before applying, or tells you plainly that no change is needed.
- **`SKILL.md`** — the same method packaged in the Claude Skills format, so it can plug directly into Claude as a skill.

## The method (nine rules)

1. **Identity first.** Lock ONE primary role before writing anything. A CV spread across many roles reads as unfocused and loses. The headline is a positioning decision; the body must prove it; you must be able to defend it in interviews.
2. **Choose the identity by demand and defensibility.** Compare the related roles you are considering, weigh which has more opportunities in your market, and pick the one your real, verifiable experience can back up.
3. **Achievements, not tasks.** Every bullet is: strong action verb, what you built, the measurable result or concrete scope. "Optimized workflows" is a task. "Cut a manual process from 1-3 days to minutes" is an achievement.
4. **Quantify honestly, never fabricate.** Use real numbers where they exist. Where they don't, use concrete scope instead of fake numbers. Never invent metrics.
5. **Specific about you, general about your employer.** Be specific about what YOU built (tech, result). Be general about the company's confidential details (no client names, product names, internal codenames, or proprietary numbers). These never conflict.
6. **Claim only what you can defend.** For team projects, published work, or anything an interviewer can probe, make sure every line survives questioning. Past assistance and impressive labels are not worth a claim you cannot back up.
7. **Skills are a summary of proof.** Build the skills section after experience and projects. It should list keywords already proven above, not a wishlist. Spotlight your real differentiator; lead with your strongest tools; keep weak ones present but de-emphasized.
8. **Write the profile last.** The summary is a trailer for everything below it, so write it once everything it summarizes exists. Lead with competence and identity, never with "student" or "fresh graduate."
9. **One page, tightened not gutted.** Fit one page by cutting filler words and redundant phrases, never by deleting selling points. Front-load strengths in the section order: Experience and Projects together as the proof block, Skills before Certificates.

## How to use it

1. Open a chat with any capable AI assistant.
2. Paste the contents of `prompts/cv-builder.md` as your first message.
3. Answer its questions honestly and in detail. The quality of the output depends on the quality of your real numbers and your actual tech stack.
4. Work through it one section at a time. Do not let it rush; do not let it fabricate.
5. When you apply to a specific job, paste `prompts/job-tailoring.md` with the job description and your finished CV to get the minimal edits for that role.

## Using it as a Claude Skill
 
Beyond pasting the prompt (see "How to use it" above), the `SKILL.md` file follows the Claude Skills format, so it can be added to Claude as a custom skill. Anthropic's documentation has the current steps for adding one. Once added, Claude applies this method automatically whenever you ask it to build or improve a CV.
 
> Skill setup steps inside Claude's interface may change over time. If the steps differ from what you see here, check Anthropic's official documentation for the current way to add a custom skill.

## License

MIT. Use it, change it, share it freely. See `LICENSE`.

---

Built and shared by **Yousef Basoodan** (GitHub: [YousefBasoodan](https://github.com/YousefBasoodan)).
