# AI Model Benchmarks

## Magazine article summaries

![Score against API cost for the magazine summary benchmark. The x-axis shows estimated API dollars per 1,000 articles.](score-against-api-cost.png)

![Score against speed for the magazine summary benchmark. The x-axis shows measured seconds per article.](score-against-speed.png)

## Math lecture

### Verbatim quotes

Both charts use the same two excerpts of the non-math portion of the lecture notes, across 47 subtitle blocks. The token chart covers 13 Claude and 10 Codex models. Verbatim quote counts measure one aspect of detail.

![Verbatim quotes against reported output tokens for Claude Batch API and Codex CLI models.](math-lecture-notes-models-quotes-against-output-tokens.png)

Claude Sonnet 5.5 at medium effort produced 32 verbatim quotes in 52.4 seconds across two Antigravity CLI runs.

![Verbatim quotes against elapsed CLI runtime for Claude, Codex, and Gemini.](math-lecture-notes-models-quotes-against-cli-runtime.png)

### Teacher solution summaries

Three models summarized the same worked solutions at medium effort. Two blinded reviewers scored four checkpoints per problem across combinatorics, geometry, and number theory.

![Retained checkpoints out of 12 for teacher solution summaries. GPT-6.2 Astra and Claude Opus 5.5 each scored 11. Gemini 3.8 Flash scored 5.](math-lecture-teacher-solution-scores.png)
