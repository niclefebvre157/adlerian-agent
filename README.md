# Adlerian Reflection Agent

A structured AI coaching agent grounded in Adlerian psychology.

This agent helps you work through real-life situations by applying Adlerian psychological principles. It is not a therapist. It is a practical thinking tool that surfaces the deeper issue, picks the most relevant principle, and assesses how aligned your thinking and actions are with Adlerian psychology. It also supports journaling so you can track patterns and growth over time.

Inspired by the work of Alfred Adler and the books *The Courage to Be Disliked* and *The Courage to Be Happy* by Ichiro Kishimi and Fumitake Koga.

---

## What is Adlerian Psychology?

Adlerian psychology is a framework developed by Alfred Adler that centers on the idea that most of our struggles are interpersonal. It emphasizes personal responsibility, the separation of your tasks from others, and the courage to act despite social discomfort or the risk of being disliked.

At its core, it argues that happiness is not something that happens to you. It is something you choose through how you engage with the world and the people around you.

---

## Principles

The agent draws from five core Adlerian principles:

- **Separation of Tasks** — know what is yours to handle and what belongs to others
- **Courage to Be Disliked** — act on your values even when others may not approve
- **All Problems Are Interpersonal** — most suffering comes from our relationships, not our circumstances
- **Contribution is Your Purpose** — a sense of meaning comes from giving to others and to the community
- **Cooperation Over Winning** — relationships work best when the goal is harmony, not dominance

---

## Output Format

Every response follows this exact structure:

- **Principle** — the single most relevant Adlerian lens for your situation
- **Assessment** — a direct evaluation of whether your thinking and actions are aligned, partially aligned, or drifted from Adlerian principles
- **Reframe** — only included when a perspective shift is needed
- **Suggested Actions** — specific, immediately actionable steps when a change in behavior is needed. When you are already aligned, the agent may offer alternatives or additional options to consolidate your direction instead
- **Reasoning** — why this principle applies and why the actions matter

---

## Example Session

> **User:** I constantly compare myself to people my age who seem further ahead. Better jobs, more money, more put together. It makes me feel like I am falling behind and I do not know how to stop.

**Principle**
- Courage to Be Disliked

**Assessment**
- You are measuring your worth against a version of life that belongs to someone else
- Drifted — the comparison is pulling you out of your own task and into theirs

**Reframe**
- Their progress is their task. Your path is yours. There is no shared timeline you are late to.

**Suggested Actions**
- When the comparison hits, ask yourself: "What do I actually want, not what I think I should have by now?"
- Write down one thing you are building toward that is genuinely yours
- Notice when the feeling is about their life versus dissatisfaction with your own direction. They are different problems.

**Reasoning**
- Comparison borrows someone else's measuring stick and applies it to your life, which will always feel wrong
- Returning to your own task is the only way to move forward with clarity

---

## How to Use

Clone the repository and open it in Claude Code. The agent is configured automatically via `CLAUDE.md` and will be ready to use.

Share a real, recent, or recurring situation and the agent will respond in the structured format above. The agent works best when you are specific. The more concrete the situation, the more direct and useful the response.

---

## Journaling

The agent can save your reflections as journal entries. After a session, it may ask if you want to save it. Entries are stored in the `reflections` folder and capture the situation, principle applied, assessment, and suggested actions.

This is useful for spotting recurring patterns in your thinking and tracking how your alignment with Adlerian principles grows over time.

---

## Disclaimer

This agent is a reflective thinking tool, not a substitute for professional mental health support. It does not provide therapy, clinical advice, or crisis intervention. If you are struggling with your mental health, please speak with a registered therapist or mental health professional.

---

## AI Collaboration

This project was developed in collaboration with an AI assistant to support drafting, structuring, and refining content. All AI-generated and co-created content was thoroughly reviewed and evaluated. The final output reflects my own understanding, intent, and expertise. While AI assistance was instrumental in the process, I maintain full responsibility for the content, its accuracy, and its presentation. This disclosure is made in the spirit of transparency.
