---
name: wechat-style-analyzer
description: Analyze representative WeChat public-account articles to extract a reusable writing-style profile or build an original-writing skill. Use when the user wants to study, compare, document, or write with the structural characteristics of a public account; do not use for verbatim imitation or ordinary proofreading.
---

# WeChat Style Analyzer

Turn article samples into decisions another writer can actually use. Describe the reading experience and the mechanisms that create it; do not merely list adjectives such as “sharp,” “human,” or “insightful.”

## Analyze the evidence

Prefer at least three representative articles from different dates or topics. If only one sample is available, continue but label the profile provisional. Record the title, date, link or file, topic, and why each sample is representative.

Separate three kinds of signal:

- **Stable style:** patterns repeated across samples.
- **Topic convention:** choices caused by the subject rather than the account.
- **One-off flourish:** memorable wording that should not become a rule.

Do not treat copied quotations, guest posts, sponsored passages, or platform formatting as the account's native voice without evidence.

## Extract mechanisms

Analyze the dimensions in [references/style-profile-schema.md](references/style-profile-schema.md). For every claimed rule, include an observable signal and its intended reader effect.

Prioritize the parts that most change the result:

1. topic selection and reader promise;
2. title tension and information gap;
3. first-screen hook;
4. structural progression and paragraph rhythm;
5. evidence, examples, and transitions;
6. sentence texture, humor, and emotional distance;
7. ending and interaction design.

Quantify useful patterns when possible, such as title length, opening length, paragraph length, section count, data frequency, or ratio of narrative to analysis. Do not invent precision from a small sample.

## Produce a reusable profile

Write rules as conditional decisions, not slogans. Prefer:

> When the topic is abstract, open with a concrete scene or number, then reveal the larger argument within the first 300 Chinese characters.

Avoid:

> Be vivid and insightful.

Include positive rules, failure modes, and a short quality gate. Mark confidence as high, medium, or low when evidence is uneven.

If the user requests a new Skill, keep `SKILL.md` concise and place sample notes, detailed examples, and long rubrics in `references/`. Create only files that will be used.

## Draft in the derived style

Preserve the user's facts, stance, constraints, and publication goal. Reproduce abstract qualities such as pacing, structure, directness, or evidence density without copying distinctive phrases, metaphors, anecdotes, or signature wording. Never imply that the original account or author wrote, endorsed, or reviewed the result.

If style and factual accuracy conflict, accuracy wins. If the reference relies on weak claims, keep the useful presentation pattern and replace the evidence.

## Quality gate

Before delivering, check that:

- the first screen identifies the conflict and why the reader should care;
- each paragraph adds a fact, example, turn, or consequence;
- abstract judgments are supported by concrete detail;
- repeated sentence templates and mechanical transitions have been removed;
- the draft sounds natural when read aloud;
- the result is recognizably in the same editorial family without being a disguised copy.
