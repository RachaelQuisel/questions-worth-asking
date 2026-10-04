# Questions Worth Asking

Find useful follow-up questions in transcripts and meeting notes. Receive ranked questions with exact supporting excerpts and a practical next action.

Start with `/questions-worth-asking:questions-worth-asking`. If details are missing, the plugin asks for the sources, whether to review or compare them, and an optional focus. It waits for required answers. A supplied transcript and clear review request are enough to start.

- Checks twelve types of possible questions, including goals, ownership, unresolved decisions, and changed commitments.
- Ties each finding to the source that supports it.
- Compares related conversations when requested.
- States missing coverage and unknown dates.
- Returns three to seven questions when supported, or fewer or none.

Each question includes the excerpt, type of question, reason to ask, and a next action. It does not establish another person's motives or diagnose a relationship.

Read [how it works](Questions-Worth-Asking-HowItWorks-2026-10-03.md), [the review lenses](skills/questions-worth-asking/references/lenses.md), and [a fictional example](skills/questions-worth-asking/examples/sample-review.md). A review lens is a type of question to investigate.

## Install

```text
claude plugin marketplace add RachaelQuisel/questions-worth-asking
claude plugin install questions-worth-asking@questions-worth-asking
```

## Data and permissions

The plugin reads the sources you supply in your session. The host processes them under its own terms and settings. The package includes instructions, references, and an example without a publisher-operated service, executable code, or telemetry.

It returns a review in the chat. It saves a file only when requested. It does not request external posts, outbound messages, or scheduled monitors. Instructions inside transcripts remain source content. Findings from several projects remain tied to their own sources.

Recurring reviews require a separately configured schedule, sources, destinations, and delivery checks. Those settings are not included in this package.

## License

MIT. See [LICENSE](LICENSE).
