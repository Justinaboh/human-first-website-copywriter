# Human-First Website Copywriter

An Agent Skill that helps an AI assistant research, plan, write, humanise, audit and optimise website content, from a rough business idea to finished, implementation-ready copy.

## What it is

A folder of instructions (`SKILL.md`) plus one specialist reference file that an AI assistant loads to behave like a website content strategist and conversion copywriter. It is not a template pack and not a single prompt: it defines modes, a workflow, quality standards, ethical limits and output formats.

## The problem it solves

Website copy is often generic, AI-sounding, unsupported by evidence, inconsistent between pages, or written before anyone decided what each page is for. This skill pushes the assistant to start from the business, the audience and the evidence, then write copy a real visitor can trust and act on.

## What it can do

- **Create from scratch**: turn a vague idea or incomplete brief into positioning, messaging, a sitemap and page copy.
- **Write complete website copy**: homepage, about, services, products, pricing, landing pages, contact, FAQ, case study framing, blog and resource pages, careers, legal page introductions, navigation, buttons, forms and microcopy.
- **Humanise** existing text while preserving facts and meaning.
- **Rewrite** for clarity, positioning, persuasion or tone.
- **Audit** existing website copy with prioritised findings and improved copy.
- **Work page by page**, or build a focused **landing page** around one offer and goal.
- **Expand** notes and headings into finished copy.
- **Develop a brand voice** guide.
- **Prepare a content handoff** organised by page, section and component, with stable content keys, for AI website builders and developers.

## How it works

1. The assistant infers the working mode from your request.
2. It reuses what you have already said and asks only the few questions that change the result.
3. If it has search tools, it researches the business, market and audience language. If not, it says so and works from your information.
4. It sets out messaging and structure, separating verified facts, research, interpretation and assumptions.
5. It writes, humanises, applies persuasive language only where evidence supports it, and checks conversion flow and consistency.
6. It delivers in a usable format and lists assumptions and proof still needed.

## What makes it different

- Never fabricates testimonials, credentials, statistics or case studies; unknown facts become labelled slots.
- Treats "human" as fit for the audience and brand, never as deliberate imperfection.
- Includes a persuasive-language reference with ethical rules and "when not to use" guidance.
- Scales to the task: a button label does not trigger a full strategy exercise.
- Produces content in a structure that can be moved into a website project.

## Who should use it

Founders, freelancers, agencies, marketers, product teams, consultants and developers who need website content, and people building sites with AI website builders or coding assistants.

## Repository contents

```
human-first-website-copywriter/
├── SKILL.md
├── README.md
├── LICENSE
└── references/
    └── 13-persuasive-language-and-power-words.md
```

- `SKILL.md`: operating instructions the AI follows.
- `references/13-persuasive-language-and-power-words.md`: power words by effect, motivation and awareness stage; overused words and alternatives; ethical rules.
- `LICENSE`: MIT.

## Installation

The skill follows the open Agent Skills format ([specification](https://agentskills.io/specification)). Platforms load skills in different ways, so check your platform's documentation for the current method. Common approaches:

- **Skill-aware tools (for example Claude or Codex environments)**: place the `human-first-website-copywriter` folder in the location your tool uses for skills, or upload the packaged folder through its skills interface. The folder name must match the `name` in `SKILL.md`.
- **Assistants without skill loading**: paste the contents of `SKILL.md` into the system or project instructions, and add the reference file as an attached or project file. Where the file cannot be attached, paste it after the main instructions.

No installation method is claimed to work identically everywhere, and this repository has not been tested on every platform.

## Example prompts

- "I'm starting a mobile bike repair service in Leeds. Plan and write my whole website."
- "Humanise this About page but keep every fact exactly as it is." (paste text)
- "Audit the copy on my homepage and pricing page and fix the biggest problems."
- "Write a landing page for our free 14-day trial aimed at operations managers at small logistics firms."
- "Define a brand voice for a friendly but precise accounting firm."
- "Give me the approved homepage and services copy as content keys I can paste into my website builder."

## Limitations

- It cannot verify your business facts; you must confirm anything tagged `[VERIFY]`.
- Competitor and audience research needs search tools. Without them it works from what you supply.
- SEO support is copy-level only; no ranking promises.
- Privacy policies and terms need review by a qualified professional.
- Translations and localisation need native-speaker review.
- Output quality depends on the assistant model and how well it follows skill instructions.

## Contributing

Issues and pull requests are welcome. Keep `SKILL.md` under 500 lines, keep references one level deep, and do not add features that require a specific proprietary tool.

## Licence

MIT. See `LICENSE`.
